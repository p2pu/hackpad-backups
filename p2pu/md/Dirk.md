# Dirk

**Parking lot**

*   Maintaining good dev workload at P2PU

## 27 Feb 2014

Things keeping me busy

*   Teach The Web: [](http://training.webmaking.org)http://training.webmaking.org

Things to talk about:

*   School of data
*   Learning Creative Learning 2
*   teaching coding
*   whatever?

## 20 Feb 2014

Things keeping me busy

*   SoW - started working on [](http://p2pu.github.io/school-of-webmaking/)http://p2pu.github.io/school-of-webmaking/

        *   Looking into methods to facilitate sign up

Things to talk about

*   Tech for LCL
*   Forking of github courses
*   MOOC data
*   What do we do about expressions of interest about the MechMOOC and who does it?
*   ??

## 13 Feb 2014

Some things keeping me busy (data, docs, and support)

*   README file for Mechanical MOOC data: [](https://docs.google.com/a/p2pu.org/document/d/1dfi5qn_g-EeicPCXHrqHGQYGJiSM9tTa63NKKkKBloU/edit)https://docs.google.com/a/p2pu.org/document/d/1dfi5qn_g-EeicPCXHrqHGQYGJiSM9tTa63NKKkKBloU/edit
*   Document about running a Mechanical MOOC: [](https://docs.google.com/document/d/16XOAYOCH0uECuTymUt54gOhavVIZe7mQqE0ftGK08G4/edit?usp=sharing)https://docs.google.com/document/d/16XOAYOCH0uECuTymUt54gOhavVIZe7mQqE0ftGK08G4/edit?usp=sharing

Things to talk about

*   SoW proposal

        *   (tech) Integration with the MakeAPI - we will need some help from their side, but I think it can be done!
    *   (tech) we have to figure out multiple runs
    *   (tech) need to figure out signup component, but I have an idea
    *   using webmaker.org for identity may imply we need them to make some changes to webmaker.org
    *   (tech) multiple courses in single jekyll site vs multiple? this affects forking
    *   (tech) facilitation part will need to happen somewhere else than github pages
    *   (tech) will need to read up about their translation process - _Transifex_

*   IoT
*   Whatever anyone else wants to discuss with me.

## 6 Feb 2014

What's keeping me busy

*   Jekyll course template: [](https://github.com/p2pu/jekyll-course-template)https://github.com/p2pu/jekyll-course-template
*   Data for PWYM
*   P2PU Data release
*   DLMOOC - investigating what is a good chat option to have a chat client and a live video stream together

Things to talk about

*   anything other people want to talk about
*   Data if Bekka is around
*   community management - concrete ex atm - what do we do with responses to interest in the Mech MOOC?
*   how does cards enter the trello board? Should things start in a special column when they are added and then moved to the correct column during the project call?
*   Analyzing the Python MOOC data
*   Analyzing some P2PU data

## 28 Jan

Considerations about supporting platforms

*   we are currently planning to abandon our own platform in favour of using many different tools and platforms. Two of the strong platforms we are currently looking at is **Wordpress** and **Jekyll** hosted by github pages
*   The motivation for this is to give the community better tools where they have more control and can do more [CR: and to remove development & support load from our tech team, freeing them for peer-learning-specific tech consulting, small tool development, community assistance]. It is also part of our motto that the web is the platform.
*   If we had the resources necessary to maintain a single platform would we be sure that that is the best thing to do? What would we spend other resources on?

A proposal for trying out Jekyll + github pages as a tool for other people to create courses

*   We create a light weight template for a course in Jekyll
*   We write a 1 page guide for setting up a course using the template (this doesn't include git training)
*   We launch 1 course [or a tool as part of a course?] using this [School of Webmaking?] 

        *   need a guinea pig pilot to assess whether this is a good optoin to be recommending more generally or not
    *   eg SoO 1st round course? Open Science course? Or someone from thepeople?
    *   process

*   ???
*   Profit

This could be a part of the School of Webmaking 2.0 (noting something Mozilla really liked about Lernanta was easy clone & course creation feature; they want an easy course creation feature for students)

Any questions?

Thoughts:

*   trialling Jekyll a great idea
*   archiving - are we ''archiving'' stuff (static copy of content, not intended for continued running), or migrating to new platform for continuing running (leading options seem to be Wordpress or Jekyll)
*   School of Webmaking - consider further what best solution

Big issues:

DLMOOC

*   had some tech probs: Wordpress running slow, live event timed-out/failed, hosting not perfect
*   how to avoid next time? Ensuring we better in the loop on progress - eg weekly call to hear progress, rather than only getting called on when something went wrong
*   better checking on the tech credentials/resource allocation at the start, before accepting a secondary tech role?? [P2PU was meant to be tech lead/host, but breakdown happened coz:

        *   they wanted to be in charge of some tech stuff
    *   Karen had some strong preferences on tech choices and tools, so she built much of the tech infrastructure herself 

*

Lernanta support 

IoT

1-on-1's: does office hours concept achieve same outcomes as 1-on-1 meetings?

SoW

## 14 Jan

Process (lets start with this)

*   "What should this weekly call look like? It is in danger to be very similar to the Tech call."

Ideas / Thoughts for the year ahead / Things to talk about

*   Immerse myself more in open web communities
*   What do we want from tech in the coming year?
*   How do we manage IT infrastructure costs?
*   Working on IoT

Progress

*   Make sure DLMOOC has everything it needs
*   Keep the wheels on (info.p2pu.org back to dreamhost + backups)

Priorities

*   Start archiving of old courses (EP busy with blog post)
*   Start migration path for new courses
*   Tech for new course about running open, online courses

Process

*   How do we prioritize ideas like self association, profiles, etc?

## 17 December

*   Discourse

        *   Progress

                *   Updated to latest version
        *   Didn't update config files - nothing important atm
        *   note: code lives at /home/discourse/discourse and not /var/www/discourse
        *   Configure reply by email using a p2pu gmail account
        *   Notifications now come from noreply @ p2pu.org and replies goes to discourse @ p2pu.org (P: Sweeeet!!!)

*   AWS

        *   Progress

                *   Setup billing alerts for AWS 
        *   read  an article of someone discovering $3.000 charges incurred on their  account because they accidentally checked in a key on github!! (PS: This obviously freaks me out! Please make this priority No.1)

        *   Priorities

                *   We should start using IAM keys - they can be restricted to what they can do

                        *   --> more secure in case of lost keys

*   Using G+ to get profile info for users

        *   Progress

                *   Basic functionallity is implemented
        *   I'm   not sure what happens if someone has a  custom URL for G+, but since   they make you agree to ToS and add verify  a USA cell number I'm  guessing  not many people will have it

        *   Priorities

                *   Test with a few different profile URLs
        *   Deploy for DLMOOC

*   Echonest blog post

        *   Priorities

                *   ping echo nest about blog post
        *   hand blog post over to BK for scheduling

*   DLMOOC

        *   Progress

                *   Purchased gravity forms for Karen - got a 30% discount from them :)
        *   Class photo - support getting profiles from G+
        *   Fixed problem with some browsers not sending cookies to iframes

        *   Priorities

                *   **Need to figure out what of the promised functionality they still want to implement?**

                        *   little needs doing from now to get them to launch (mid-Jan)
            *   but some 'wants' that we could work on for them (if they align with 'wants' of our own)
            *   first 2 weeks of Jan set aside for DLMOOCing: doing the remainder of 'needs' to get to launch
            *   can do this discussion after that

                *   Ask KF to schedule a regular call - also talk about proposal after initial launch
        *   Busy sorting out redirection of dlmooc.net -> dlmooc.deeper-learning.org

*   IoT

        *   Progress

                *   Held first call and gave some feedback

        *   Priorities

                *   What are the next steps?
        *   Dirk to write back to them to say what we can offer them without raising funds, and what we could imagine doing if we raise funds

*   DNS transfer from PS account to P2PU account

        *   Progress

                *   Did the transfers with the help of BK

        *   Priorities

                *   I think PS needs to approve the transfers (P: I haven't gotten anything from Dreamhost, but expect that they'll send me emails to authorize the transfer - will let you know.)

*   Scheduled a call with Dominic (student from Capetown interested in edtech)
*   Music MOOC data

        *   Progress

                *   Did a dump of the data for the MOOC thus far

        *   Priorities

                *   Talk with Alex/VMG about data questions tomorrow

                        *   work out what q's we can answer

*   P2PU data release

        *   Priorities

                *   Give June Ahn feedback on what P2PU data they can include in the data dump
        *   I think it is important that they also include data from the new courses

*   Jekyll (possible alternatives for courses in the future)

        *   Progress

                *   Quick investigation into Jekyll
        *   Really like being able to keep content separate from layout and HTML stuff
        *   Too technical for most people

        *   Priorities

                *   Investigate exporting P2PU courses to github using API
        *   Investigate other editors for GH pages (P: what about prose.io - it's super nice, but not sure if the folder structure is too confusing)

*   Misc

        *   Process

                *   I don't like PPPPI all the time because it becomes stale and starts feeling like justifying my time rather than talking about the things we are working on.

## 10 December

*   Mechanical MOOC interest gauge

        *   Got feedback on project page and form
    *   Update copy on info.p2pu.org and add form
    *   Need copy to put on the front page and make the changes in code 

*   Mechanical MOOC grouping alternatives

        *   Need to investigate G+ JavaScript API
    *   Need to investigate discourse for group communication
    *   Page for helping to create/list self created groups

*   Echonest grouping blog post

        *   Worked through feedback
    *   Run by Echonest and hand over to Bekka to schedule for publishing

*   IoT talk

        *   Talked on Monday
    *   Need to discus internally and follow up with Cesar and Marc
    *   Need to follow up with other potential collaborators
    *   [](https://docs.google.com/presentation/d/1dsbUumrMkHZ6wLuXHDgNm_O6Tu1JiYDMHrWednwEDvk/edit#slide=id.g258c37ede_037)https://docs.google.com/presentation/d/1dsbUumrMkHZ6wLuXHDgNm_O6Tu1JiYDMHrWednwEDvk/edit#slide=id.g258c37ede_037

*   Old course archiving

        *   EP working on blog post communicating archiving steps
    *   Need to list old/new courses

*   Course listing on Balloon site

        *   Create old fashioned CSV file that we can email to them

*   Talk with SOO about future plans for schools

        *   School landing page
    *   Courses ran by schools
    *   Listing courses
    *   Infrastructure like Etherpads
    *   Branding/affiliation with P2PU
    *   profiles, homepages, course listings - things that clearly could be done better away from lernanta (in terms of resource cost to P2PU and functionality for users)

                *   homepage - we could help soon
        *   profiles - could be done better elsewhere with our help
        *   content hosting - could be done better elsewhere with our help
        *   course listing - could def be done better, whether on our own platform or elsewhere

        *   course itself - maybe not so bad on lernanta (new courses)
    *   old courses - burden to support need to archive ASAP

hello - hello! hello! I'm off to eat, catch up later :)

[Philipp Schmidt](/ep/profile/Dc7zU8svumi) - sounds like D is going to close out a few things shortly tho - echoneet post done, mech mooc feedback done, archiving lernanta stuff E is handling.  Big stuff sees to be IoT and conversation with Jane nowish re SoO.  (Sorry D if putting words in your mouth correct me if wrong!)

Ah. Those things are more obvious when using the Progress / Priorities split (or some other way of indicating where we need to focus in the coming week). I'm not sure if there is a reason you didn't use that. 

## 3 December

*   Progress

        *   MOOC unsubscribes now handled by the MOOC itself

                *   requires a confirmation email

        *   DLMOOC call

                *   still a little unclear, but have some things that we can start doing

        *   Echonest grouping tech post

                *   [](https://docs.google.com/a/p2pu.org/document/d/1CtaUsIIQ4cg9Y_T955YusZ7ODuoBOX_kfreNwbsEMkA/edit)https://docs.google.com/a/p2pu.org/document/d/1CtaUsIIQ4cg9Y_T955YusZ7ODuoBOX_kfreNwbsEMkA/edit
        *   [](http://jsfiddle.net/dirkcuys/SU3v6/embedded/result/)http://jsfiddle.net/dirkcuys/SU3v6/embedded/result/

        *   Conversation about online/offline

                *   [](http://thepeople.p2pu.org/t/open-education-and-maker-spaces-and-co-work-spaces/312/5)http://thepeople.p2pu.org/t/open-education-and-maker-spaces-and-co-work-spaces/312/5

*   Priorities

        *   A few user support requests for PWYM
    *   Page to gauge interest in Mechanical MOOC by wider community

                *   button/form on p2pu.org -> link to info.p2pu.org/projects/mechanical-mooc
        *   form on info.p2pu.org/projects/mechmooc

                        *   what questions should we ask?

        *   Investigate the emails we send from Lernanta
    *   See if we can use G+ for class photo
    *   See if we can get posts to a community for G+
    *   Way for users to advertise self formed groups on G+

                *   CR: for P2PU: way for us to compare success of this mech vs other things we've tried (eg Music MOOC Echonest?)
        *   possible features

                        *   guide to create group
            *   collection of URLs for group

        *   Schedule call with IoT people about online/offline

*   Problems

        *   When do we communicate strat decisions to the community? Esp WRT Lernanta?

                *   Dirk to do draft communicatation to the community about Lernanta

                        *   include a list of all the stuff that will be archived, which ones may be problems + some stats about what is there and not being used.
            *   include briefly the options for what to do with the active schools

## November 26

*   Progress

        *   MOOC meeting
    *   DLMOOC meeting
    *   Sent group photos for Python Mechanical MOOC
    *   Backups for info.p2pu.org and thepeople.p2pu.org
    *   Investigated 

*   Priorities

        *   Page to gauge  interest in Mechanical MOOC by wider community

    *   Mailgun issues wrt Mechanical MOOC for upcoming DLMOOC

    *   Investigate what emails we send from Lernanta

    *   EP will loot at: Make all etherpad pages read-only
    *   Finish document of all P2PU web properties
    *   Basic summary of data on p2pu.org
    *   DLMOOC call on Monday

*   Problems
*   Process

## November 19

*   Progress

        *   Downgraded mailgun account used for data mooc to free account
    *   Busy making sure no important data are still on dev.p2pu.org, about to shut it down
    *   Sent out compiled group photos to PWYM groups (P: "I got mine - super nice!")
    *   Talked with Carl about some Tech process and the future of Lernanta
    *   Some user support (accidentally unsubscribed users, etc)

*   Priorities

        *   I'm talking with Werner Westermann after this call, mostly social, but will probably talk about P2PU
    *   MOOC planning meeting: [mechanicalmooc](/HQW58J0cY5Z)

                *   DU to send email to Alex later today for his feedback

        *   Looking at some data for a broader discussion about the future of Lernanta
    *   Setup backups for info.p2pu.org and thepeople.p2pu.org
    *   Make all etherpad pages read-only
    *   Finish document of all P2PU web properties
    *   Finalize PWYM Blog post (and hand it over to Bekka)
    *   Send group photos for Python Mechanical MOOC

*   Problems
*   Process

## November 12

*   Progress

        *   Feedback on strategy document
    *   PWYM email problem resolved, but we need to think about email groups
    *   Busy constructing doc about all the web properties we have + costs
    *   Shut down 1 EC2 instance we used when we had trouble with Etherpad
    *   In the process of shutting down dev linode - we can use EC2 when we need a server for testing
    *   EP is looking at archive.p2pu.org and backup for hackpad
    *   MOOC support - a few small requests and problems
    *   Talked with Karen about DLMOOC

                *   Karen to schedule call with HTH, PS, DU to talk about actual course

*   Priorities

        *   Busy with blog post about PWYM groups
    *   Retire dev server
    *   Sending class photos to groups
    *   Change pad.p2pu.org to be read only
    *   Cancel data mooc mailgun account
    *   Tech planning - Migration plan for lernanta
    *   Bounce ideas around with Karen, Steve, Alex, Vanessa, Philipp, etc about MOOC

*   Process
*   Problems

## November 5

*   Progress

        *   Play with Your Music

                *   grouping
        *   Class photo

*   Priorities

        *   Add comments / edits to strategy doc
    *   Play with your music

                *   **figure out problems with mailgun** - not all messages are being delivered!! 17% have been dropped so far!!!
        *   Send email to VMG and June about extra prompting emails
        *   Compile class photo for groups (this apply to Python MOOC also)
        *   Compile list of artists for every group

        *   Write technical article about using Echonest API for grouping
    *   DLMOOC

                *   Check in with Karen and figure out what problems needs sorting out

        *   Parking Lot:

                *   Fix info.p2pu.org problems 
        *   Tech planning - Migration plan for lernanta
        *   Consolidated documentation for server infrastructure
        *   Archiving archive.p2pu.org
        *   Archiving etherpad
        *   Reducing our linode footprint

        *   Cancel data mooc mailgun account

*   Process

        *   What time is this call? (next week)

*   Problems

## October 28

*   Progress

        *   Play with Your Music: [](http://jsfiddle.net/dirkcuys/TUq5a/4/)http://jsfiddle.net/dirkcuys/TUq5a/4/
    *   Gentle Python grouping + email

                *   Mailgun recipient variable didn't work with mailing list email. I suspect it's because there are two ways to add multiple addresses - separated by comma or as multiple arguments to the post request. Seems like recipient variables doesn't work with both :(

*   Priorities

        *   Fix info.p2pu.org and make sure it doesn't go down again

                *   Install supervisord
        *   Maybe move to Ansible managed Ubuntu 12.04 environment

        *   Commit changes made to MechMooc on Friday
    *   Music MOOC signup visualization
    *   Music MOOC grouping script
    *   Tech planning

                *    Migration plan for lernanta

        *   Create separate class photo for groups Gentle Python MOOC and send a link to them
    *   Consolidated documentation for server infrastructure
    *   Archiving archive.p2pu.org

*   Problems
*   Process

## October 23

*   Progress

        *   DLMOOC

                *   setup DLMOOC signup to run in wordpress
        *   added ability to export signups for DLMOOC
        *   Added signup count for DLMOOC

        *   Python MOOC

                *   Grouped users
        *   Updated to latest template

        *   Music MOOC

                *   updates to copy

## October 17

*   What is the main drive behind the strategy discussion?

        *   focus

*   Progress

        *   mostly what we said in the tech call

## October 8

Progress

*   Class Photo

        *   [](http://mooc-signup-test.herokuapp.com/gallery/1/)http://mooc-signup-test.herokuapp.com/gallery/1/

*   Sent email to translators

Prioties

*   Deeper learning MOOC

        *   want to run pilot 1 November
    *   we will need to change to MOOC signup if we want to use the blog as the main site, maybe create the signup form as an iframe/javascript library?
    *   need to add ability to track signups (both numbers & list of signups)
    *   contact Karen to define scope of pilot (expectations)

*   Class Photo

        *   need to do work on error reporting, feedback while loading, etc
    *   Simplify backend
    *   Test on more browsers

*   Music MOOC

        *   user grouping script that uses echonest
    *   signup 15 October
    *   start 1 November

*   Python MOOC

        *   Support to copy emails
    *   Signup already open (2500 people so far)
    *   Start October 21st
    *   contact Steve to discuss new design for 1st week (combine some emails, do class photo)

*   Data MOOC

        *   Not sure if OKFN plan to use our mail sending interface
    *   Waiting to hear from them. Either we build it quickly or we ask them to send the emails themselves. 

## October 1

Progress

*   Talk about data with June

        *   we are recording a lot less data now
    *   a lot of the work they previously did was on old courses & the data involved with that

*   Music MOOC 

        *   copy updates
    *   talked about interest based grouping
    *   created google analytics for the mooc

*   Python MOOC

        *   discovered signup spike!
    *   setup new sequence

Priorities

*   Organize call/hangout/?? with interested trasnlators
*   MOOC maker

        *   class gallery
    *   support for copying old messages for python MOOC
    *   see/export a list of participants
    *   see number of signups

Problems

Process

## Sept 24

Music MOOC

*   Done:

        *   DNS registered through domain cheap (a confidence inspiring company name)
    *   Also hosted by domain cheap. It is not possible/recommended to point a top naked domain to Heroku using linode DNS hosting
    *   Signup up at [](http://www.playwithyourmusic.org/)[http://www.playwithyourmusic.org/](http://www.playwithyourmusic.org/)
    *   Copy updated, but may need some corrections/tweeks
    *   Email setup through playwithyourmusic.p2pu.org

*   Will do:

Mooc class photo

*   Done:

        *   Fixed problem with cross site POST request used to upload profile pictures to S3
    *   Setup a separate MOOC with all the moving parts at [](http://mooc-signup-test.herokuapp.com/)[http://mooc-signup-test.herokuapp.com/](http://mooc-signup-test.herokuapp.com/)
    *   Changed the way that we get data from twitter