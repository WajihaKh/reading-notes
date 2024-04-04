# In Memory Storage

__What is a ‘call’?__

A 'call' is when a program runs a function. It pauses its current task, does the functio's job, and then goes back to what it was doing.

__How many ‘calls’ can happen at once?__

Only one call can happen at a time in JS.

__What does LIFO mean?__

LIFO: Last In, First Out.

__Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.__

Call stack:

thirdFunction() <-- Top of the stack
secondFunction()
firstFunction()
main()

__What causes a Stack Overflow?__

A Stack Overflow happens when there are too many functions calls piled up.

__What is a ‘reference error’?__

A reference error is when we try to use a variable that hasn't been declared yet.

__What is a ‘syntax error’?__

A syntax error is a grammar mistake in code.

__What is a ‘range error’?__

A range error is when we try to do something with an object that's not allowed, like giving it an invalid length.

__What is a ‘type error’?__

A type error is when we try to use a value in a way that doesn't match its type like trying to access a property on an undefined variable.

__What is a breakpoint?__

A breakpoint is a point in our code where we want to pause and take a closer look at what's happening

__What does the word ‘debugger’ do in your code?__

Debugger is a command that tells the program to stop executing at a certain point so we can check what's going on.
