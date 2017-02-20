A Public API for the Clipper Card
=================================
Using a [Clipper Card](https://www.clippercard.com) "smart card," travelers can easily pay for fare on most San Francisco Bay Area public transit systems. The current system provides a clunky web interface for loading cash and paying for monthly passes. Users can export their travel and billing history to a PDF. There is no way to export data in a machine readable format, nor does the Clipper Card system provide any publicly accessible APIs, let alone programmatic "callbacks" that trigger when you swipe your card.

The contract for the Clipper Card system expires in 2019---it's currently held by [Cubit Transportation Systems](http://cts.cubic.com/)---and the [Metropolitan Transportation Commission](http://www.mtc.ca.gov/) (MTC) is beginning to solicit requirements from transit agencies for the next version of the system. ([More information on the Green Caltrain blog](http://www.greencaltrain.com/2014/04/caltrain-cac-tomorrow-mtc-starting-to-take-feedback-on-clipper-2-0/).)

Although the MTC has not opened comments to the general public, there may eventually be opportunities for the Bay Area's community of software developers, hobbyists, and entrepreneurs to offer concrete suggestions on how the next version of the Clipper Card system can be improved.

Below is a letter that I plan on sending to the [members of the MTC's administration committee](http://www.mtc.ca.gov/about_mtc/standing_committees.htm). If you'd like to sign your name to it, please feel free to open a pull request. You're also welcome to propose changes or additions to the letter itself, again with a pull request. 

-- Drew Dara-Abrams ([@drewda](twitter.com/drewda), [dda@dara-abrams.com](mailto:dda@dara-abrams.com))

Letter
------

To the members of the Metropolitan Transportation Commission administration committee,

Almost every day of the week, I use my Clipper Card to ride a variety of transit systems. It's a great improvement over paying fares with cash and carrying monthly passes, especially for trips that involve more than one agency.

I am glad to hear that the MTC is considering how to improve the Clipper Card system as it prepares for a successor to the system's current contract. Many important improvements will involve much negotiation and cost. I am writing to you all today to suggest a specific improvement to the Clipper Card system that will require little negotiation and little cost: a publicly accessible API (application programming interface) to allow software developers, hobbyists, and entrepreneurs to build software services on top of the Clipper Card system.

Consider how transit agencies around the world have made available their route schedules and station locations to Google and a host of other software providers, which in turn disseminate this information to their users in a variety of attractive and usable web and mobile applications. The agencies release their public data using a common standard and reasonable licensing terms; application developers are then free to consume and package the data into whatever software packages and services they wish to create.

Why not ask potential bidders on the next iteration of the Clipper Card system to do the same? That is, allow third-party software developers to---with each individuals' permission---access the travel and billing histories of a Clipper Card and to get "callback" notifications when an individual tags on and off at stations. All of these data are already being collected as part of the current Clipper Card system. All of these data are already available to transit agency personnel for enforcement. And I, as an individual user, can access these data in a cumbersome process on the clippercard.com site, which produces a PDF file that I can download. But what I cannot do, at present, is build a piece of software that directly accesses this data in a machine readable format and acts on it.

If the next iteration of the Clipper Card system provides such a public API, I and other software developers could create, to give three examples: an application that analyzes your regular transit usage patterns and suggests alternative routes to try or when to purchase a monthly pass; or an application that sends you a text message on your phone with BART system alerts when it's aware that you've entered, but not yet exited, a BART faregate; or a beautifully presented summary of transit rides taken over a selected time period, letting a user decide whether their pattern warrants the purchase of a monthly pass to reduce their costs. Applications like these won't solve the difficult challenges that the Bay Area's transit agencies face in deliverying service, but this sort of software can provide useful marginal improvements on existing services, making transit more convenient and usable for both "choice" and "dependent" riders, as well as providing additional ways for the MTC and transit agencies to engage with their riders and constituents.

The Clipper Card system already provides great value to the Bay Area's transit riders. While addressing the next iteration of the Clipper Card system, please also consider the small cost and, potentially, large gain of a publicly accessible API (application programming interface) that allows software developers, hobbyists, and entrepreneurs to build software services on top of the Clipper Card system.



Signers
-------

* Drew Dara-Abrams (lives in Burlingame; works in San Francisco; rides BART, Caltrain, MUNI, Samtrans)
* Michael Norelli (lives and works in San Francisco; rides BART, Caltrain, MUNI, AC Transit, Golden Gate Transit, Marin Transit, and the PresidiGo shuttle)
