Drip Campaign Sender
====================

You will be designing and writing a software application to send a scheduled Drip Campaign.

You are responsible for designing and building as much as you can in the allowed time.
Feel free to leverage any technologies, libraries, frameworks you'd like;
in fact we encourage you to use anything that will let you build faster.

After the allowed time, you will demonstrate the following:

* What you have accomplished
* Your thought process during design and build
* What it would take to finish the project

This is an intentionally ambitious project for the given time. __We do not expect you to complete it__.

We do expect you to accomplish as much as you can and to learn what it would take to finish it.


Project Requirements
--------------------

Create a software application that will send a Drip Campaign to your users. A Drip Campaign is a schedule of automated messages sent to a user after taking a particular action. For example, after signing up for your service, users might receive a schedule of messages teaching them about the features and capabilities of the service.

An example Drip Campaign:

* Drip Campaign: _"New User Tutorial"_
  * Step One: _"Welcome to our service!"_
    * Sent on Day 1
  * Step Two: _"Complete your profile"_
    * Sent on Day 3
  * Step Three: _"Invite your friends to help you"_
    * Sent on Day 6

Your application must...

* Define and store data models in a database
  * These models must be easily serializable to/from JSON
* Provide an API (or functions) for other entities in the system to:
  * Start a drip campaign to a specific user
  * Query pending and sent messages for a specific user
  * Stop messages from sending before they are sent
* Ensure that messages are sent as close as possible to the time they are scheduled to send
* Be hosted on Github and accessible by the Sendwithus team

#### Bonus points for thinking about:

* System performance and potential bottlenecks
* Data storage and query efficiency at large scale
* Multiple servers performing different tasks
* Deployment process


What We're Looking For
----------------------

We're primarily interested in how you think about technology and code, how you approach
large problems, and your ability to dive fearlessly into new projects.

You will be assessed on the following:

* How much you accomplish in the given time
* Your ability to design and plan the technical requirements
* Use of existing tools and technologies
* Your ability to communicate and discuss what you have designed and built


You May...
----------

* Use any languages, libraries, or frameworks you'd like
* Use the internet freely
* Ask us any questions you'd like (just interrupt one of us)


You May Not...
--------------

* Use a pre-built solution
* Enlist the help of others outside of the Sendwithus team. Remember, questions are okay!
* Work outside of the Sendwithus office
