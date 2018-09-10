InCASE
-------------------------------
InCASE is a computer-aided software engineering tool similar to StarUML. It allows developers to create a project and then add use case models to the project. (Future versions will allow other types of UML models to be added to a project.)

Developers can add allowable elements to a model. Allowable elements include use cases, actors, diagrams, and arrows (generalization, association, extend, and include). However, an association only connects actors and use cases. Other types of arrows also have restrictions on the types of their sources and targets. For example, a generalization arrow connecting two use cases or two actors may be added to the model.) Elements can be edited and deleted.

InCase Labs
1. Create a use-case model for InCase. (Each use case should include a description, risk, and priority. At least two highlighted use cases should include main scenarios.)
******************************

SocNet
-------------------------------
SocNet is a web-based social networking application similar to Facebook. Visitors to the SocNet site can become members by creating profiles. A profile contains information such as name, gender, birthdate, relationship status, etc.

Members can send and accept friend requests. A member may also delete a friend.

Every member has a blog and a feed. Members post entries to their blogs. A blog entry typically contains text, a photo, a date, a location, and a teaser (i.e., maybe the first line of the text). The teaser appears in the feeds of all of the poster's friends. Of course a member may edit or delete embarrassing entries. The visibility of an entry can be set to public, friends-only, or private.

A member can browse his or her feed. Selecting a teaser causes the entire entry to be displayed. The member may comment on the entry or may simply approve (thumb up) or disapprove (thumb down) of the entry. Entries can also be shared with the friends of the member reading the entry.

Members can report offensive entries. A moderator can view and delete reported entries. A moderator can expel members who repeatedly post offensive entries.

SocNet Labs
1. Create a use-case model for SocNet. (Each use case should include a description, risk, and priority. At least two highlighted use cases should include main scenarios.)
******************************

Film Pal
-----------------------------
Film Pal is an application that runs on GPS-equipped devices such as smartphones and tablets. Similar to Flixster, Film Pal allows patrons to search for information about current films and nearby theaters. (A film is current if it is playing in at least one theater.)

For example, a patron can search for current films by title, cast members, director, and genre (documentary, horror, comedy, drama, romance, action). A patron can search for theaters by name and proximity (i.e., if the location of the theater is within some specified number of miles of the location of the patron).

A patron can read reviews of a selected film (Film Pal pulls reviews from RottenTomatoes). A patron can also read a description of a selected film, the filmography and bio of the director, and the filmography and bio of each cast member.  (Film Pal pulls all of this information from the Internet Movie Data Base (IMDb).)

A patron can find out the showings at a selected theaters. A showing is a showing of a film. It has a time and an optional screen number (for multiplex theaters). A patron can also buy an e-ticket to a showing. (Film Pal uses online ticket brokers to enable purchase of e-tickets.)

A film has a title, run time (in minutes), director, cast of actors, rating (G, PG, PG13, R, NC17, or unrated), and genre. Actors and directors have names, biographies, agents, and filmographies. An agent has a name and phone number.

A theater has a name, phone number, location, and one or more daily showings. (This information is pulled from theater web sites.)

To facilitate ticket purchases, Film Pal keeps a record of each patron. A patron is a registered Film Pal user and has a credit card (with number, expiration date and security code) and a location.

Problems
Problem 1
Create a use case model for this system. Provide an elaboration of the use case that allows patrons to search for nearby theaters.
