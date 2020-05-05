# Efficient and successful programming assignments
This repository aims to help you to get better grades for your programming project in less time.
It is targeted at students in the *Programming Fundamentals 2* class at [USI](https://www.usi.ch/en) 
but its content probably generalizes to most programming assignments in software engineering.

Jump directly to the two main chapters:
- [How to get a good grade](#a-guide-to-good-grades)
- [Common problems and countermeasures](#common-problems-and-countermeasures)

## A guide to good grades
The following points will help you to get a good grade for your project:

#### :+1: :+1: :+1:  Be fair (no plagiarism, no late submission, no warning suppression) :exclamation:
Do not copy any code from anywhere. 
If you consulted online references (e.g. StackOverflow) to solve a problem, make sure you fully understand and re-write the solution
yourself (instead of copying). Make sure to appropriately reference your sources.

Also, cheap tricks like `@supresswarnings` or simple renaming of variables to hide code duplication look 
very bad when detected during grading :triumph:. Do not risk it!

#### :+1: :+1: :+1: Code compiles without errors
If your code does not compile, your TA cannot run it and won't be able to give you any points for any of the cool stuff you implemented.
For this, it is important that you do not use any external libraries (which your TA won't bother installing).

#### :+1: :+1: :+1: Happy path functionality
Make sure at least one minimal happy path works and is described in your Readme. [-> minimal first principle](./mini_sections/minimal_first.md)

#### :+1: :+1: Code documentation and project readme
Document all exposed methods in your code. 
This does not just make it easier for you to work in a team, but its also easier for the TAs to 
understand what a function is supposed to do - and to give you partial points 
even if the implementation of a method is incorrect or incomplete.
Additionally, a 'README.md' should explain how to use your program, how to run it
and also transparently declare what's not yet implemented. 

#### :+1: :+1: Reasonable software design choices
Sticking to good software design choices makes your debugging easier and your lecturer/TA who has to do the grading 
happier. 
Use **abstraction (inheritance)** and **helper classes** to avoid code and documentation duplication.
Avoid **god-classes** (huge classes with too much logic) and **spaghetti code** (unstructured code).
You can use various **tools** (e.g. PMD, CPD) to help you with this. 

[-> PF2 Design Principles](./pf2_specific/good_practice.md)

#### :+1: :+1: High test coverage with meaningful tests
Make sure all your code is covered by unit tests.
Your tests should be effective: They should check for more than just a happy path and also treat edge conditions.:

1. Good testing will impress during grading and convince the TA that your code is of high quality. 
2. Good testing will make the debugging process for you so much easier 
    as problems can be quickly narrowed down to particular functions.
3. Good testing reduces the risk of submitting something that still contains errors which you could have easily fixed
    but of which you were not aware.

Rule of Thumb (Mutation Testing): If all your tests are green 
    and you change a random piece of correct and tested code to something that's wrong,
    at least one test should fail.

#### :+1: :+1: No checkstyle errors or compiler warnings
Errors and problems which are detected by checkstyle tools (e.g. PMD, CPD) 
    are likely to be detected by the TA grading you as well - we use a superset of the tools you use.
Additionally, such warnings are often good indicators of bugs and 
    avoiding them will make your debugging life much easier [-> debugging tips](./mini_sections/debugging_starter.md)

#### :+1: :+1: Complete Features requested in assignment
Besides the stuff mentioned above, feature completeness 
    (i.e., the correct implementation of all functionality requested in the assignment)
    should of course not be forgotten. [-> minimal first principle](./mini_sections/minimal_first.md)

#### :+1: Additional Functionality (Top GUI, Easter Eggs, Feature Extensions)
Once all of the above is perfectly completed, you can typically collect additional points
with *nice to have*s such as a beautiful GUI, funny easter eggs or optional features.
Attention: If you add unrequested features, make sure to discuss them with a TA and get the approval 
to deviate from the expected functionality. 

## Common Problems and Countermeasures

#### :hankey: The project is not completed at the time of submission. :bulb: Prioritize features [-> minimal first principle](./mini_sections/minimal_first.md)

#### :hankey: At the time of (milestone or final) submission, the project is in an invalid state :bulb: feature branches  [ -> git advantages](./mini_sections/simple_git.md) 

#### :hankey: One of the teammates does not contribute to the project. :bulb: Talk to the TA or lecturer asap.

#### :hankey: A bug is driving me crazy :bulb: That's life :-) [-> debugging tips](./mini_sections/debugging_starter.md)

#### :hankey: There's a checkstyle / CPD warning I don't agree with. :bulb: -> explain your argument in a comment (*)
 
#### :hankey: There's a feature I cannot implement. :bulb: [-> provide & document a stub](./mini_sections/stubs.md)

#### :hankey: I forgot to save my project. It's all gone. :bulb: git push frequently [-> git advantages](./mini_sections/simple_git.md)

#### :hankey: The pressure is getting too much. :bulb: [-> Start early, minimal first, get help!](./mini_sections/stress.md)

(*) You're probably wrong.

## About this Repo
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)
[![HitCount](http://hits.dwyl.com/{MiWeiss}/{Project-Tips}.svg)](http://hits.dwyl.com/MiWeiss/Project-Tips)

**Author:** Michael Weiss, Software Institute @ Università della Svizzera Italiana (USI), Switzerland
