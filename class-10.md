# Debugging

**Order of Execution** - Before understanding how to debug you must first understand the order of which statements are processed or the order of execution. 

### Execution Context
The JavaScript interpreter uses the concept of execution contexts. Every statement in a script lives in one of three execution contexts:
1. Global Context 
    - Code that is in the script, but not in a function. There is only one global context in any page.
2. Function Context
    - Code that is being run within a function. Each function has its own function context.
3. Eval Context 
    - Text is executed like code in an internal function called eval() 

### The Stack
The JavaScipt interpreter processes one line of code at a time. When a statement needs data from another function, it stacks(or piles) the new function on top of the current task.

## How to Debug
Debugging is about deduction: eliminating potential casues of an error. Try asking yourself the questions below.
- Where is the problem?
    - First, should try to narrow down the area where the problem seems to be. Look at the error message, it tels you : Relevant scrip that caused problem, the line number, and the type of error.
- What exactly is the problem?
    - Once you know where the area is you can try and find the actual line. 
        - Break down the code to test smaller pieces of the functionality. Looks at the variables and make sure they have the values you would expect them to have.

**JavaScript Console** - Will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be. The JavaScript console is just one of several developer tools that are found in all modern browsers.

If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.

