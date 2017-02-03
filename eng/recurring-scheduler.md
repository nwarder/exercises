Recurring Reminder System
===========================

You will be designing a system for scheduling and showing yourself recurring reminders.

#### Overview

You are responsible for designing and prototyping as much as you can in the allowed time.
Feel free to leverage any tools, technologies, and/or frameworks you'd like;
in fact we encourage you to use anything that will help you work faster.

After the allowed time, you will demonstrate the following:

* How your system will operate when completed
* Any prototypes you've worked on
* Your thought process during design
* What it would take to finish the project

This is an intentionally ambitious project for the given time. __We do not expect you to complete it__.

We do expect you to accomplish as much as you can and to learn what it would take to finish it.


Project Requirements
--------------------

Design a system for sending yourself recurring reminders. Reminders can be scheduled, viewed, and deleted in a browser. Each time you load the UI, you'll be shown any reminders that have triggered since your last visit. Reminders that have triggered can be dismissed to not show again. Reminders that haven't been dismissed will continue to show up in the UI until you dismiss them.

#### For Example...

You would like to remind yourself to "eat breakfast!" every weekday morning at 9:00am. Using the system described above, you could build a new reminder and schedule it to send "every weekday morning" at "9:00am". You would set the reminder to say "eat breakfast!".

The next weekday morning at 9:00am, the system will generate a new reminder for you. When you next view the UI, you'll see "eat breakfast!" in your reminders. You can dismiss the reminder to remove it from the UI and not see it again until the following weekday morning at 9:00am.

When you no longer need a reminder to eat breakfast, you can delete the reminder schedule completely to prevent future reminders.

#### Browser UI (Frontend)

* Creating a new reminder should prompt for the following information...
  * A UI to build a recurring schedule (ie: weekly on Tues and Thurs @ 7pm)
  * A reminder message (ie: "eat breakfast!")
* You should be able to view and delete all the scheduled reminders that have been created
* Any reminders that have triggered and haven't been dismissed yet should be displayed prominently
* You should favor functionality over aesthetics in any design and prototyping you do

#### Application Server (Backend)

* Your application should be able to store and trigger scheduled reminders
* It should serve the Browser UI and allow it to create and interact with the scheduled reminders
* How you store the data is up to you

#### Triggering Reminders

* Reminders should be triggered asyncronously, within at most 60s of their intended time
  * Be prepared to discuss how your system achieves this

#### Other Notes

* Focus on designing the system in its entirety, rather than actually building it
  * Working prototypes are helpful to prove your design works but not required
* The hardest part of this project will be creating, storing, and triggering the recurring schedules
  * "every weekday at 8am" is easy to say and difficult to codify
* Any code you write should be available for review on Github, and should run on your local laptop

#### Bonus points for considering...

* Testing, verification, and quality assurance
* Design/CSS and frontend architecture
* Additional API and UI actions
* Server deployment


What We're Looking For
----------------------

We're primarily interested in how you think about technology and code, how you approach
large problems, and your ability to dive fearlessly into new projects.

You will be assessed on the following:

* Ability to design, plan, and rapidly prototype
* Knowledge and use of existing tools, technologies, and best practices
* Ability to communicate and discuss what you have designed and built


You May...
----------
* Use any languages, libraries, or frameworks you'd like
* Use the internet freely
* Ask us any questions you'd like (just interrupt one of us)


You May Not...
--------------
* Use an existing software solution
* Enlist the help of others outside of the Sendwithus team. Remember, questions are okay!
* Work outside of the Sendwithus office
