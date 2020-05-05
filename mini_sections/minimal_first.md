## The 'minimal features first' principle

The probably most common reason why programming assignments are a failure comes from unrealistic expectations at the start of the assignment.

To make sure you have something to submit as early as possible, I recommend the following procedure:

1. Identify **features**  that your program **has to** support.
    Keep these features as simple as the assignment allows 
    (e.g. when implementing a the *computer player* for a game you have to implement, 
    let it make random moves instead of starting with a sophisticated AI player right away)
2. Choose a software architecture that allows to encode these features and define the interfaces 
    (i.e., declare and document class names and public methods - without actually implementing them yet).
    Use TODO-Comments and Mocking to indicate methods that still have to be implemented. ([-> Stubs](./stubs.md))
3. Pick a **minimalistic happy path**, i.e., the simplest feature from (1) that allows a program execution.
    Use TDD to implement it (=> Write the tests first, than the logic), leave all other method untouched.
    
    Make sure not to forget to document your code [-> Docs & Readme](../README.md#1-1-code-documentation-and-project-readme).
    Your project is now already in a state that could be executed and that will collect partial points,
    even though (by far) not yet all required features are implemented.
4. Iteratively implement more features which you identified in step 2, again using TDD until there are no TODOs left.
5. You're technically done with the project.
    If you want you can now (**and only now - not earlier**) start thinking about bonus points,
    (e.g., replace the random move computer player in our example above with a smart strategic AI player).
    
