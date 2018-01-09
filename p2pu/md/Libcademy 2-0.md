# Libcademy 2.0

**Learning Circles model**

*   Do we store weekly meetings in the DB or calculate from the start and end date.
*   start_date and weekday and time are currently redundant. Having inconsistent values can lead to bugs!

**Login for facilitators**

*   Django default auth

        *   - users need to create an account - username + password
    *   + simple to set up

*   Allauth plugin that allows social account login

        *   + users don't need a new password
    *   - users still need to create an account

Lets start with Django auth.

**Flyer generation**

Criteria for tool

*   Work from template - Layout, content and footer
*   Programmatically fill out template - Course(s), time and location
*   Edit flyer online - Change descriptions.
*   Print/publish flyer - Save to PDF/PNG/JPG - print directly - share on social media (bonus points)

Possible tools

*   Google drive (slides or draw)

        *   ▼  doesn't support programitically filling out a template
    *   ▲ Easy to edit online

*   [](http://www.flyerforfree.com/)http://www.flyerforfree.com/
*   [](http://www.hipsterlogogenerator.com/)http://www.hipsterlogogenerator.com/
*   [](https://www.canva.com/create/flyers/)https://www.canva.com/create/flyers/
*   [](http://www.squarespace.com/logo/)http://www.squarespace.com/logo/

During call with EP decided to generate PDF flyers and offer Google slide template if users want to customize.

**Applications**

*   Per study group application URL to be used by branches

**RSVP**

How do we capture RSVP on a per meeting basis

*   Create a RSVP model
*   Send a special link to each user when sending reminders (**Needs reminders to be sent to users individually**)

Data that is needed

*   user email / mobile
*   study group meeting
*   yes/no

In an ideal world the link could be 

[](https://chicago.p2pu.org/en/rsvp/manning-1/?user=dirk@mail.com&rsvp=yes&22-oct-2015-18:00)https://c[h](https://c)[i](https://ch)[c](https://chi)[a](https://chic)[g](https://chica)[o](https://chicag)[.p](https://chicago)[2](https://chicago.p)[p](https://chicago.p2)[u](https://chicago.p2p)[.o](https://chicago.p2pu)[r](https://chicago.p2pu.o)[g](https://chicago.p2pu.or)[/](https://chicago.p2pu.org)[e](https://chicago.p2pu.org/)[n](https://chicago.p2pu.org/e)[/](https://chicago.p2pu.org/en)[r](https://chicago.p2pu.org/en/)[s](https://chicago.p2pu.org/en/r)[v](https://chicago.p2pu.org/en/rs)[p](https://chicago.p2pu.org/en/rsv)[/](https://chicago.p2pu.org/en/rsvp)[m](https://chicago.p2pu.org/en/rsvp/)[a](https://chicago.p2pu.org/en/rsvp/m)[n](https://chicago.p2pu.org/en/rsvp/ma)[n](https://chicago.p2pu.org/en/rsvp/man)[i](https://chicago.p2pu.org/en/rsvp/mann)[n](https://chicago.p2pu.org/en/rsvp/manni)[g-](https://chicago.p2pu.org/en/rsvp/mannin)[1](https://chicago.p2pu.org/en/rsvp/manning-)[/](https://chicago.p2pu.org/en/rsvp/manning-1)[?](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/)[u](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?dirk@mail.com&)[s](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?udirk@mail.com&)[e](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?usdirk@mail.com&)[r](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?usedirk@mail.com&)[=](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?userdirk@mail.com&)[d](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?)[i](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?d)[r](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?di)[k](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?dir)[@](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?dirk)[m](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?dirk@)[a](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?dirk@m)[i](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?dirk@ma)[l](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?dirk@mai)[.c](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?dirk@mail)[o](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?dirk@mail.c)[m](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?dirk@mail.co)[&](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?dirk@mail.com)[r](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?user=dirk@mail.com&)[s](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?user=dirk@mail.com&r)[v](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?user=dirk@mail.com&rs)[p](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?user=dirk@mail.com&rsv)[=](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?user=dirk@mail.com&rsvp)[y](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?user=dirk@mail.com&rsvp=)[e](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?user=dirk@mail.com&rsvp=y)[s](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?user=dirk@mail.com&rsvp=ye)[&](https://chicago.p2pu.org/en/rsvp/manning-1/?user=dirk@mail.com&rsvp=yes)[22-oct](https://chicago.p2pu.org/en/rsvp/manning-1/22-oct/?user=dirk@mail.com&rsvp=yes)[-](https://chicago.p2pu.org/en/rsvp/manning-1/?user=dirk@mail.com&rsvp=yes&22-oct)[2](https://chicago.p2pu.org/en/rsvp/manning-1/?user=dirk@mail.com&rsvp=yes&22-oct-)[0](https://chicago.p2pu.org/en/rsvp/manning-1/?user=dirk@mail.com&rsvp=yes&22-oct-2)[1](https://chicago.p2pu.org/en/rsvp/manning-1/?user=dirk@mail.com&rsvp=yes&22-oct-20)[5](https://chicago.p2pu.org/en/rsvp/manning-1/?user=dirk@mail.com&rsvp=yes&22-oct-201)[-](https://chicago.p2pu.org/en/rsvp/manning-1/?user=dirk@mail.com&rsvp=yes&22-oct-2015)[1](https://chicago.p2pu.org/en/rsvp/manning-1/?user=dirk@mail.com&rsvp=yes&22-oct-2015-)[8](https://chicago.p2pu.org/en/rsvp/manning-1/?user=dirk@mail.com&rsvp=yes&22-oct-2015-1)[:0](https://chicago.p2pu.org/en/rsvp/manning-1/?user=dirk@mail.com&rsvp=yes&22-oct-2015-18)[0](https://chicago.p2pu.org/en/rsvp/manning-1/?user=dirk@mail.com&rsvp=yes&22-oct-2015-18:0)

Possible ways to secure link (prevent someone from typing in the URL

*   encrypt data (details not visible in link)

Q: **How do people RSVP via SMS?**

**StudyGroupMeeting**

Create new model

*   meeting date & time

Generate meeting 

*   1 week in advance

        *   ▲ will reflect changes in study group details
    *   ▼ Assumption about regular "once a week at the same time" is made every week
    *   ▼ Hard to make changes to all StudyGroupMeetings

Generate reminder 4 days in advance

Send reminder with RSVP links 2 days in advance

**DateTime picker **

for datetime fields in interface

*   Use a single widget like [](https://tarruda.github.io/bootstrap-datetimepicker/)https://tarruda.github.io/bootstrap-datetimepicker/

        *   ▼ Clunky interface

**Closing learning circle signup**

*   Automatically close based on start date

        *   **!! Does not support exceptions to the default policy !!**

Not sure about need to schedule closure - easy to implement data/bool, but bool probably easier for user to understand.

List study group on landing page vs don't list?

**Navigation for organizers vs facilitators**

*   display different links based on what group a user is in?
*   no easy way to check if user is in a specific group in templates
*   add permissions to group
*   Django permissions doesn't work in an expected way -> 

        *   when adding permissions to a model they don't get added to the db as part of the migration that adds them
    *   they only get added at the end of migrations making it difficult to depend on the presence of custom permissions.
    *   adding a data migration to assign permissions to groups doesn't work
    *   if permissions aren't added using a migration some custom app configuration would be required :(

*   alternative: create 1 to 1 model for Organizers and Facilitators

**Facilitators creating learning circles**

*   2 or 3 step process

        *   how do we keep track of progress?

Created a custom view that reads to django forms and validates data!

**Delete learning circles while keeping a history**

*   Log Learning Circle data into a log db using pre-/post- delete signal

**City field for Learning Circles**

*   Make sure entered value is a valid country

        *   Get a list of all countries and all cities in each country

*   Make city field a free form text field

        *   Allow the user to type in the name of the city
    *   Auto-complete with list of City (Country)

*   Split input for Country first and then City
*   [](http://download.geonames.org/export/dump/readme.txt)http://download.geonames.org/export/dump/readme.txt
*   geonamescache - [](https://pypi.python.org/pypi/geonamescache)https://pypi.python.org/pypi/geonamescache

        *   gc = geonamescache.GeonamesCache()
    *   [ c['name'] for k,c in gc.get_cities().iteritems() if c['countrycode'] == u'ZA' ]

*

**Parking lot**

1.  Can more than 1 facilitator be associated with a learning Circle?
2.  How do we route a message for a participant signed up to 2 learning circles
3.  Facilitators are currently just Users linked from the Study Group model -> need to insure that they are also in the facilitators group!
4.  Need a place where facilitators can log in/out + manage account info.
5.  Should we close applications once LCs start? Maybe not to build up interest for the next LC?
6.  Consider making LCs times a link to iCal files
7.  Idea: Make LC app more composable with Zapier/IFTTT integration
8.  **When does US/Central daylight savings time start/stop?** Sometime in November, but I think I addresses the concern with changing daylight savings in the middle of a learning circle.
9.  <s>What happens if 1 LC needs to happen at a different time?</s>
10.  <s>What happens if the first meeting is at a different time?</s>