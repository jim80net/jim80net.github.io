# Elements of Agile in Operations
This is a story all about how  
Operations got flipped-turned upside down  
And I'd like to take a minute  
Just sit right there  
I'll tell you how to run an ops team with an Agile flair.  

## Pair admin-ing
![pair kaiju-fighting](http://laughingsquid.com/wp-content/uploads/2014/07/pacific-rim-jaeger-pilot-a-simul.jpg =500x)

### Here is a list: 
- Less distraction: spend less time checking mytwitface, and _more time_ actually working. Yes, really. 
- Less getting stuck: With experienced pairs, while one is "driving" the keyboard and worrying about implementation, the other "navigates" and keeps the pair churning through it's objectives. 
- More context transfer: When pairs have disproportionate experience or context in the group, the deficient one "drives" while the other "guides."
- Less overload: Periodically switch roles in order to keep fresh. Experienced pairs can seemlessy transition between the two states. 
- Less [cowboyism](#Susie): Instead of one person knowing all about a system, and  
  1. Increasing exposure to [bus factor](TODO) by becoming a one-man silo
  2. Becoming a go-to person for a customer or sub-organization.
  at least two people will know about what is going on. If a pair rotates during a story, then more than two people will have context on the story. All of this helps reduce the impact of [drive-by's](TODO) and enables [interrupt pairs](#Interrupt_pairs). 
- Less miscommunication:
- Less nooby damage: Great job noob, you took it down. If only someone was standing over your shoulder to stop you. 
  
### Susie, the go-to woman
You might have a Susie in your organization. Susie is a hero, she likely knows it, and she may even treasure the fact. Unfortunately, this person often has a seriously high bus-factor, and her presence actually increases drive-by's ("Susie fixed it for me last time..."). While Susie is probably a great person, she presents a great risk to your organization. TODO(moneyball)

The [Theory of Constraints](TODO), as applied to IT management teaches us to "protect and elevate the constraint." Does this mean building a team around Susie, to ensure her work buffer remains full? No, her uniquene capacity is a constraining factor. Further, it's not Susie herself that is the constrained resource, it's her ability and know-how. Pair Susie immediately, so that her exclusive context can start flowing to others. She may complain that this reduces her productivity because she has to spend more time teaching and less time doing. She will be right, but this is a worthwhile cost. During your mandate, fires will still find their way to her anyways. You're on the right track as long as the frequency of these interruptions go down over time. [The Goal](TODO) is to improve [throughput]() and distilling Susie's know-how to the team results in greater throughput in the long run, not less. 


### Workstation setup

Workstations should be setup uniformly. Use CI to ensure that workstation configurations are consolidated and updated regularly. All work should be done in the SCM of choice. No workstation should be optimized to the point that another admin cannot use it.
 
  
## Iterations and the Iteration Planning Meeting (IPM)

### IPM

### Context switching and flow 
![Never interrupt a programmer](h ttp://i.imgur.com/3uyRWGJ.jpg =300x)

[Flow](TODO) in an operations context means that admins are able to work without interruption of state of mind. Flow is important because a team that suffers high-interrupts consequently suffers high context-switching, dramatically reducing efficiency. 

Interruptions can happen because:  

1. an admin gets stuck and needs to change gears.  
2. work escapes outside the locus of control ( a meeting becomes necessary, lack of access requires external action )  
3. drive-by's and other unplanned work

These interruptions can be reduced by: 

1. [Pair](#Pair_programming) admins in order to reduce how often admins get stuck  
2. [Reduce the cost of seeking external action.](TODO)
3. Plan for interruptions by assigning [interrupt pairs](#Interrupt_pairs) to handle drive by's. 

Reducing interruptions does not mean completely eliminating unplanned work. Unblocking others is of high-value. An Agile organization is able to respond to unplanned work in a coordinated way. 

 
#### Reducing the cost of external action. 

- If possible, break up stories such that external calls are invoked at the conclusion of the story.  
- Encourage internal teams to employ interrupt pairs to help reduce meeting volume and going straight to the end of the ticket queue.  
- Consider bringing some things in-house. Frequently touched services, say firewall changes by the networking team for example, may be better served when managed internally. Identification is as simple as asking. Your admins will know what could be done in-house more efficiently because they  cringe everytime they have to e-mail networking to open port 22,80,443 on a new web-server and wait a week while the ticket makes it slowly up the ticket queue. If networking must retain control of the firewalls, maybe you can bribe them into prioritizing the self-service portal. Do something. 


#### Interrupt pairs

Dedicate [interrupt pairs](#Interrupt_pairs) to manage walk-ups. While they may not have enough context for every interruption, they'll act as a first line of defense against disrupting flow. They will work with the walk-up as they are able. If stories are generated as a result, add them to the icebox for planning in the coming iteration. If a customer requires immediate assistance for a valid reason, engage leadership (whether this is a project manager, team lead, or team manager) to prioritize the work. 

These folks perform two critical functions: 

- unblock other teams. 
- help maintain flow for their peers. 

  
## Blameless Postmortems


## Retro
### =)
### =|
### =(




