# Tech call

Thursday / Time -- 10.00am US Eastern (please update your local times accordingly)

Old Notes: 

*   [](http://pad.p2pu.org/tech-old-notes)[http://pad.p2pu.org/tech-old-notes](http://pad.p2pu.org/tech-old-notes)
*   [](http://pad.p2pu.org/p/tech-2012-2013)[http://pad.p2pu.org/p/tech-2012-2013](http://pad.p2pu.org/p/tech-2012-2013)

Project Pipeline -> [](https://trello.com/board/project-pipeline/4ec0f020c137ff072a5d8afa)[https://trello.com/board/project-pipeline/4ec0f020c137ff072a5d8afa](https://trello.com/board/project-pipeline/4ec0f020c137ff072a5d8afa)

## Current projects

Consider updating/transferring WIP list toTrello: [](https://trello.com/b/8NlzI2nG/wip)https://trello.com/b/8NlzI2nG/wip

*   Mechanical MOOCs

        *   Future - got 3-4 expressions of interest in more use, via the homepage survey.  Transfer discussions to thepeople and see if can be progressed
    *   DLMOOC
    *   Python MOOC - waiting on 2000-2500 sign-ups before next run.  Would be good to package data and export

                *   data
        *   interest guage

        *   Music MOOC - handoff to Alex/NYU nearing completion.  
    *   (Offline groups) - progress as IoT project(?)
    *   Data/statistics mooc
    *   (Writing MOOC)

*   Lernanta

        *   Archiving old style courses - Erika's blogpost about ready to go --> starts countdown to archiving old courses.
    *   Figure out what we should do with new courses

                *   SoO courses
        *   SoW challenges
        *   what else is 'new courses'

        *   Future of P2PU profiles

*   Badges

        *   future of badges

*   P2PU Blog
*   Schools

        *   School of Open new landing page (-> new home?)

                *   Have discussed with Jane - maybe willing to use Github pages
        *   They have a resource (Tim G)

        *   School of Webcraft

*   Data product for lernanta data
*   P2PU homepage/blog ??

        *   cleaning up blog??
    *   further changes to homepage??

*   Course re running open courses

## Parking Lot (for next call): 

*   Badges might need a SSL as well

## Feb 6 2014

Progress

*   Jekyll course template

        *   basic template & documentation
    *   supports Google Analytics and Disqus
    *   we can, improve design, add social sharing functionality, figure out a signup method, optimize SEO, LRMI, method for listing on P2PU

*   DLMOOC

        *   some support wrt users who signed up for pilot but not real course (+- 40)
    *   investigating chat options

*   Data

        *   data.p2pu.org - created for upcoming data release
    *   data for PWYM, for the report VMG is working on - I learned to pivot
    *   reviewed data dictionary and data for the data release

Priorities

*   DLMOOC chat client

        *   we need to figure out a chat solution. Watching a live stream and engaging through chat is a basic requirement

*   Data release

        *   update site content 

                *   basic introduction to why we are doing it
        *   specifics about this data release (they call it a data dictionary)
        *   licensing terms
        *   how to reference the data

*   SOO Landing page

        *   Mockup is a WIP
    *   Working on this with Jane

Process

Problems

*   Dreamhost hosting - we had trouble with both the DLMOOC and info.p2pu.org. If we don't use dreamhost we should probably get 1 server where we do Wordpress hosting or get someone else who does proper Wordpress hosting

## Jan 23 2014

*   Cleaning out the Tech Accounts Document, considering possible wiki

Progress

*   IoT talk
*   DLMOOC 

        *   moved to digital ocean - there is now a ansible script to setup WP hosting: [](https://github.com/p2pu/marvin/tree/master/wordpress)https://github.com/p2pu/marvin/tree/master/wordpress
    *   We setup a weekly meeting on Mondays (30 min / 12pm ET)

*   Data release

        *   initial site up at data.p2pu.org - just a copy of reports.p2pu.org -> do we need to distinguish the look somewhat?

*   thegovlabacademy.org moved to their own Dreamhost account

        *   the down time was less than 2 hrs (happened on Saturday)

*   SOO Meeting about the home page

        *   had a meeting with Jane to discus the requirements for the home page
    *   we are working on making a theme for SOO home page for WP

Priorities

*   Time estimate for IoT project
*   Project plan/proposal for SoW
*   Data release

        *   Update contents
    *   Get recent data for June closer to actual release (db & disqus comments)

*   Apollo course listing

        *   what are we currently lacking for this? better descriptions for the courses?

*   DLMOOC

        *   disable dreamhost VPS

*   First release of SOO home page (Wow - very cool! Can we see a draft version? Or is the first release the draft? Yes, I am working on it as we speak)
*   Reports publishing

        *   LCL report is still on a waiting list
    *   Assessment report as well (but expecting to be ready till the end of the week?)

*   Investigate the Badges issue reported from Vanessa

Process

Problems

*   DLMOOC server performance
*   DLMOOC people dropping from hangout and unable to connect again
*   Mailgun deprecating mailboxes and deleting messages in them end of February
*   p2pu.org went down on Tuesday evening - may have been because it has been running for a while. We should consider using a process monitoring service like supervisord to automatically dump logs and restart server if something like this happens.

        *   We had 100% increase in traffic on Sat/Sun. 
    *   4,998 visits from [](http://www.analyticsbug.com/)http://www.analyticsbug.com/

Process (additional): 

*   Support - role and resourcing from here?

        *   I've created an item in the Community call hackpad

*   How do we use this call going forward? (Dirk brought this up at the beginning). cf Trello - useful or not? 

## Jan 16 2014

Progress

*   Due to an plugin update thegovlabacademy.org was temporarily out of action (1hr)

        *   It raises an issue of updating plugins on WP
    *   WP gives more freedom, but it also allows people to break their site

*   To request of Alex I put the FB share and like buttons on Badges as well as made some copy changes
*   Reports got new report (LCL Report) - [](http://reports.p2pu.org/reports/learning_creative_learning/lcl_index.html)http://reports.p2pu.org/reports/learning_creative_learning/lcl_index.html

        *   Bekka knows git and HTML now (great!)
    *   Had the conversation with Dirk and we agreed we can try and make more visual reports as well as more "text heavy"

*   Talked with Sarah (and June) about data

        *   busy exporting data from disqus (XML that needs to be processed)

*   Echonest blog post finally posted! (Great post, I enjoyed reading it) No response from Echonest though (Worth following up?)

Priorities

*   Backup for hackpad this week
*   Transfer thegovlab hosting from philipp account to govlab account
*   Fix bugs with pushing badges to backpacks
*   pingdom account for p2pu
*   Cleaning out info.p2pu.org WP

        *   I don't think we need 150 themes, so I would like to delete all of them but the one we we are using (Yes, please)

*   Redesign template for info.p2pu.org
*   Publish blog post about archiving ([](https://docs.google.com/a/p2pu.org/document/d/1a46cKTzyDH_pkHMeVFd4n1ZSxGhLH6zm93MNS4x_hdY/edit))https://docs.google.com/a/p2pu.org/document/d/1a46cKTzyDH_pkHMeVFd4n1ZSxGhLH6zm93MNS4x_hdY/edit)

Problems

Suggestions:

*   bob = your_uncle;
*   mmm(bob);
*   ba dupa dop

## Jan 9 2014

Progress

*   info.p2pu.org

        *   moved hosting back to dreamhost (free and better managed)
    *   shut down and destroyed digital ocean server

*   I tried out [](https://github.com/benbalter/wordpress-to-jekyll-exporter)https://github.com/benbalter/wordpress-to-jekyll-exporter

        *   it is useful, but not perfect - had problems with the markdown it generated - errors and missing iframes
    *   only exports content, not layouts

Priorities

*   Blog post about archiving old courses/challenges
*   Schools, talk with Jane about School of Open's landing page. She expressed interest in trying github pages.
*   Blog design alignment to p2pu.org design

Problems

*   Adding courses to schools doesn't work anymore!

Process

## 19 Dec 2013

Progress

*   Using G+ to get profile info for class photo

        *   We can get profile info through the API ([](https://developers.google.com/+/api/latest/people/get))https://developers.google.com/+/api/latest/people/get) if we can get a users unique ID. Normally it is in their profile link: [](https://plus.google.com/u/0/116157284498773185129)https://plus.google.com/u/0/116157284498773185129
    *   Custom URLs for G+ present a problem, but since they make you agree to ToS and add verify a USA cell number I'm guessing not many people will have it.

*   Updated discourse to run latest version

        *   Didn't update config files - nothing important changed atm
    *   note: code lives at /home/discourse/discourse and not /var/www/discourse
    *   Notifications now come from noreply @ p2pu.org
    *   Reply by email is working using a P2PU gmail account - discourse @ p2pu.org
    *   Creating new topics by email is not yet supported

*   Setup billing alerts for AWS and

        *   changed keys to IAM keys so that it can't be used to spin up EC2 instances and mine bitcoins

*   Confirmed that EP have SSH access to all servers and other accounts
*   Quick look at Jekyll and github pages for courses

        *   nice in that it can keep content and framework separate to an extent
    *   too technical for someone familiar with web basics

*   DLMOOC

        *   new domain dlmooc.net that redirects to dlmooc.deeper-learning.org
    *   had some issues with this - what IP does dreamhost use when hosting a domain

*   DNS domain transfers

        *   transferred all domains from PS account to P2PU account
    *   don't know if this went through fine, I get "You can't add that domain: parent domain p2pu.org is already in our system" when I try to setup schoolofopen.p2pu.org
    *   @PS: Does p2pu.org still show up in your account?

Priorities

*   Archiving old p2pu.org courses

        *   CR: aim to get blogpost up in first 2 weeks of Jan (with this: work out process for any notification/additional checking we need to do prior to actually archiving)
    *   If we use something like Jekyll when we archive the old courses we can maintain content separate from the course HTML
    *   If we use wget we have a perfect look-a-like, but content will be mixed with general layout HTML

*   Pingdom alerts for other servers

        *   [Erika Pogorelc](/ep/profile/oTNkHa0lFrI) sent them email this morning asking about if they offer something for non-profits, so now we wait

*   Jekyll

        *   how does i18n work

*   Dump data for PWYM and get basic stats
*   Govlab Dreamhost account

        *   created today, but not verified yet

Process

*   Difference between Dirk call and Tech call - CR:agreed :).  
*   Would we be ok doing one more sprint with GovLab?

Problems

## 12 Dec 2013

<u>Progress</u>

*   Emails going out from p2pu.org

        *   2112144 sent since the start of this year
    *   1624480 comment notifications in English
    *   52471 comment notifications in Spanish
    *   13126 signup notifications
    *   829 task creation notifications
    *   18876 badge review notifications
    *   20109 following notifications
    *   363563 "made a comment in your course" (Wall updates)

*   Mechanical MOOC group communication alternatives ([Mechanical MOOC group communication alternatives](/XZsQnZz3Rkk)) [specifically G+ and Discourse]

        *   Does not seem like we can subscribe people to categories 

                *   PS: do we know when Discourse are planning to implement "subscribe to category"? 

        *   CR: other issues we want from a platform

                *   licensing? does it have to be CC? or just broad enough to be "open" for our values?

                        *   G+ doesn't prevent a CC licence (tbc)
            *   Discourse does allow CC, you can even sel-host the platform

                *   accessibility:

                        *   can we manipulate/extract/export content in bulk easily, etc

        *   G+

                *   Restrictive API limits what we can do
        *   Lack of analytics we can get out of it
        *   Feature development out of our control (we have no input in future direction)

        *   What's the next project we need this for? (What's the timeframe for our decision?)

*   pad.p2pu.org archived and EC2 instance shut down (P: this makes me disproportionally happy - thank you!!!)
*   Talk with Jane Park about SOO and archiving old challenges

        *   How did this go? Went well! notes at [](http://etherpad.creativecommons.org/p/SOO_call)http://etherpad.creativecommons.org/p/SOO_call
    *   SoO buy-in to a steady transition away from courses platform (aiming to minimise P2PU development time spent replicating funcitonality provided better, cheaper elsewhere)
    *   developed a roadmap for 2014 phased transition
    *   SoO plans 3 cycles of courses; we could aim to transition bits in line with each cycle, ie

                *   1st cycle (~Mar-Apr 2014): we aim for new SoO landing page [kicking off now - see further down this hackpad]
        *   2nd cycle (Jul-Aug 2014): we aim for moving existing SoO content on courses 1.0 to latest courses version; and new 'peripheral' functionality as needed by school  - eg new course listing, profiles, community forums.. whatever seems worth moving/pursuing/bang for buck
        *   3rd cycle (fall 2014): aim for solution on transitioning content/course hosting itself ("create a course")

*   Tech blogpost about grouping using Echonest done. Waiting for feedback from Echonest

*   Govlab

        *   moving tickets forward in a steady stream
    *   waiting for some answers from Cosmo
    *   process: communicate by google chat/email rather than just trello

*   Dumped latest data for PWYM mooc

<u>Priorities</u>

*   Update discourse server to run latest version (reply by email? <- Yay!!!)

        *   check config for reply by email

*   Push updated front page with link for "Run your own Mechanical MOOC" to server
*   Transfer domain registration/hosting for p2pu.org from PS account to P2PU's dreamhost account

        *   P sent all the transfer codes to DU already

*   Moving govlab to their own Dreamhost
*   WP for SOO landing page

        *   ideally done in a way that's redeployable as a template for new schools:

                *   means minimal customisation?
        *   is customised content/functionality 'skinnable'? Ie easily redeployable?

                        *   yes - wordpress themes

        *   set the server up
    *   point schoolofopen.p2pu.org to it
    *   give access to JP
    *   next year - look at theme to give it a stronger connection with p2pu.org

*   Talk with School of Ed - have same conversation, check their needs/expectations re courses platform, roadmap for them possible?

<u>Process</u>

*   Doing more analysis work on MechMOOC data
*   Favorite quote from SOO call (that I was not even on) -> "PS still goes to jail if we steal money (or the board)"

## 5 Dec 2013

Progress

*   MechMOOC unsubscribe now happen with email verification (only live for www.playwithyourmusic.org)

        *   hopefully no more user support related to this

*   Tech post about grouping users according to musical taste using Echonest - [](https://docs.google.com/a/p2pu.org/document/d/1CtaUsIIQ4cg9Y_T955YusZ7ODuoBOX_kfreNwbsEMkA/edit)https://docs.google.com/a/p2pu.org/document/d/1CtaUsIIQ4cg9Y_T955YusZ7ODuoBOX_kfreNwbsEMkA/edit
*   Form for gauging interest in Mech MOOC - only two questions about audience and tech skills - [](https://docs.google.com/a/p2pu.org/forms/d/1p0MccWvoY5GsrMU_iekqzMXaN8a0EY14eBTwbWjj4Kk/edit#)https://docs.google.com/a/p2pu.org/[forms/d/1p0MccWvoY5GsrMU_iekqzMXaN8a0EY14eBTwbWjj4Kk/edit#](https://docs.google.com/a/p2pu.org/document/d/1CtaUsIIQ4cg9Y_T955YusZ7ODuoBOX_kfreNwbsEMkA/edit)

        *   two more question (will add to thepeople too) 
    *   'plesae tick one or more of these that apply to you:

                *   I want to use MechMOOC with one-click deployment
        *   I'm willing to do a small amount of work to deploy MechMOOC for my use
        *   I'm willing to do significant work to deploy/customise MechMOOC for my use
        *   I'm willing to provide ongoing tech support for MechMOOC while my course is running'
        *   'are you willing to contribute funding/host your instance'

*   Pulled plug on dev.p2pu.org (Yay! I think we got some credits back -> US$ (enough for a party?))
*   Archived etherpad [](http://p2pu.github.io/etherpad_static)[http://p2pu.github.io/etherpad_static](http://p2pu.github.io/etherpad_static)

        *   There is a lot of pads that are not of any value (e.g. no content) do I clean them up?
    *   Symbolic links added in to github 
    *   DNS still points to pad.p2pu.org
    *   [1400-odd pads; phaps 200 useful]

*   Badges

        *   also display projects for a badge that didn't yet receive the badge

Priorities

*   Next steps for MechMOOC future

        *   Dirk: Update landing page to point to MOOC page on info and add form to info page

*   Finalize echonest grouping post

        *   Dirk: Should we run it by Paul Lamere?

*   Archiving old things

        *   Erika: write blog post informing people about what we will be archiving in the next 2/3 months
    *   create a list of all the courses and active people on lernanta
    *   speak to people who would be affected

*   Mechanical MOOC grouping

        *    Look at what is possible with the G+ APIs (js API may be able to do more)
    *    Sketch out basic idea for 2 use cases - we do initial grouping, users self group completely
    *   (Philipp: I also wrote to one of the G+ founders - mainly about analytics - but haven't heard back)

*   Next steps for online/offline combo:

        *   Talk during the community call
    *   [Carl: work out what interesting pedagogical q's we think this could answer, so we go into meetings with idea of what we personally would like out of it] [P: There is some background thinking / language about this in the Shuttleworth proposal]
    *   Set up meeting with possible partners

*   Investigate lernanta - emails spewing out of lernanta

        *   This will be less of an issue once we archive old courses

*   Still working on ALLOWED_HOSTS error on Badges
*   Govlab sprint #2 is starting on 6.dec 

Erika will work for the next two weeks (do you think it's a full 2 weeks? I don't think so) on their input in trello [](https://trello.com/b/NmVDO0Ts/govlab)[https://trello.com/b/NmVDO0Ts/govlab](https://trello.com/b/NmVDO0Ts/govlab)

Process

*   Leave for December (should do this on community call as well)

        *   P2PU closes all of its offices between Xmas and New Year
    *   Philipp: No day-to-day work between 25 Dec - 6 Jan (Mon). Will keep an eye on any emergencies. 

*   Carl should join our weekly standup at least once in a week (Carl: will join Mondays)

Problems

## 21 Nov 2013

Progress

*   Backups 

        *   running for info.p2pu.org (mysql db and whole wordpress directory)
    *   running for thepeople.p2pu.org (postgres database)
    *   code here: [](https://github.com/p2pu/marvin/tree/master/backup)https://github.com/p2pu/marvin/tree/master/backup
    *   hackpad backups: requires manual download of hackpads (but only takes a min). erika will do this once a week for now. 

*   Class photo group photos were sent to all groups in PWYM
*   Talked about Mechanical MOOC strategy (People  who are building and using Mech Moocs)

        *   Notes: [mechanicalmooc](/HQW58J0cY5Z)

                *   How much are Mech MOOC packaged and make them useful

        *   next step: test demand for a more packaged solution

                *   separate conversation to have with ocwconsortium.org (Philipp to set up)
        *   find a way to test demand from the community (Dirk)

        *   what was our takeaway from this?

                *   How much are Mech MOOC packaged and make them useful

*   Tech strategy

        *   Plan going forward:

                *   Archive old platforms (most of lernanta, archive.p2pu.org, etherpad). Move away from hosting platform. 
        *   Critically look at how best to support existing projects wrt new strategy (courses, mechanical MOOC and badges)
        *   Build/find missing the pieces of the “Open educators technology toolkit”

                        *   What are the components of the toolkit? (Sign-up, Grouping, Working in the group, ...)
            *   Primary audiences: How to run a school? How to run an open p2p course?How to run an open learning community? 
            *   Take-away: there is more <u>editorial</u> content, and more <u>tech</u> content, that we want to share with the community (?).  

                                *   to be done: best way of doing it, what goes in it. 

                *   Work on showcase projects and build tools for them

*   Deployed bugfix for thrown error from DB (too may chars) for Badges

Priorities

*   Talking with Karen & HTH about DLMOOC later today
*   TODO: Turn off archive.p2pu.org on Dreamhost
*   TODO: Pull plug on dev.p2pu.org
*   GovLab Academy 1.0 next steps
*   Anyone interested in Lists, please read -> [](http://gawande.com/the-checklist-manifesto)http://gawande.com/the-checklist-manifesto

Problems

Process

*   How do I deal with the issues at help.p2pu.org?

        *   I just assigned the ones I have no clue about to Dirk (I hope that is cool), but can pick up on this a bit more too

*   How is the p2pu-dev-bounces@lists.p2pu.org managed, who is managing, is there a need for it, etc?
*   turns out there is such a thing as "[Wordpress Essential Training](http://www.lynda.com/WordPress-tutorials/WordPress-Essential-Training/97614-2.html)", but it is not open.