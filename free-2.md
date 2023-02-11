# Free project 2

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

- Pixel Art Generator Tm. The need is to be able to create pixel art at varying scales using code instead of freehanding with other paint softwares 
- I feel like current a lot of general paint softwares are built for larger scale pictures so when trying to use built in tools at that scale it can be very annoying. While this won't be as quick as freehanding on smaller indivdual elements, ideally it would be used to generate SPRITE SHEETS. So the experience if I could help would be they make one sprite then are able to copy it x times with small variations easily. 
- In short, the need is quick and easy conversion to sprite sheets.

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

- Specifically this is probably only time saving for sprite sheets (especailly environments) were slight variation is required, but one tile being a little wonkhy is fine. A dsl is appropriate because we need to be able to take small changes on a large variety of small sprites. 

### Why you?

_What excites you about this idea? How did you come up with it?_

- I like pixel art, and compared to the other idea I wanted to come up with something artisitic for this idea. The exiting thing is digging into pixel art holdheartedly (and likely video game and animation filters. 

### Domain

_Describe the project's domain in five words._

- Pixel animation sprite sheet generation

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

- I think this could *ideally* be part of a bigger pixel art software (and I think some already exist) but a quick and easy drap and drop exterior coding option is where I would want to go with it. I think its the right way to interact because we want to make it part of an existing workflow, so avoiding pulling up a python document for example is much more significant then some (pregenerated) files that the initial sprite can be droped into. 

### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

-Errors are infinite loops, but thats mainly it. I think when the program runs it just generates all the images and presents them as soon as they are ready. Then they can be downloaded seperately or in a sprite sheet with the original. The user requestes how many they want. 

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

- Easy: generate a bunch of sprites with small adjustments in a sheet. 
- medium: make significant edits to each before exporting - cleaning up-- possibly also moving and placing each new sprite on the generated sheet (ie where the user wants) 
- probably actually making the original pixel art. 

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

- I couldnt find any existing DSL's specifically on pixel art but there are a *lot* of pixel art software (specialized beyond general art programs like photoshop) such as GIMP and paint.net. https://blog.felgo.com/game-resources/make-pixel-art-online
- I think they address the need very well, and with normal copy paste generating sprite sheets is built in. For this DSL to be worthwhile it would have to be **Faster** then control c control v 

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

- I could see it being much more difficult to implement outside of language compared to idea 1. Its also because I have less experience with pixel art. However, since everything is pixel by pixel, it is much easier to loop through/ access specific pixels. So that it has over a general art generation program. 

### Scope

_How big an idea is this? How ambitious is this project?_

- Id say its more ambitous then idea 1. However it has a lot of "checkpoints" that could just be the entire project. 

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

- pros : its art. its using pixels. Lets me dive into pixel art. pixel manipulation can be easy 
- cons : hard to justifiy compared to just general art programs. Image manipulation can be dififuclt. 
