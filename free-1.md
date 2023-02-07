# Free project 1 - Dice management

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

- The project would serve me specifically. Thats a joke, it would be for calculating probabilities of dice etc easily and quickly with changing elements. The language is so you can have coded results depending on the randomized elements. Things like rerolling 1's, rolling critical successes (ie when you roll a maximum value, you roll again)  etc .


### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

- Specifically, easily accessing average results and expected values that requires limited statistical knowledge (such as jargon). Currently most values when game designing can be calculated directed (especially simple ones) but more complex results (and expected value) is less obvious and usually just guessed. Ideally with this you could load up a python doc, or use a exterior DSL to quickly throw together expect value and results cleanly.  


### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

- Unlike other tools, it should be a DSL specifically to utilize If -else terminology and useful ness. If I roll a 1, and a series of actions occur, then I want this dsl to account for that. 

### Why you?

_What excites you about this idea? How did you come up with it?_

Im a big Game Designer (ttrpg). It would help me do the things i want to do specifically. Honestly the more interesting question is if it would help anyone else. 

### Domain

_Describe the project's domain in five words._

Game Design result analysis 

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

- I think it could be an external thing, but even just a python plugin would be usable. Something quick and easy. Honestly anything that could quickly export visuals, so probably exterior is ideal 

### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

- The program runs, calculates all the possibilities (running through each) then shows the expected value based on whats reported. Peferably in nice visuals 

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

- It should be easy to get expected values of dice rolls, and add contingencies for certian results. 
- It should be difficult to edit the generated visuals, but it is possible just not the main use of the software 
- I think keeping it hyper specific is better, so anything outside of math, loops and statistics is a no no 

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

- I mean any statistics DSL is in this domain (python can do it generally) (R and mathematic etc is also definitely possible) And many sites have dice roll projections, but I think the goal is to give a middle ground between complete open statisitcal analysis and quick but powerful expirimentation. 

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

- uhhhhhh. If im interpreting this question correctly, I would think its good for this. Actually implementing code that checks contingencies etc is not difficult 
(even doable in just python) the goal is to make an easy and clear design of it. 

### Scope

_How big an idea is this? How ambitious is this project?_

- I think its pretty manageble, especially if its implemented with a dsl that can already generate graphs etc 

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

- Pros: I definitely would care about and use  this - relatively simple to implement outside of langauge design 
- cons: Limited use, not very flashy - easily done with other languages already.
