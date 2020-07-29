# Book Study: The Unicorn Project

## Section 1: Chapters 1-4
### *Themes*
* Developer on boarding 
* Developer productivity
* Managing through a crisis

### *Key Takeaways*
* Must have a well documented environment to enable day one builds for new devs
* Proper documentation as important as code to make things work
* State of flow concept like "being in the zone"
* Working on legacy code can be difficult, but is a constant. Spend time upfront trying to make decis ISP one knowing you'll have to redo.

### *Discussion Questions*
* How was your first day at current job?
* Describe our developer environments?
* What is the current build process?
* What area of legacy code have you worked on? How was it? What steps do we take to ensure it's easy to work on legacy code?

#### Chapter 1
* mistakes and entropy are a fact of life
  * culture of fear is corrosive
  * Punishing failure only causes people to hide their mistakes and stifles innovation pg 10
* *"... Leaders to buffer their people from all the political and bureaucratic insanity..."* pg 10
* *"...you know you're in real trouble when even the intern feels sorry for you..."* pg 12
* Long hours symptom of something going wrong
* *"...when people can't get their builds going consistently, disaster is usually around the corner..." pg 17
* Create link page to tools pg 18
  
#### Chapter 2
* Day one build good test of system
  * Day One PBI Model for Anowa running
  * Log on to report server
  * Publish hello world data viz to reports server
