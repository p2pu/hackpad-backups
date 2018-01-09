# Sysadmin: SSL using letsencrypt

**Domains:**

*   www.p2pu.org - 27 May
*   community.p2pu.org
*   discourse.p2pu.org
*   courses.p2pu.org - 30 May
*   badges.p2pu.org - 30 May
*   learningcircles.p2pu.org - 29 May
*   info.p2pu.org

Run in docker to avoid installing all dependencies locally

*   docker run --name lets-encrypt -it -v /home/dirk/letsencrypt/:/var/letsencrypt ubuntu:14.04 /bin/bash

Need to use manual auth or run letsencrypt on server

*   ./letsencrypt-auto certonly --test-cert -a manual -d www.p2pu.org -d info.p2pu.org -d community.p2pu.org -d badges.p2pu.org -d learningcircles.p2pu.org

**Different hosting services**

*   AWS S3 / Cloudfront (www.p2pu.org) - add file and update
*   discourse (community & discourse) - [](https://meta.discourse.org/t/setting-up-lets-encrypt-cert-with-discourse-docker/40709)https://meta.discourse.org/t/setting-up-lets-encrypt-cert-with-discourse-docker/40709
*   Apache - supported by client or manual
*   Django + Nginx + Docker - 

**Options for installing**

*   Manually auth, get and install certs

        *   1 cert to rule them all
    *   **single certs (1 for discourse, 1 for courses, 1 for learning circles, 1 for homepage)**

Get certificates for use with learningcircles.p2pu.org

*   docker run -it --rm -p 443:443 -p 80:80 --name letsencrypt \
*               -v "/etc/letsencrypt:/etc/letsencrypt" \
*               -v "/var/lib/letsencrypt:/var/lib/letsencrypt" \
*               quay.io/letsencrypt/letsencrypt:latest auth

Lets encrypt certificates are only valid for 90 days!!

Discourse config:

*   [](https://meta.discourse.org/t/setting-up-lets-encrypt-cert-with-discourse-docker/40709)https://meta.discourse.org/t/setting-up-lets-encrypt-cert-with-discourse-docker/40709
*   Problem with multisite - above method would only get certificate for primary domain - currently discourse.p2pu.org

**www.p2pu.org -> AWS CloudFront**

[](https://bryce.fisher-fleig.org/blog/setting-up-ssl-on-aws-cloudfront-and-s3/)https://bryce.fisher-fleig.org/blog/setting-up-ssl-on-aws-cloudfront-and-s3/

[](https://nparry.com/2015/11/14/letsencrypt-cloudfront-s3.html)https://nparry.com/2015/11/14/letsencrypt-cloudfront-s3.html

*   Generate SSL cert using docker + letsencrypt with manual verification
*   install aws cli - pip install awscli
*   configure aws CLI: aws configure
*   upload certificates:

*   aws iam upload-server-certificate \
*     --server-certificate-name www.p2pu.org \
*     --certificate-body [](file://./letsencrypt/live/www.p2pu.org/cert.pem)file://./letsencrypt/live/www.p2pu.org/cert.pem \
*     --private-key [](file://./letsencrypt/live/www.p2pu.org/privkey.pem)file://./letsencrypt/live/www.p2pu.org/privkey.pem \
*     --certificate-chain [](file://./letsencrypt/live/www.p2pu.org/chain.pem)file://./letsencrypt/live/www.p2pu.org/chain.pem \
*     --path /cloudfront/

*   I can probably turn the whole processes into a single python script

**learningcircles.p2pu.org**

*   sudo docker run --name lets-encrypt -it -v /home/p2puadmin/letsencrypt/:/var/letsencrypt -p 80:80 -p 443:443 ubuntu:14.04 /bin/bash
*   git clone [](https://github.com/certbot/certbot.git)https://github.com/certbot/certbot.git
*   ./certbot-auto certonly --standalone -d learningcircles.p2pu.org
*

**courses.p2pu.org**

*   wget [](https://github.com/xenolf/lego/releases/download/v0.3.1/lego_linux_386.tar.xz)https://github.com/xenolf/lego/releases/download/v0.3.1/lego_linux_386.tar.xz

Stop apache

*   <s>./lego/lego run -d courses.p2pu.org -m admin@p2pu.org -a --webroot /var/www/</s>
*   ./lego/lego -m admin@p2pu.org -d courses.p2pu.org run

Start apache

**badges.p2pu.org**

*   mkdir /var/www/.well-known/
*   sudo chown -R www-data:www-data /var/www/.well-known/

Update apache config to share .well-known contents at /.well-known

*   sudo ./lego/lego -m admin@p2pu.org -d badges.p2pu.org --path=/etc/letsencrypt --webroot=/var/www run

TODO: cron job to renew certificates

**Renewing www.p2pu.org**

Run docker with old letsencrypt certbot & mount /etc/letsencrypt volume

*   docker run --rm --name lets-encrypt -it -v /home/dirk/Downloads/letsencrypt/:/var/letsencrypt -v /home/dirk/workspace/servsec/letsencrypt/:/etc/letsencrypt ubuntu:14.04 /bin/bash
*   cd /var/letsencrypt && ./letsencrypt-auto
*   git pull (outside docker container)
*   ./letsencrypt-auto certonly -d www.p2pu.org

Outside docker:

*   aws iam upload-server-certificate \
*     --server-certificate-name www.p2pu.org-aug-2016 \
*     --certificate-body [](file://./letsencrypt/live/www.p2pu.org/cert.pem)file://./letsencrypt/live/www.p2pu.org/cert.pem \
*     --private-key [](file://./letsencrypt/live/www.p2pu.org/privkey.pem)file://./letsencrypt/live/www.p2pu.org/privkey.pem \
*     --certificate-chain [](file://./letsencrypt/live/www.p2pu.org/chain.pem)file://./letsencrypt/live/www.p2pu.org/chain.pem \
*     --path /cloudfront/

<s>Superseded by </s>[](https://docs.google.com/document/d/1ceGEbTTvicyYbV5HWpQW7Wg3OgEvwz_NjBdwOlvHZNQ/edit)<s>https://docs.google.com/document/d/1ceGEbTTvicyYbV5HWpQW7Wg3OgEvwz_NjBdwOlvHZNQ/edit</s>

[](https://paper.dropbox.com/doc/Sysadmin-SSL-using-letsencrypt-UD0DKooiMMVWIiWM0gNmy)https://paper.dropbox.com/doc/Sysadmin-SSL-using-letsencrypt-UD0DKooiMMVWIiWM0gNmy