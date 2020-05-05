
# Efficient and successful programming assignments

## How to get a good grade?
The following things will help you to improve your grades (loosely ordered in dicreasing order of priority).

#### :+1: :+1: :+1: :exclamation: Be fair (no plagiarism, no late submission) 
Do not copy any code from anywhere. 
If you consulted only references (e.g. StackOverflow) to solve a problem, make sure you fully understand and re-write the solution
yourself (instead of copying). Also add appropriate referencing to your solution.

#### :+1: :+1: :+1: Code compiles without errors
If your code does not compile, we cannot run it and won't be able to give you any points for any of the cool stuff you implemented.

#### :+1: :+1: :+1: Happy path functionality
Make sure at least one minimal happy path works. [-> minimal first principle](./mini_sections/minimal_first)

#### :+1: :+1: Code documentation and project readme
Document all exposed methods in your code. 
This does not just make it easier for you to work in a team, but its also easier for the TAs to 
understand what a function is supposed to do - and to give you partial points 
even if the implementation of a method is incorrect or incomplete.

Additionally, a 'README.md' should explain how to use your program, how to run the happy path
and also transparently declare what's not yet implemented. 

#### :+1: :+1: Reasonable software design choices
Sticking to good software design choices makes your debugging easier and your lecturer/TA who has to do the grading 
happier. 
Use abstraction (inheritance) and helper classes to avoid code and documentation duplication.
Avoid god-classes (huge classes with too much logic) and spaghetti code (unstructured code).
You can use various tools (e.g. PMD, CPD) to help you with this. [-> PF2 Design Principles](./pf2_specific/good_practice)

#### :+1: :+1: High test coverage with meaningful tests
Make sure all your code is covered by automated unit tests. 

Your tests should be reasonable: They should check for more than just a happy path, but also treat edge conditions.
Rule of Thumb (Mutation Testing): If all your tests are green and you change a random piece of correct and tested code to something wrong, 
at least one test should fail.

#### :+1: :+1: No checkstyle errors or compiler warnings
Errors and problems which are detected by checkstyle tools (e.g. PMD, CPD) are likely to also be detected by your TA 
and will make you loose points ;-) 
Additionally, such warnings are often good indicators of bugs. 
Avoiding them will make your debugging life much easier [-> debugging tips](./mini_sections/debugging_starter.md)

#### :+1: :+1: Edge-Case functionality for main features


#### :+1: Additional Functionality (Top GUI, Easter Eggs, Feature Extensions)



## Common Problems and Countermeasures

#### :hankey: The project is not completed at the time of submission. :bulb: Prioritize features [-> minimal first principle](./minimal_first)

#### :hankey: At the time of (milestone or final) submission, the project is in an invalid state :bulb: feature branches  [ -> mini git tutorial](./mini_sections/simple_git.md) 

#### :hankey: One of the teammates does not contribute to the project. :bulb: Talk to the TA or lecturer asap.

#### :hankey: There's a bug that is driving me crazy :bulb: That's life :-) [-> debugging tips](./mini_sections/debugging_starter.md)

#### :hankey: There's a checkstyle error / code duplication I cannot fix. :bulb: [-> explain in a comment](./mini_sections/explanantion_comments.md)
 
#### :hankey: There's a feature I cannot implement. :bulb: [-> mock functionality](./mini_sections/mocking.md)

#### :hankey: I forgot to save my project. It's all gone. :bulb: git push frequently [-> mini git tutorial](./mini_sections/simple_git.md)

#### :hankey: The pressure is getting too much. :bulb: [-> Start early, minimal first, get help!](./mini_sections/stress.md)




## About this Repo
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)
<!-- TODO RE-ENABLE
[![HitCount](http://hits.dwyl.com/{MiWeiss}/{Project-Tips}.svg)](http://hits.dwyl.com/MiWeiss/Project-Tips)
-->

**Author:** Michael Weiss, Software Institute @ Università della Svizzera Italiana (USI), Switzerland [ -> web](https://mweiss.ch)


