# Passing Functions as Props

__What does .map() return?__

.map() returns a new array where a new array where each element is the result of applying a function to every element of the original array.

__If I want to loop through an array and display each value in JSX, how do I do that in React?__

In order to loop through an array and display each value in jsx, we would use the .map() function in React and that would return the jsx element inside the curly braces.

__Each list item needs a unique [blank].__

key

__What is the purpose of a key?__

The key in React is like a special label for each item in a lsit. It keeps tract of which item is which.

__What is the spread operator?__

The spread operator is used to expand element of an array or object into individual elements.

__List 4 things that the spread operator can do.__

- Concatenate arrays
- Copy arrays or objects
- Pass arguments
- Spead object properties

__Give an example of using the spread operator to combine two arrays.__

const arr1 = [1,2,3];
const arr2 = [4,5,6];

const combinedArray = [...arr1, ...arr2];

__Give an example of using the spread operator to add a new item to an array.__

const ogArray = [1,2,3];
const newArray = 4;

const newArray = [...ogArray, newItem];

__Give an example of using the spread operator to combine two objects into one.__

const obj1 = { name: 'April', age: 20};
const obj2 = { gender: 'Female', location: 'New York'};

const combinedObj = {...obj1, ...obj2};

__In the video, what is the first step that the developer does to pass functions between components?__

The first step that the developer does to pass functions between components is passing functions by props.

__In your own words, what does the handleClick function do?__

The handleClick function allows you to pass components from the parent function to the child because it's a prop.

__How can you pass a method from a parent component into a child component?__

using props

__How does the child component invoke a method that was passed to it from a parent component?__

In order for the child component to invoke a method to the parent, we would use callback.
