# Live Coding Challenge, Core
## How to conduct the live coding challenge.
**55 mins maximum**
* prepare before
    * read through the SR writeup
    * read through the CV
    * check GitHub projects asf
* ensure your setup is working (mic, headphones, power adapter, stable connection)
* join the hangouts channel at least two minutes before the start of the session
* be ready to take notes (classic notebook preferable, doesn't have typing noise)
### Give Brief Outlook

Example:

_"Welcome to the AUTO1 live coding challenge. My name is <...>. I would like to give you an outlook what to
expect in the next 60+ minutes. I will briefly introduce myself and what my role at AUTO1 is, then I would like you to do
the same. Afterwards we will jump right into live coding. We will start off with a simple task and then keep
adding features to it, following a discussion about what it takes to get it onto production. Does this sound ok for
you?"_

### Short Introductions
Try to keep it short, without showing disinterest. Yet, we want to focus on the coding and operational part in this
session.

Example:

_"As mentioned earlier my name is <...>. I'm a <...> Engineer in the Core team and with AUTO1 for <...> years. We 
are mainly responsible for evolving the backend platform. Our stack is based on AWS products like ECS, SNS/SQS, ALB and
 more. We are leveraging the Spring Framework and use Terraform, Docker & Jenkins for CI/CD.
 Would you have any questions regarding our stack or the team?_

_"Now, if you would please introduce yourself. I am keen to understand what your current role is and what tech 
stack you were exposed to, starting from the most recent projects, please. What I would specifically like you to skip 
for now, are product and business related details of your previous experiences."_

Listen carefully and make notes. Make sure to not let it continue for too long:

_"Mind me jumping in here? It sounds like you have gained quite some experience already. Very impressive. 
Your new role at AUTO1 is very hands-on, and you will be writing lots of code. Are you ready to do some live coding 
 with me? Then please share your screen, so I can follow and see you in action."_

### Let's start coding
Find the task description [here](TASKS.md). Describe to the candidate what we would like to see:

Example:

_"We will start off with a simple task to warm up. Please read carefully through the description and let's clarify any 
questions. Additionally, please be very verbose on your line of thought, so I can get a better understanding of what 
your rationale is behind the decisions you make. We will follow-up with questions or ask you to skip certain parts."_

Paste the tasks **one after the other** into the Hangouts Chat and guide the candidate through the tasks.

Interrupt gently after latest 50 minutes after coding start.

_"Excuse me for interrupting your flow. I'm afraid we are running out of time for this part of the interview. Thank you 
for the effort so far."_

If you know already at this point, that we will not proceed, you can exit with:

_"I would like you to zip your solution and mail it to our HR. Don't mind cleaning it up from IDE specific files or 
alike. We do not want to keep you busy any further with it.
Now, Let me outline how we will proceed from here. I will discuss your solution with my manager and the recruiter. We
 will get back to you latest within the next 3-4 working days on how we proceed. Would that be ok with you?
 Do you have any questions left? About the process, the team or AUTO1 in general?"_
 
 _"Thank you very much for your time. Have a great rest of the day."_

## Get it to production
**20 mins maximum**

This part is about what it takes to get the solution the candidate has build deployed into production. Hereby we do not
want to go into detail about which web application framework to use to expose the service. We want to find out:
* how to ensure coverage and quality
* how to ensure no regression happened
* what are the choices for CI/CD
* birds view example setup: Docker? Terraform? CircleCI?
* where would these descriptions live?
* who is responsible for that?
* how to ensure liveliness (errors, alerting, asf.)

Example:

_"Since we have the basic functionality implemented now, imagine we have it wrapped up in some web application
 framework and exposed as a web service. What does it take to get it into production? How to ensure
quality and liveliness of the service. What would your ideal CI/CD setup look like and which tools would you choose?"_

Let the candidate explain and ideal setup. Push for specific tools and flows rather than general concepts.
Do not go into a discussion about web application frameworks. Just concentrate on the CI/CD part, which should be
completely agnostic.
See [here](QUESTIONS.md#cicd--test-coverage) for example questions you can follow up with.

## Finish
Finish off thanking for the time and effort and explain how we will proceed.

Example:

_"Now, Let me outline how we will proceed from here. I will discuss your solution with the team and the recruiter. We 
will get back to you latest within the next 3-4 working days on how we proceed. Would that be ok with you? 
Do you have any questions? About the process, the team or AUTO1 in general?"_

_"Thank you very much for your time. Have a great rest of the day."_
 
## Wrap up
* wait for the zip from HR to be forwarded to you
* review the code once again if necessary
* push your notes into SR
* if uncertain, ask a peer discretely for second input
* notify HR in #core-recruitment about the outcome
