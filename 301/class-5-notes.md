# Putting it all together

__What is the single responsibility principle and how does it apply to components?__

The Single Responsibility Principle is a rule in software design that says each piece of code should do just one thing. A component should have a clear, single purpose/responsibility.

__What does it mean to build a ‘static’ version of your application?__

To build a 'static' version of an application means making a simplified version where data is fixed, runs only in the browser and has no dynamic features.

__Once you have a static application, what do you need to add?__

- Add a dynamic feature
- Connect to a database
- Implement user authentication
- Establish client-server coms
- Update content dynamically
- integrate external services

__What are the three questions you can ask to determine if something is state?__

- Does it change over time?
- Is it necessary for the application's behaviour?
- Is it shared or needed by multiple components?

__How can you identify where state needs to live?__

- Figure out which part of the app needs to remember things like users input / fetched data
- Decide if it's just for one small part or if many part need to share it
- If it's just one part, keep it local. If its many, keep it where they all can access it
- Make sure it's only used for what your app needs to do, like showing data or reacting to clicks
- Put state where it can quickly react to what users do, like clicking buttons/ tyoing

__What is a “higher-order function”?__

A higher order function is like a function that either uses other functions or creates new functions

__Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?__

In line 2 of the greaterThan function, we are creating a new function. This new function checks if the number it receives ('m') is greater than the number 'n'. If m is greater than n, the new function returns true, otherwise it returns false.

__Explain how either map or reduce operates, with regards to higher-order functions.__

The map operator is like a tool for transforming each item in an array. The reduce operator is like a tool for combining all the items in the arrow into a single value. Both functions make working with array easier by letting you describe what you want to do with the item.