* Papers We Love [link](https://paperswelove.org/)
* *"...loves functional programming because she knows that pure functions and composability are better tools to think with..."* p 28
* lambda calc over turing
* strangler pattern for old code refactor pg 24
* Use of work diary. ala Dee in *A Curious Moon* pg 27
* *"...Always good to give more than you get..."*
* Timecards pg 29
* *"...It felt bad enough to be sitting on her butt getting so little done this week, despite her very best efforts, but it feels far worse to have to lie about it..."* pg 30
* *Organizational whiplash* pg 31
* *"...when engineers think of “the customer” in the abstract instead of as a real person, you rarely get the right outcomes..."* pg 32
* All hands townhall meeting

#### Chapter 3
* features important because you can see. Builds important too. Devs can't be productive without a great build, integration, and test process. pg 37
* definition of good day pg 44
* definition of bad day pg 44
* state of flow pg 44
* agony of waiting pg 52
* Constantly running program as way to provide constant feedback pg 54
* functional programming pg 55
  * get rid of loops entirely and use iterators instead pg 55
  * healthy software system is one that you can change at the speed you need, where people can contribute easily without jumping through hoops. pg 57

#### Chapter 4
* Phoenix Proj still on for deployment
* Frantic activity
* Phoenix never deployed before
* No release manager assigned
* Harry Potter reference, Wes is like Big Malfoy
* Capacity planning for server resources
  * transactions per sec
* Laughing out loud at Sarah
  * discussing why instead of how
* Redshirts and Bridge crew analogy
* At end of day going to desk and seeing dev working on features even though the build is failing and they arecin crisis mode.
* Binder from Kurt 80 pgs of documentation
* Informal meeting at "The Dockside Bar"

## Section 2: Chapters 5-8
### *Themes*
* Working in self organizing teams
* Safety with complex systems
### *Key Takeaways*
* Physcological Safety
* Informal teams
* Five Ideals
### *Discussion Questions*
1. Product Requirements Document - Are these still necessary?
1. Can you explain the "Project Funding Model"
1. What do you think of the intersperal of the board member emails as a way to show the background business discussions?

#### Chapter 5
* Dockside bar hangout
* "Rebel Alliance" - bypassing normal org structure
* Characters
  * Dave - Dev team lead
    * "Never Asks for permission..." -  not advocating that.
    * can't do anything without 20 meetings
  * Shannon - InfoSec
    * Security Engineer
    * Automated security testing
    * ran Red Team exercises last year
  * Brent
    * Infastructure expert
    * Maxine documented all the ENV variables
  * Dwayne - Senior DB and Storage Eng from Ops
    * Bowling shirt
  * Adam - Test Engineer
    * Infrastructure expert
    * Automate the legacy test suite
* Cloud strategy for migration of DBs to open source DBs.
  * Cost savings, better relationship w/ vendor
* Disatisfaction with beuracracy
* "The square"
  * Up 2 levels, over 2 levels, down 2 levels just to talk to an engineer 
* "You can't do anything without first convincing a bunch of steering committees and architects or having to fill out a bunch of forms or work
with three or four different teams who each have their own priorities.
Everything is by committee. No one can make decisions, and implementing even the smallest thing seems to require consensus from everyone."
* PRD - Product Requirements Document
  * Still make sense? We can prototype faster
  * balanced approach - helps to clarify BU thinking
* "Red Shirts" type analogy
* Everyone is the custodian of customer's data.
* "...we can only win by innovating and understanding our customers, whcich we can only do by mastering data."
* Project funding model a big problem
* Data analytics group from marketing who needs help
* Phoenix project and procurement issues make it an emergency
  * Sound familiar?
* two agenda items
  * Share intel on who needs help and others to recruit
  * Share something learned lately or new technologies that could change the game
  
#### Chapter 6
* Continuous builds pg 99
* Automated testing pg 99

#### Chapter 7
1. code deployment lead time pg 106
1. code deployment frequency pg 106
1. time to resolve problems pg 106
* "... are predictive of software delivery, operational perfromance, and organizational performance...
they correlate with burnout, employee engagement, and more..." pg 106
* ".. simplicity enable locality..." pg 106
  * locality = loosely coupled
    * in code and in organizations
* *improvement* of daily work **>** daily work itself pg 107
* "complexity debt" pg 108
* Five Ideals pg 108-110
  * First: Locality and Simplicity
  * Second: Focus, Flow, Joy
  * Third: Improvement of Daily Work
  * Fourth: Psychological Safety
  * Fifth: Customer Focus

#### Chapter 8
* Data Hub team
  * part of a message bus system
* Kurt's description of **manager's job:** "listen, do whatever [your employees] need [you] to do to help make [them] successful, and remove any obstacles in [their] way"
* "Software is like a city, constantly undergoing change, needing renovations and repair."
* "heisenbugs" = act of observation changes the nature of reality itself
* Maxine's use of functional programming concepts to fix bug pg. 121-122
  * example of First Ideal - Locality and Simplicity
* "Being able to test and push code to production is more productive, makes for happier customers, creates accountability of code quality to the people who write it, and also makes the work more joyful and rewarding."
* extended warranty feature takes too many teams to get it done. Not a "two-pizza" team
* not able to see production logs
* Sev2 Data Hub issue really related to internal networking issue
* "...we can't be the people with a solution, peddling them to people who don't know they have a problem."
* Annecdotes about tech giants and feature freezes to fix tech debt
* Nokia killed by tech debt
* "Technical debt is inherently neither good nor bad - it happens because in our daily work we are always making trade-off decisions" pg 131
* working with eigth other teams just to get things done
* Toyota andon cord example
* "... a bad system will beat a good person everytime..." - W. Edwards Deming
* increasing "coordination costs" result in higher costs of delay
* General Stanley McChrystal decentralized decision making example for Iraq
* Example of overworked engineer
  * 4 late nights in a row
  * lots of terminal windows open
    * typed command into wrong terminal window
* Alcoa saftey zero deaths example
* functional programming pg 122
* name, blame, and shame pg 136
* "...every incident is a learning opportunity, an unplanned investment that was made without our consent." pg 137

<div style="page-break-after: always;"></div>

# Book Study: The Phoenix Project

## Section 3: Chapters 9-12

### *Discussion Questions*

### *Themes*

### *Key Takeaways*

#### Chapter 9
- Testind Day
- throwing a party for QA

#### Chapter 10
- code merge compared to writing a Hollywood script in isolation pg 156
- merge code once per day pg 157
  - "... small batch sizes, like in manufacturing, create
a smooth flow of work ..."
- _**bad idea**_
    - "... if it hurts, do it less often ..." pg 159
- to make it hurt less you have to merge **more** frequently pg 158
 
#### Chapter 11
- Contiunous intergration pg 181
- Continuous deplyment pg 181
- colocateing DEV and QA pg 181

#### Chapter 12
- promotional items SKUs pg 183

<!--
## Section 4: Chapters 13-16
### *Themes*
### *Key Takeaways*
### *Discussion Questions*
#### Chapter 13
- whitespace deployments pg 202
  - like "dark launches"
  - ie. adding a couple of blank lines to the end of HTML or config files
  - in theory this wouldn't change functionality in any way
- questions to ask when trouble shooting with a team pg 203
  - "Good hypothesis, Brent. What are you thinking?"
  - "How can we test your idea?" 
- blamless postmortem pg 208
#### Chapter 14
- customer personas pg 212-213
#### Chapter 15

#### Chapter 16

<div style="page-break-after: always;"></div>

# Book Study: The Phoenix Project

## Section 5: Chapters 17-20
### *Themes*
### *Key Takeaways*
### *Discussion Questions*

#### Chapter 17

#### Chapter 18

#### Chapter 19

#### Chapter 20

## Section 6: Chapters 21-24
### *Themes*
### *Key Takeaways*
### *Discussion Questions*
#### Chapter 21

#### Chapter 22

#### Chapter 23

#### Chapter 24
## Section 7: Chapters 25-28
### *Themes*
### *Key Takeaways*
### *Discussion Questions*
#### Chapter 25

#### Chapter 26


<div style="page-break-after: always;"></div>

# Book Study: The Phoenix Project

#### Chapter 27

#### Chapter 28
## Section 8: Chapters 29-32
### *Themes*
### *Key Takeaways*
### *Discussion Questions*
#### Chapter 29

#### Chapter 30

#### Chapter 31

#### Chapter 32
## Section 7: Chapters 33-35
### *Themes*
### *Key Takeaways*
### *Discussion Questions*
#### Chapter 33

#### Chapter 34

#### Chapter 35
-->
