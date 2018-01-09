# Backup for docker setup

**Postgres backups**

Create backups of postgres dbs that run on docker using [](https://github.com/p2pu/marvin/blob/master/backup/roles/postgres_backup/files/backup-postgresql.sh)https://github.com/p2pu/marvin/blob/master/backup/roles/postgres_backup/files/backup-postgresql.sh

*   Create a container that always run with cron inside to do backups

        *   what will performance/memory impact be on host server?

*   Start up a new container for each backup

        *   will need to setup cron on docker host
    *   want to keep host as clean as possible, but maybe backups are ok?

*   Run backups on docker host

        *   will need to install extra software on host

**Add backups as part of django app**

*   Create a reusable django app that backs up media and db and uploads to S3 using grandfather, father, son rotation scheme.
*   Run backup task using celery

Questions

*   How should new settings be indicated? Just in docs?

pg_dump must be same or later version that the server!! Current version of the server is 9.4 while application container runs 9.3 !!!

Possible solutions

*   update client on application instance :(
*   use other backup method :(

Left to do

*   variables for live env
*   celery tasks to do backups
*   downgrade docker image for live server
*   test what's going wrong with log files on staging server

**Do backups using containers**

*   add a volume for backups to postgres server
*   use "docker exec" to run pg_dumpall to create backup
*   use docker with volumes from to upload & rotate to s3
*   cron job to do docker execc
*   cron job to do upload & rotate