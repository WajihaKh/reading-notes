# State and Props

__Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?__

The render happens before the componentDidMount.

__What is the very first thing to happen in the lifecycle of React?__

The very first thing to happen in the lifecycle of React is the creation of the component instance. (Inital state + props)

__Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates.__

1. constructor
2. render
3. componentDidMount
4. React Updates
5. ComponentWillUnmount

__What does componentDidMount do?__

componentDidMount loads anything using a network request or initialize the DOM.
[React: Component Lifecycle Events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

__What types of things can you pass in the props?__

- string, numbers, booleans
- objects + arrays
- functions

__What is the big difference between props and state?__

The big difference between props and state is:

- props: pass into a component
handled outside the component
- state: handled inside of that component

__When do we re-render our application?__

To re-render our application is when user has done something.

__What are some examples of things that we could store in state?__

- users input
