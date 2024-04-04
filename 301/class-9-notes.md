# Functional Programming

__What is functional programming?__

Style of programming where we can use functions as the primary building blocks of your programs, focusing on avoiding changing date and state.

__What is a pure function and how do we know if something is a pure function?__

A pure function is a function that always give the same output for the same input and doesn't modify anything outside its scope.

__What are the benefits of a pure function?__

- Easier to understand
- Easier to test
- Easier to work with

They do not have side effects and produce the same result everytime.

__What is immutability?__

Immuntability: Once data is created, it cannot be changed. Instead, we create new data when we need to make changes.

__What is Referential transparency?__

Raferentisl transparency means you can replace a function call with its result without changing the program's behaviour, as longas the function has no side effects.

__What is a module?__

Module is another JS file.

__What does the word ‘require’ do?__

'require' is a keyword in JS, used to import modules/files.

__How do we bring another module into the file the we are working in?__

To bring another module into the file into the one we are working in by using 'require' or 'import'

__What do we have to do to make a module available?__

In order to make a module available, we need to export it from its file using 'module.exports'
