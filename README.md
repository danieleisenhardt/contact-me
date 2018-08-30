# contact-me
This is a document to read before contacting me.

## Developers
This document is mainly meant for recruiters, who make up about 98% of the 3<sup>rd</sup> parties contacting me. 
* If you want to contact me for advice on development, you can feel free to do so. 
* If you would like to use this document yourself, you may. I may however update it so it would be wise to link to a specific version or fork it and make your own.

## Recruiters
If you're an IT recruiter interested in procuring my services for a client (or if you are the client) this document is meant for you. It may seem somewhat harsh, however cold calls, emails and LinkedIn messages from recruitment companies have taken up an unacceptable amount of my time over the years. 

Therefore, any attempt to contact me that doesn't comply with this list will be replied to with only a short polite request to refer to the list. It will save us both a lot of time in the long run, because the vast majority of offers I've had in the past have turned out to be a mismatch- Something which we could have found out much faster if essential information had been communicated from the start.

These requirements are all mandatory, but I can help out if the prospect client isn't there yet on technical matters. In this case this will be the first work I will do for them, because I will not be working on any functionality without the infrastructure first being in place.

### An hourly rate (number)
Communicate an hourly rate as an `integer`. Words like "competitive" or "conforming to market rates" are not `integers` they are `strings`, furthermore they tell me nothing because when you ask two people to put a number on those words you'll end up getting at least three answers.

*I've heard criticisms of this requirement that it gives the impression, as if money is the only thing that matters to me. This is not true at all. However there are rates that are simply to low for me to work for and even if they aren't there might be a better offer on the table from one of your competitors. It's best to know this right away so neither of us lose any time on discussing offers that are not going to work out.*

### At least one day remote
Although being on-site has its advantages there's no need to go overboard. I find it very useful to have at least one weekday where I can plan my own time freely and save some transit time.

### No more than one hour transit (one-way)
Transit time is lost time. I try to get at least something out of it with audiobooks or by using my laptop on the train, but there's no two ways about it: I would rather be doing something else with my time. 

In the least favourable scenario I would work four out of five days on site with one hour transit. This adds up to eight hours transit per forty-hour work week. That's twenty percent! 

### Demarcated units of work
Work must be split up in distinct units that have a clear status (backlog, to-do, doing, in review, done).

### Functional review
After automated testing a person will look at my work to review it and either mark it accepted or send it back to me.

### Acceptance criteria
Units of work need to come with acceptance criteria. I will work to meet the acceptance criteria. Someone will then review my work according to those acceptance criteria. If the acceptance criteria are met, this unit of work is considered done. New acceptance criteria will be added to a (new) unit of work in the backlog; not to the one in review or one I'm already working on.

### Feature + issue management system
Systems such as JIRA are excellent for managing units of work. Without a system like this this the information ends up 'in the ether' between phone calls, emails and people standing at your desk at inconvenient times.

### Version control with git
This is the industry standard, at least in my sector. I will not work with `svn` or other version control systems.

### Code reviews with pull requests (git-flow)
My code must be reviewed by another developer via pull requests on a git server. I highly recommend the git-flow strategy for this. Obviously, I will also be available to review code from other developers.

### Functional tests
Colloquially know as 'unit tests', functional tests guarantee the functionality of the product. They are by far the least labour-intensive tests to write and pay off that effort as soon as you've written them by speeding up development and reducing the number of bugs.

### Continuous delivery
By using an infrastructure which supports continuous delivery the project gets built and tested continuously. This way problems are detected in time and the code is always in a more deployable state.

### Automated deployment
There are plenty of solutions out there where the infrastructure watches the `master` branch on the `git` repository automatically deploying any changes. There is no reason to manually deploy products anymore and I won't do it.

### Respectable company and project
Work isn't just about the money or even the joy of work (though sometimes it is). It also provides a feeling of accomplishment, and is often a topic of conversation at dinner parties with friends and family.

Therefore, I will not work with companies and projects involved in for example: cluster munitions, predatory lending, pornography, the promotion of gambling to people on welfare, or forcing clinical drugs on perfectly functioning elementary school children.

### Clear lines of communication
I need to be informed clearly in writing (via email is fine) who the people are I'm working with and who I should contact regarding which topic. For example: there may be a Lead Programmer for technical matters, a Department Manager for organizational matters and a HR Representative for personal matters.
