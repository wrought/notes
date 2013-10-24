# BADcamp 2013 - Bay Area Drupal Camp

## Non-Profit Summit

Came in late. Marsh Arts Center in Berkeley has terrible wifi service for an event where apparently some folks want to be connected to the internet.

### Tech Soup Global
Caught the post-lunch keynote, 30 min talk. Pretty interesting hearing about the work of a progressive team inside of a large global non-profit. In sum, if you believe you can deliver, push ahead and build the world you want to work in, even if it rides against the stream.

Really interesting content, slides are perfect notes for this circumstance, will link here. 

### CRM breakout

*Metaphor for CRM:* it is like writing an outline for a novel&mdash;enough detail, but not too much.

Recommend: build the tiniest possible thing and starting to use it and help it grow.

<blockquote>Most important thing about planning a CRM project is being *un-sentimental* about the organizational needs. Do not elevate 'wants' to 'eneeds' while also not demoting 'needs' to 'wants'.</blockquote>

Listen for moments of surprise and encourage those. Identify warning signs early and catch them ASAP, early, without being paranoid. 

Need to change from Technology Advocate to Subject-Matter Expert in your organization (recognize this).

Recognize that this stuff is only interesting to technologists / nerds, not to everyone!

!! Opportunity case: TI Alumni have this issue of older folks not needing some fancy things they see as young and unnecessary. On the other hand, they want to see what a new system will look like before pursuing it. Unofortunately, as the tech person has to say, if we could show you what it would look like&mdash;we would have built it already! SO, what is the use case?
!!! The user wants to build a *real* mock-up using an actual crm instance, [http://wordpress.com/ wordpress.com]-style. This leaves the opportunity for running a simple, blog-style CRM, then upgrading for freemium features, and ultimately to move to independent instances, development contracts, etc. 
!!! Need to investigate pantheon, aws, other drupal hosting (and cloud hosting) services to determine how to hack this with an MVP.

#### What about modularity&mdash;why drupal at all?

If you are using drupal as a brochureware, why would you bother integrating CRM? Probably you should not, unless you are doing *actual* interaction with your user, such as doing event registration, etc.

#### Technologies

* Springboard
* Blackbaud? (Convio ancestor)
* Salesforce (force.com)
* Red Hen (built FDBD, for-drupal-by-drupalers, vs civicrm)
* CiviCRM

## Bay Area Video Coalition (BAVC)

Jennifer Gilmen and Mark Hellar.

Community center in San Francisco. Support independent media, including a public access tv station&mdash;which motivated the move to drupal in the first place some years ago.

Center of Investigative Reporting & them are interested in measuring impact.

Part of documentary filmmaker coop called New Day Films, want to use drupal + salesforce, etc.

At the center of quite a number of different kinds of orgs. From cities to youth programs, independent producers, public meda, companies, etc.

Bid on SF public access TV station some years ago. AT&T rigged the laws to choke major city contracts for public access. Funding was going down to $170,000 / year, which is nothing! Not much to support all the good work they were doing there already.

Wanted to provide a lot of functionality for the public broadcast station, was possible due to work from the  Denver Open Media project. Needs more development!!! Contact them.

!! Side-note... It seems like the advantage of the html5 side of the web is that folks can access the full stack of the application and can therefore reproduce issues and do bug-fixing. However, when you have server-side software, there is a limitation to reproduce the same applications in order to actually work on them in the abstract. Some systems try to address this in some fashion that allow you to more closely reproduce the sites and applications *as they may exist in the wild* but usually it is a pain in the ass! E.g. django has fixtures, drupal has site archetypes (erg, what is the technical name for this?).
!!! So how to fix this? Unclear, is there a standard or simple way to make your site, private, safe, yet clonable?

Lots of discussion of webforms and integrating with salseforce using springboard. This is boring. Is this really the state of the art on the web for independent and public media coalitions? What is the next-generation of this type of work?

Honky-dory that program folks can interoperate with this system fairly elegantly&mdash;the state of the art is perhaps (not restricted but) shaped by the use of folks who are going to be implenenting programs and working on services provided by non-profits, etc.

* Perhaps it is /using/ data, visualizing it, and allowing *complex interaction*. 
** What does "complex interaction" look like? 
*** doing lots of things with the data, storing states, allowing it to interoperate with other sources and services, being able to share and then build a review/comment layer on top of this.
** This is perhaps why I am very interested in using drupal as a back-end to some javascript engines like knockout.js.

BAVC has a program for documentary filmmakers to publish and share content, which automatically gets archived in the internet archive&mdash;stored in "Community Media" archive.

Ideally, folks should be able to upload content to their local library, ship it to BAVC, publish to the website, and archive it with Internet Archive&mdash;*automagically*.

Created a website for city and county of San Francisco, (http://goconnectsf.org/)[GoConnectSF] with youth center digital filmmaking programs.

If you want to see code email markh@bavc.org, for programs, email jennifer@bavc.org
