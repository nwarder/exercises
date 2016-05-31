SMTP REST API
=============

You will be creating a web service capable of...

* receiving emails over SMTP and storing contents
* fetching email contents over HTTP REST API
* viewing email contents in a browser

#### Overview

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

Design and create a software application for receiving emails over SMTP, powering an HTTP REST API for retrieving those emails, and a browser UI for displaying received emails.

#### Receiving Emails Over SMTP

* Your application should listen for SMTP connections on port 1025
* You are welcome to use an existing SMTP library to implement your server -- we're not expecting you to learn or implement [SMTP from scratch](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol#SMTP_transport_example)
* You should spend some time developing methods to send test emails to your application
* Emails received should be persisted in a database (of your choosing)

#### HTTP REST API

* Received/stored emails should be available over an HTTP REST API
* Your REST API should consist of two endpoints...
  * One to return a list of emails received by the SMTP server
  * Another to return all information stored for a specific email
* Designing and documenting these endpoints is up to you

#### Browser UI

* Your application should also provide a simple browser UI for viewing received emails
* We strongly suggest you design your UI to use the HTTP REST API described above (just to make things easier)
* In general you should favor functionality over aesthetics for the purpose of this project

#### Other Notes

* We suggest spending a reasonable amount of time planning and designing your system prior to writing code
* Your code repo(s) should be available for review on Github
* Your application should run on your local laptop

#### Bonus points for considering...

* Design/CSS and frontend architecture
* Additional API and UI actions
* Testing and quality assurance
* Server deployment

What We're Looking For
----------------------

We're primarily interested in how you think about technology and code, how you approach
large problems, and your ability to dive fearlessly into new projects.

You will be assessed on the following:

* Ability to design, plan, and rapidly prototype
* Knowledge and use of existing tools and technologies
* Ability to communicate and discuss what you have designed and built


You May...
----------
* Use any languages, libraries, or frameworks you'd like
* Use the internet freely
* Ask us any questions you'd like (just interrupt one of us)


You May Not...
--------------
* Use an existing hosted solution
* Enlist the help of others outside of the Sendwithus team. Remember, questions are okay!
* Work outside of the Sendwithus office
