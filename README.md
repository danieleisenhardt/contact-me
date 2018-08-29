# contact-me
This is a document to read before contacting me.

## developers
This document is mainly meant for recruiters, who make up about 98% of the strangers contacting me. 
* If you want to contact me for advise on development you can feel free to do so. 
* If you like to use this document yourself you may. However I might update it so it would be wise to link to a specific version or fork it and make your own.

## recruiters
If you're an IT recruiter interested in aquiring my services for a client (or if you are the client) this document is meant for you. It may come of a bit stern, but cold calls, emails and LinkedIn messages from recruitment companies have taken up an unacceptable amount of my time over the years. 

Therefore any attempt to contact me that doesn't comply to this list will be replied to with only a short polite request to comply to the list. It will save us both a lot of time in the long run, because the vast majority of offers I've had in the past turned out to be a mismatch. Something we could have known much faster if the important information had been communicated from the start.

### An hourly rate (number)
Communicate an hourly rate as an `integer`. Words like "competitive" or "conforming to market rates" are not `integers` they are `strings`, furthermore they tell me nothing, because when you ask two people to put a number on those words you'll end up getting at least three answers.

*I've heard criticisms of this requirement that it comes of as if money is the only thing that matters to me. This is not true at all. However there are rates that are simply to low for me to work at and even if they aren't there might be a better offer on the table from one of your competitors. It's best to know this right away so neither of us lose any time on discussing offers that are not going to work out anyway.*

### At least one day remote
Although being on-site has it's advantages there's no need to go overboard. I find it very useful to have at least one weekday where I can plan my own time freely and save some transit time.

### No more than one hour transit (one-way)
Transit time is lost time. I try to get at least something out of it with audiobooks or by using my laptop on the train, but there's no two ways about it: I would rather be doing something else with my time. 

In the least favorable scenario I would work four out of five days on site with one hour transit. This adds up to eight hours transit per fourty hour work week. That's twenty percent! 

### Demarcated units of work
Work has to be split up in distinct units that have a state (backlog, to-do, doing, in review, done).

### Functional review
After automated testing a person will look at my work to review it and either mark it accepted or send it back to me.

### Acceptance criteria
Units of work need to come with acceptance criteria. I will work to meet the acceptance criteria. Someone will then review my work according to those acceptance criteria. If the acceptance criteria are met this unit of work is concidered done. New acceptance criteria will be added to a (new) unit of work in the backlog; not to the one in review or one I'm already working on.

### Feature + issue management system
Systems like JIRA are exellent for managing units work. Without one this information ends up in the ether between phone calls, emails and people standing at your desk at inconvenient times.

### Version control with git
This is the industry standard, at least in my sector. I will not work with `svn` or other version control systems.

### Code reviews with pull requests (git-flow)
My code must be reviewed by another developer via pull requests on a git server. I highly reccomend the git-flow strategy for this. Obviously I will also be available to review code from other developers.

### Functional tests
Colloquially know as 'unit tests' functional tests guarantee the functionality of the product. They are by far the least labour intensive tests to write and pay off that effort as soon as you've written them by speeding up development and reducing the number of bugs.

### Continuous delivery
By using an infarastructure that supports continuous delivery the project gets built and tested continuously. This way problems are detected in time and the code is in a more deployable state at all times.

### Automated deployment
There's plenty of solutions out there where the infrastructure watches the `master` branch on the `git` repository automatically deploying any changes. There is no reason to manually deploy products anymore and I won't do it.
