# Book Study: The Phoenix Project

## Why even do DevSecOps?
* Air Force "Gonkulator" case study
  * https://www.fastcompany.com/40588729/the-air-force-learned-to-code-and-saved-the-pentagon-millions
  * https://www.airforcemag.com/article/making-the-kessel-run/
  
* This is just one example of the book's purpose of "Helping Your Business Win"

## Frontmatter
> "*The Phoenix Project* is a must read for business and IT executives who are struggling
> with the growing complexity of IT."
> 
> Jim Whitehurst &mdash; President and CEO, Red Hat, Inc.

> "Every person involved in a failed IT project should be forced to read this book."
> 
> Tim O'Reilly &mdash; Founder & CEO of O'Reilly Media

## References
* [Palo Alto Networks Discussion](https://www.youtube.com/watch?v=ygSvdv-QpUM)
  * IT organized around technology much like 1900's style manufacturing organized around big machines
  * Cross-functional alignment (breaking down silos)
  * "Organize around the work"

## Week 1: Chapters 1-3
### *Themes*
* Companies rely on technology/ computers more and more.
* Lean management principles apply to IT (any knowledge work really) as much as manufacturing plants
   * Visual work
   * Constraint management
* 3 Ways
* 4 types of work
  1. Business Projects

### *Discussion Questions*
* What can we implement/ How can we incorporate lessons?
* What really resonated with you?
* Do you know any Brent's?

### *Notes*

#### Chapter 1 - Tuesday, September 2
* IT needs to work like plumbing
* 2nd and 3rd order effects of critical system failure
* It's interesting that Bill assumes calls are related to an outage. How bad is his life to automatically assume a work call is a crisis?
* Bill jokes about a career ending outage and acknowledges that it's a thing. Is it like that where we work?.
* Is IT in a dingy area where you work?
* TV reference: *The IT Crowd*

> "Because they're ... not people with a technology background, they'll publicly promise the impossible and IT will have to figure out how to deliver."
  * Is this familiar where you work?
> "For the last decade, like clockwork, new CIOs would come and go every two years."
  * Why is this the normal today? Is it like that with other C suite execs? 
> "CIO stands for 'Career is Over'. And VPs of IT Operations don't last much longer."

> "... the trick to a long career in IT Operations management is to get enough seniority to get good things done but keep your head low enough to avoid the political battles that make you inherently vulnerable. I have absolutley no interest in becomming one of the VPs who just give each other PowerPoints all day long."

> "... it seems very difficult for senior IT leadership to succeed here. Any request for budget or staff is always shot down, and executives are replaced so quickly, some never get a chance to fully unpack."
  * Not sure this is true for CNO. Seem to have had reasonable increase in resources from 2019 to 2022. Increase will stop and eventually we'll need to do more with less.

> "What do you want most... And what don't you want?"
  * Good framing questions.

> "... IT systems to be reliable and available, and for the business to be able to depend upon them. You want disruptions to normal operations kept to an absolute minimum so the business can focus on getting Phoenix done."


#### Chapter 2 - Tuesday, September 2
* Help desk and Service desk are the face of the entire IT organization pg 31
* Network operations center as a central location during a crisis pg 30
* Reliance on messiah (Brent) over scripture (systems/ procedures) pg 33
* Benefits of virtualization pg 34
* Working an outage: Establish a timeline pg 35.

> "To get Finance the dat they need, we may have to cobble together some custom reports, which means bringing in the application developers or database people.
> But that's like throwing gasoline on the fire. Developers are even worse than networking people. Show me a developer who isn't crashing production systems, and I'll show you one who can't fog a mirror."

> "...continue to plan for the worst and we fully document plan B, so we can pull it off without further complications."

> "I feel better, now that I've seen the problem from the business perspective."

> "When something hits the fan, you need all the various stakeholders and technology managers to communicate and coordinate until the problem is resolved."



#### Chapter 3 - Tuesday, September 2
* Poor IT hardware maintenance (old SAN) pg 37
* Deployment window 4 months away pg 42
* Change management is critical pg 44
* IT seems to always work late hours pg 44

<!--

## Week 2: Chapters 4-6
### *Themes*
*

### *Key Takeaways*
*

### *Discussion Questions*
*

#### Chapter 4
* “It’s amazing to me how handoffs between Development and IT Operations always get screwed up.” pg 49
* IT is critical to/ involved in many projects pg 49
* Development environment and production. Case for VMs/ containerization pg 52
* Deadlines driving decisions pg 54 
   * symptom of poor scoping and poor risk management
* Break-fix cycle pg 56 (top)
* Desktop support delays pg 57

## Section 2: Chapters 5-7
### *Themes*
* Theory of Constraints (TOC)
* We need to see our selves
* Are we doing the *right things*?
* Are we doing *things right*?
### *Key Takeaways*
* Critical to have an understanding of what work we're doing and where is it coming from
### *Discussion Questions*
* Where do we keep our master work list?
* Can you identify a constraint in your current workflow?
#### Chapter 5
* Old servers barely hanging on pg 68
* Brent is bottleneck according to Theory of Constraints pg 69
* List of work to do pg 70

#### Chapter 6
* “Knowing is always better than not knowing.” pg 76
* Resource planning pg 76
* Hiring and time until EE is effective 6-12 months pg 77
* Change management card process pg 80-81

#### Chapter 7
* “Can’t achieve strategic until you’ve mastered the tactical.” pg 87
* Deliverables, outages, and compliance pg 88
* Three management movements pg 89
  * Theory of Constraints
  * Toyota Production System
  * Total Quality Management
* WIP is the silent killer
* Pace work to the bottleneck pg 90
  * "... any improvements made *anywhere besides the bottleneck* are an illusion" 
* “... ensure the fast, predictable, and uninterrupted flow of planned work that delivers value to the business while minimizing the impact and disruption of unplanned work, so you can provide stable, predictable, and secure IT service.” pg 91
* "... figure out how to control the release of work into IT Operations and, more importantly, ensure that your most constrained resources are doing only the work that serves the goal of the entire system, not just one silo."
* Three Ways pg 91
  1. **Fast flow of work as it moves from Development into IT Operations.** That is what is between the business and the customer.
  1. **Shorten and amplify feedback loops, so we can fix quality at the source and avoid rework.**
  1. **Create a culture that simultaneously fosters experimentation, learning from failure, and understanding that repetition and practice are the prerequisites to mastery.**
* Four types of work pg 88 & 92
  1. Business Projects

<div style="page-break-after: always;"></div>

# Book Study: The Phoenix Project


## Section 3: Chapters 8-12
### *Themes*
* IT Value Stream
* Change control process
* Link between plant floor management and IT Operations
### *Key Takeaways*
* How to deal with a constraint to a system
* Four types of work
  1. Business Projects pg 92
  1. IT Internal Projects pg 109
  1. Changes pg 110
### *Discussion Questions*
* Do you have a Value Stream Map for your workflows?
* What is the percent of changes each week that fail or need to be deferred/ rescheduled?

#### Chapter 8
* CAB Process:
  * **High Risk**, *"fragile"* - changes must be authorized by CAB before being scheduled and implemented. pg 100
  * **Medium Risk**, *"messy middle"* - change submitter has responsibility and accountability for consulting and getting approval from people potentially affected. Once arranged, they submit the change to the CAB for review and scheduling. pg 102
  * **Low Risk**, *"standard"* - changes we've done many times successfully are preapprove. They still need to be submitted, but can be scheduled without the CAB. pg 102

#### Chapter 9
* Dealing with a SEV 1 incident pg 105
  * Start call by presenting a timeline of all relevant events pg 106
  * Need to know all changes pg 105
  * Finger pointing is unproductive pg 105 
  * Announce and discuss any changes before implementing pg 106
* Four types of work
  1. Business Projects pg 92
  1. IT Internal Projects pg 109
  1. Changes pg 110

#### Chapter 10
* Brent the bottleneck
  * Isolate the constraint
  * Put safe guards in place to protect the constrained resource
    * "... create a resource pool of level 3 engineers to handle the escalations, but keep Brent out of the pool. The level 3s would be responsible for resolving all incidents to closure, and would be the only people who can get access to Brent.
    *  ... they are responsible for documenting what they learned, and Brent would never be allowed to work on the same problem twice 
    *  ... Brent not allowed to touch keyboard. He's allowed to tell people what to type and shoulder surf only." 
* "Processes are supposed to protect people." pg 115
* "Every time that we let Brent fix something that none of can replicate, Brent gets a little smarter, and the entire system gets dumber." pg 116

#### Chapter 11
* Continued development of CAB process
* Need to limit work in the system
* Color coding change cards if they involve bottle neck
* Work in Process (WIP) of IT work

#### Chapter 12
* Phoenix project deployment day
* Inconsistent environments
* IT working all hours
* Database migration scripts failures
* Impact to retail store POS's
* Request to delay Phoenix launch
* Credit card security failure

## Section 4: Chapters 13-16
### *Themes*
* Business and IT need to work together
### *Key Takeaways*
* IT exists to satisfy business requirements.
  * Can't always say no.
* "Deciding what not to do is just as important as deciding what to do."
### *Discussion Questions*
* As BI "developers" we need to be aware of what we get the ops people into.
* Do we as IT have a good idea of how we prioritize business projects?

#### Chapter 13
* Phoenix deployment
  * Crazy working conditions for deployments
  * Massive PCI issue

#### Chapter 14
* Business holds IT responsible for finding solutions not just saying no.
  > “I need the business to tell me it’s no longer being held hostage by you IT guys. This has been the running complaint the entire time I’ve been CEO. IT is in the way of every major initiative. Meanwhile, our competitors pull away from us, leaving us in the dust. Dammit, we can’t even take a crap without IT being in the way.”
* Marketing Access Database program
  > a combination of the need to deliver needed features to market, forcing us to take shortcuts, which are causing ever-worsening deployments.
* Post Phoenix party

#### Chapter 15
* Change control process prevented disaster
* Fourth category of work is "Unplanned Work"
  1. Business projects
  2. IT projects
  3. Change control
  4. Unplanned work
* Three ways
  1. Fast flow of work from dev through ops to business
  2. Feedback
* Stabilize environment
* Visualize and manage work
* Manage constraint
* "The Goal" by Eli Goldratt
  1. identify the constraint.
  2. exploit the constraint
  3. subordinate the constraint
  4. elevate the constraint
  5. prevent inertia from becoming the constraint
* **Deciding what not to do is just as important as deciding what to do.**
* invoicing issue
* the right way to handle a sev 1 incident
* quitting over convictions

#### Chapter 16
* Invoices incident
* Dealing with a Sev-1 incident
* Bill resigns

<div style="page-break-after: always;"></div>

# Book Study: The Phoenix Project

## Section 5: Chapters 17-21
### *Themes*
* Building trust
* Using Lean techniques to manage IT
### *Key Takeaways*
* Project freeze
* Work centers for IT
### *Discussion Questions*
* Do we have anything like a Bill of Resources or Bill of Materials?


#### Chapter 17
* Making up with Steve

#### Chapter 18
* mtg with CEO and all IT leaders
  * Steve's background
#### Chapter 19
* mtg with CEO and all IT leaders
  * Other leader's backgrounds
* Project freeze
#### Chapter 20
* after project freeze, those not relying on constraint can be released
* work centers for IT
  * man, method, machine, measure
  * bill of resources, and routing 
  * work instructions
* utilization is hrs busy / hrs avail
  * **50/50 wait 1 unit vs 90/10 wait 9 units, vs 99/1 wait 99 units**

#### Chapter 21
* audit meeting
  * scoping error
  * management controls that backstop IT

## Section 6: Chapters 22-26
### *Themes*
* IT needs to have a good understanding of the business measures
### *Key Takeaways*
* Improvement kata
* IT project types
* Utilization graph points to why wait times can be so long
* Fleet management oil change analogy
### *Discussion Questions* 
* What are our businesses kpis? Do we have a chart or slide like Dick's

#### Chapter 22
* improvement kata
  * 2wk cycle for plan, do, check, act
* color coding change board 
  * Green - IT internal 20%
  * purple - top 5 business projects
  * yellow - not priority
  * pink sticky for stuck

* It project types
  * Replace fragile infrastructure
  * Vendor upgrades and patching
  * support internal projects
  * audit and security work
  * data center work

* three categories
  * increase capacity to constraint
  * doesn't require constraint
  * all others

* laptop replacement queue

#### Chapter 23
* resource graph
#### Chapter 24
* meeting w/ John at bar
* importance of honest feedback

#### Chapter 25
* meeting with Dick
* managers measurement program
* CFO questions
  * describe a good day and bad day
  * what are goals, objectives, and measurements for the year
* systems thinking 
* fleet management oil change analogy

#### Chapter 26
* marketing phoenix project reporting delayed until next year
* planning horizon for IT projects greater than 12 months

<div style="page-break-after: always;"></div>

# Book Study: The Phoenix Project

## Section 7: Chapters 27-31
### *Themes*
* Using Lean tools to improve IT operations
### *Key Takeaways*
* Shadow IT
* Flow of work one way - "Single Piece Flow"
* Find constraint, then look for way to automate
### *Discussion Questions*
* Do we use process mapping to visualize our workflows?
* What are our top three critical workflows?
* Do we have scripts or something like an automatic build system?

#### Chapter 27
* CIA triangle of data
  * Confidentiality
  * Integrity
  * Availability
#### Chapter 28 (9:25:45)
* Shadow IT
* Increased performance of group
* Phoenix deployment #2

#### Chapter 29 (9:47:24)
* mtg w/ Steve re: John's recommendations
* No reverse gear
* Flow of work one way - "Single Piece Flow"
* Faster cycle time, speed up release schedule
  * when things are bad, do more of them to improve not less to avoid.
  * like football practice or military training
* SWAT team to do some features

#### Chapter 30 (10:04:15)
* visit to MRP plant
* "inner Allspaw"
* takt time
* find constraint, then look for way to automate
* Ohno, Spear, Rother
* Dev -> Ops -> QA -> Business = super tribe
* Eric Reis "Lean Startup"

#### Chapter 31 (10:38:30)
* Process mapping white board
* Value Stream Map
* Automating environment setups

## Section 8: Chapters 32-35
### *Themes*
* IT critical competency for all senior business leaders
### *Key Takeaways*
* Small little teams (2 pizza team) to rapidly develop features
* Loosely coupled architecture better for flexible development
* VM architecture to help scale out and up
### *Discussion Questions*
* Can you name any senior business leaders in our organization with an IT background?

#### Chapter 32 (10:38:30)
* decouple from Phoenix
* open source db
* how do you manage db sprawl
* Brent secret mission

#### Chapter 33 (10:52:30)
* VM scale out parrallization, spin up then down
* Starting to see benefits of cloud

#### Chapter 34
* Trouble at Thanksgiving goes much more smoothly
* Ability to rollback features
* Unicorn team moving to continuous delivery

#### Chapter 35 
* not being CIO
* Bill's career plan
* Sarah leaving

### Books I'd Like to See
* Book from Sarah's perspective (Business Perspective).
* Book from Bill's prior work to create a good mid level ops team. Phoenix Project for small teams.

-->
