# The Call Stack and Debugging

- Call Stack is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions. What function is currently being run and what functions are called from within that function.
- All functions called by that function are added to the call stack further up.
- When current function is finished the interpreter takes it off the stack and resumes execution where it left off on coding.
- If stack takes up more space than it was told to, it will result in a "stack overflow" error message.
- The call stakc function is used mainly for function invocation or call.
- Call stakck is synchronous meaning each function execution is done top to bottom.
- Call Stack is a data structure that uses the last in first out principle to temporariloy store and manage function calls.
- When a function is called, its variable, parameters, and the function are pushed into the call stack to form a stack frame.
- Stack overflow occurs when a function calls itself wthout an exit point.


## Attributions
https://developer.mozilla.org/en-US/docs/Glossary/Call_stack
https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/