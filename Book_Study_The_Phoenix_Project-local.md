﻿# Book Study: The Phoenix Project

## Section 1: Chapters 1-4

### *Discussion Questions*
* What can we implement/ How can we incorporate lessons?
* What really resonated with you?
* Do you know any Brent's?

### *Themes*
* Companies rely on technology/ computers more and more.
* Lean management principles apply to IT/ knowledge work as much as manufacturing plants
   * Visual work
   * Constraint management

### *Key Takeaways*
* 3 Ways
* 4 types of work
  1. Business Projects
* Lean management applies to knowledge work

#### Chapter 1
* IT needs to work like plumbing
* 2nd and 3rd order effects of critical system failure

#### Chapter 2
* Network operations center as a central location during a crisis pg 30
* Reliance on messiah (Brent) over scripture (systems/ procedures) pg 33
* Working an outage: Establish a timeline pg 35.

#### Chapter 3
* Poor IT hardware maintenance (old SAN) pg 37
* Deployment window 4 months away pg 42
* Change management is critical pg 44
* IT seems to always work late hours pg 44

#### Chapter 4
* “It’s amazing to me how handoffs between Development and IT Operations always get screwed up.” pg 49
* *PZ's Ah Ha moment:* IT is critical to/ involved in many projects pg 49
   * Duh!
* Development environment and production. Case for VMs/ containerization pg 52
* Deadlines driving decisions pg 54 
   * symptom of poor scoping and poor risk management
* Break-fix cycle pg 56 (top)
* Desktop support delays pg 57

## Section 2: Chapters 5-7
### *Discussion Questions*
### *Themes*
### *Key Takeaways*
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

<!--
<div style="page-break-after: always;"></div>

# Book Study: The Phoenix Project
-->

## Section 3: Chapters 8-12

### *Discussion Questions*

### *Themes*

### *Key Takeaways*

#### Chapter 8
* CAB Process:
  * **High Risk**, *"fragile"* - changes must be authorized by CAB before being scheduled and implemented. pg 100
  * **Medium Risk**, *"messy middle"* - change submitter has responsibility and accountability for consulting and getting approval from people potentially affected. Once arranged, they submit the change to the CAB for review and scheduling. pg 102
  * **Low Risk**, *"standard"* - changes we've done many times successfully are preapproved. They still need to be submitted, but can be scheduled without the CAB. pg 102

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
* Brent the bottlenecku
  * Isolate the constraint
  * Put safe guards in place to protect the constrained resource
    * "... create a resource pool of level 3 engineers to handle the escalations, but keep Brent out of the pool. The level 3s would be responsible for resolving all incidents to closure, and would be the only people who can get access to Brent.
    *  ... they are responsible for documenting what they learned, and Brent would never be allowed to work on the same problem twice 
    *  ... Brent not allowed to touch keyboard. He's allowed to tell people what to type and shoulder surf only." 
* "Processes are supposed to protect people." pg 115
* "Every time that we let Brent fix something that none of can replicate, Brent gets a little smarter,nd the entire system gets dumber." pg 116
* 
#### Chapter 11

#### Chapter 12

## Section 4: Chapters 13-16
### *Discussion Questions*
### *Themes*
### *Key Takeaways*
* As BI "developers" we need to be aware of what we get the ops people into.

#### Chapter 13
* Phoenix deployment
  * Crazy working conditions for deployments
  * Massive PCI issue

#### Chapter 14
* Business holds IT resposible for finding solutions not just saying no.
  >> “I need the business to tell me it’s no longer being held hostage by you IT guys. This has been the running complaint the entire time I’ve been CEO. IT is in the way of every major initiative. Meanwhile, our competitors pull away from us, leaving us in the dust. Dammit, we can’t even take a crap without IT being in the way.”
* Marketing Access Database program
  >> a combination of the need to deliver needed features to market, forcing us to take shortcuts, which are causing ever-worsening deployments.
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
<!--
<div style="page-break-after: always;"></div>

# Book Study: The Phoenix Project
-->

## Section 5: Chapters 17-21

### *Discussion Questions*

### *Themes*

### *Key Takeaways*

#### Chapter 17
* Bill resigns

#### Chapter 18
* 
* 
#### Chapter 19
* mtg with CEO and all IT leaders
* Project freeze
#### Chapter 20
* after project freeze, those not relying on constraint can be released
* work centers for IT
  * man, method, machine, measure
  * bill of resources, and routing 
  * work instructions
* utilization is hrs busy / hrs avail
  * 50/50 wait 1 unit vs 90/10 wait 9 units, vs 99/1 wait 99 units

#### Chapter 21
* audit meeting
  * scoping error
  * management controls that backstop IT

## Section 6: Chapters 22-26
### *Discussion Questions*
### *Themes*
### *Key Takeaways*

#### Chapter 22
* improvement kata
  * 2wk cycle for plan, do, check, act
* color coding change board 
  * Green - it internal 20%
  * purple - top 5 business projects
  * yellow - not prioritity
  * pink sticky for stuck

* It project types
  * Replace fragile
  * Vendor upgrades and patching
  * support internal projects
  * audit and security work
  * datacenter work

* three categories
  * increase capacity to constraint
  * doesn't require constraint
  * all others

* laptop replacement queue

#### Chapter 23
* resource graph

#### Chapter 24
* meeting with John at bar
* importance of honest feedback
#### Chapter 25
* meeting with Dick
* managers measurement program
* CFO questions
  * desxrive a good day and bad day
  * what are goals, objectives, and measurements for the year

* systems thinking 

* fleet mgmt oil change analogy

#### Chapter 26
* marketing phoenix project reporting delayed until next year
* planning horizon for IT projects greater than 12 months
<!--
<div style="page-break-after: always;"></div>

# Book Study: The Phoenix Project
-->
## Section 7: Chapters 27-31

### *Discussion Questions*

### *Themes*

### *Key Takeaways*

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
### *Discussion Questions*
### *Themes*
### *Key Takeaways*

#### Chapter 32 (10:38:30)
* decouple from Phoenix
* open source db
* how do you manage db sprawl
* Brent secret mission

#### Chapter 33 (10:52:30)
* VM scale out parrallization, spin up then down
* Starting to see benefits of cloud

#### Chapter 34

#### Chapter 35 
* not being CIO
* Bill's career plan
* Sarah leaving