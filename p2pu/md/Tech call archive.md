# Tech call archive

## 14 Nov 2013

Progress

*   Homepage

        *   Added a Lab Reports section
    *   Made some minor style tweaks (e.g. margin on community section)
    *   Added Mythical Erika's face to the community section (home page is now complete) - haha!
    *   Pull request has been sent.

*   We have successfully moved archive.p2pu.org to GitHub pages

        *   Now this page is static, so it probably lost some of the features, like search and login
    *   It comes up faster (GitHub "CDN" is better)

*   Blog post about Echonest grouping
*   PWYM email problem resolved
*   Almost done with group photos for PWYM
*   DLMOOC pilot debrief

        *   Questions about grouping, but need to discuss how to group (and what we want to use to support groups)
    *   How to organize (and support) chat back channel for live sessions

                *   Recommendation: use unhangouts instead of candy

*   Migration to Hackpad - Turned off creation of new etherpads on [](http://pad.p2pu.org)[http://pad.p2pu.org](http://pad.p2pu.org)

Priorities

*   DLMOOC talk with HTH (Thu 4pm US Eastern)
*   Mech MOOC Strategy Call (Dirk will confirm date/time today)

        *   What's  our long term strategy? Are we building a commodity platform for  reasonably technical people - or - are we building an experimentation  toolkit that we can deploy easily? What's the size of the audience? 
    *   Noting revised strategic direction - P2PU as resource/knowledge hub - mech MOOC should add to that
    *   What's  long term strategy? Are we building a commodity platform for reasonably  technical people? Are we building an experimentation toolkit that we  can deploy easily?

*   Push homepage changes to server
*   Backups for info.p2pu.org
*   Backups for thepeople.p2pu.org 
*   Talk with CR about some tech status, process and strategy
*   Shut down dev linode, haven't received any objections to this so far
*   PWYM group photo: get copy from vanessa and schedule when needed

Problems

Process

*   How do we manage support requests for MOOC users going forward? This is especially an issue for larger MOOCs.

## 7 Nov 2013

Parking Lot:

*   Discuss next steps Wordpress for Schools

Progress

*   PWYM groups created, content updated, ready to run, but mailgun is blocking things atm :(

Priorities

*   Talking with Karen about DLMOOC tomorrow
*   Resolve issues with mailgun
*   Sending class photos as part of email (great idea / as png?)

Problems

Process

## 24 Oct 2013

Progress

*   DLMOOC signup page embedded in Wordpress site
*   info.p2pu.org moved to digital ocean
*   Gentle Intro to Python users grouped
*   Dumped data for the 4th sequence of Gentle Intro to Python
*   Removed old data from the Gentle Intro to Python db to keep using heroku free hosting

Priorities

*   Music MOOC grouping script - getting good data from Echonest, need to turn that into groups now
*   Make HTML copy of archive.p2pu.org and host using github pages
*   Send email to grouped users doing the Mechanical MOOC
*   Update Tech Accounts doc to show where everything is running
*   Migration Plan (and blog post)

Process

Problems

## 17 Oct 2013

## 10 Oct 2013

*   Progress

        *   Class photo

                *   [](http://mooc-signup-test.herokuapp.com/gallery/1/)[http://mooc-signup-test.herokuapp.com/gallery/1/](http://mooc-signup-test.herokuapp.com/gallery/1/)
        *   Error checking/interface
        *   Simplified backend - authenticate first and then update, no confirming update

        *   DLMOOC

                *   setup wordpress on dreamhost
        *   setup heroku instance to use for pilot signup

        *   Python MOOC

                *   1st emails are starting to go out (now almost fully automated) <- Success!!!

        *   Set up a free (non-profit) P2PU dreamhost account <- This is great!
    *   Started conversation with translators
    *   Badges

                *   new dashboard is out (everything is different and better)

                        *   users get a better snapshot of their own badges, 
            *   see conversations about badges they are trying to get, 
            *   list of reviews that others are waiting on

                *   few bugfixes deployed just now

*   Priorities

        *   Class photo

                *   implement sending email to all users in a sequence with a custom link to the class photo
        *   test on other browsers

        *   Music MOOC

                *   grouping script using Echonest

        *   DLMOOC

                *   get signup running through Wordpres blog
        *   talk to Karen to confirm scope and expectations for the pilot

        *   Python MOOC

                *   support for copying emails
        *   test 'class photo' with this MOOC (confirm with Steve)
        *   group users using info from 'class photo'
        *   course work starts 21 Oct

        *   Badges

                *   setting up the LRMI data  (PS: If it's 1-2 days of work, let's do it now. If it's more than that,  let's come back to this in November. There are more interesting / more  urgent things to work on). 

## Questions about P2PU strategy

*   Platforms

        *   do we focus on free/open source platforms? YES
    *   or rather, how do we handle closed platforms? We use them if they let us get all our data out
    *   what happens with existing platform? Lernanta -> migrate to something else
    *   do we keep learner profiles on p2pu.org. 
    *   are there cases when we host a platform (for a little while)?
    *   would we take on another project like the badges platform?
    *   Lernanta (example for a platform we can turn off)

                *   We are not learning new things from it
        *   We can reasonably ask users to take more responsibility for their own tech
        *   Good alternatives exist (wordpress, tumblr)

*   Schools
*   R&D

## 3 October

Progress

*   Music MOOC

        *   Copy updates

*   Class gallery

        *   Styling updates ( not done )
    *   Scaling images uploaded to S3

*   Deeper learning MOOC

        *   Talk with Karen about tech requirements
    *   Registered Dreamhost account (thanks Bekka!)
    *   [](http://mooc-signup-test.herokuapp.com/gallery/1/)[http://mooc-signup-test.herokuapp.com/gallery/1/](http://mooc-signup-test.herokuapp.com/gallery/1/)

*   Python MOOC

        *   created next sequence

Priorities

*   Fax papers to dreamhost for free hosting
*   Class gallery

        *   Add gallery link to welcome email
    *   Simplify db (got unnecesarily complicated)
    *   Add page to request email with gallery link
    *   Styling -> change forms to in place edit

*   DLMOOC

        *   setup MOOC instance for pilot
    *   Create dreamhost account for Karen

*   MechMOOC

        *   ability for admin to see number of signups
    *   ability to see/download list of signups

Problems

*   info.p2pu.org slow

## 26 Sept

Music MOOC

*   Progress

        *   Domain: [](http://www.playwithyourmusic.org)[http://](http://www.playwithyourmusic.org)[www.playwithyourmusic.org](http://www.playwithyourmusic.org)
    *   Signup form with updated questions
    *   Updated copy + image
    *   Changed default top menu

Adwords

*   [Bekka Kahn](https://p2pu.hackpad.com/ep/profile/BT4g65BvPRV) talked with Lucas Monteiro
*   Adwords access for Lucas and Joao

MOOC class photo

*   Progress

        *   Allow cross site uploads of images to S3
    *   get info from twitter

Translation

Development process

*   Where should we report things like problems with CSS framework? Github issues feels like the right place

Badges

*   Progress

        *   Selenium test installed and working
    *   Travis CI alingment with selenium tests 
    *   Dashboard is almost there (only homestrech) :)

                *   Had a talk with VMG and decided on finalization

        *   There was a bunch of new funcionalities deployed yesterday

                *   Editing a Badge after it already published
        *   New styling upon badge creation, editing
        *   Added toolbar on Badge view from where user is able to push to backpack, edit or delete
        *   Requirements can be edited with richtext editor
        *   Link to the courses can be added

*   Priorities 

        *   Dashboard
    *   LRMI
    *   Blogpost about edit a Badge
    *   Now that users can add links to the Badges, how worried should we be about spam?

DLMOOC

Reports

## 19 Sept

<u>Progress</u>
<ul><li>Hackpad

*   it's free if we create public pads!
*   don't know if there is a limit on the number of users
*   potential drawback / issue -> no anonymous access. it requires people to sign in to edit, don't know if this will be a problem for other people?
*   We can export our pads to make backups if we need to!
</li>
<li>MOOC class gallery

*   WIP running at: [](http://mooc-signup-test.herokuapp.com/gallery/)[http://mooc-signup-test.herokuapp.com/gallery/](http://mooc-signup-test.herokuapp.com/gallery/)
*   Cannot get email address from twitter ([](https://dev.twitter.com/docs/faq#6718))[https://dev.twitter.com/docs/faq#6718](https://dev.twitter.com/docs/faq#6718))[ ](https://dev.twitter.com/docs/faq#6718%29This)This  means that we need to ask a user for their email and let them do a  twitter authentication using OAuth. We can drop the twitter oauth and  just ask them for a twitter handle and email address?
</li>
<li>Dumped latest databases of p2pu.org and badges.p2pu.org for June. Also gave access to the student intern working on it</li>
<li>Badges

*   Now we allow editing of requirements after it has been published
*   Checking availability of Badge title with ajax
*   P2PU course can be linked within requirements field which is edited with rich text editor
</li>
<li>Browser testing

*   AWS Console asscess (for Philipp personal account)

Priorities

*   Mechanical MOOC profile gallery

*   Browserstack:

Process

*   AWS Console asscess

        *   interesting reaading: [](http://aws.amazon.com/cli/)[http://aws.amazon.com/cli/](http://aws.amazon.com/cli/)

Problems

## 13 Sept

Progress

*   MOOC class gallery (mini user profiles) coming along - need to update CSS
*   Investigating etherpad issues (others are having them as well)
*   Homepage design review
*   DLMOOC CSS -> CSS Framework

        *   remove github stuff, make partners page, put p2pu logo on the right, move signup above description, add conference logo

*   Working on CSS framework

        *   a lot of work and testing done

Priorities

*   What are our plans for info.p2pu.org?

        *   Is [](http://p2pu.github.io/p2pu-css-framework/components.html)[http://p2pu.github.io/p2pu-css-framework/components.html](http://p2pu.github.io/p2pu-css-framework/components.html) up to date with the latest CSS
    *   [](http://thepeople.p2pu.org/t/updating-info-p2pu-org-mostly-removing-content/216/3)[http://thepeople.p2pu.org/t/updating-info-p2pu-org-mostly-removing-content/216/3](http://thepeople.p2pu.org/t/updating-info-p2pu-org-mostly-removing-content/216/3)

*   Analytics

        *   Stilll waiting for Nadeem (he is quite busy)
    *   a bit stucked up with badges and moocs now

*   MOOC class gallery

        *   consider twitter login to get pic

*   Badges

        *   dashboard is getting aligned with recent testing
    *   editing badge after already published

*   Explore hackpad as etherpad alternative

        *   DU: to investigate per user pricing?

Problems

*   EP too pasionate about some topics :)

Process