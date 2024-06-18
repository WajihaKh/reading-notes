# Redux - Combined Reducers

**Why create multiple reducers?**
Multiple reducers allow you to manage different parts of your application's state independently, making code more organized and maintainable.

**How would you combine multiple reducers?**
You combine multiple reducers into a single reducer using `combineReducers` provided by Redux.

**How will you manage state as an immutable object? why?**
Managing state immutably ensures that state changes are predictable and traceable, which helps prevent bugs and makes debugging easier.

**combineReducers is a utility function to simplify the most common use case when writing ___ _____ .**
`combineReducers` simplifies the process of creating a root reducer that delegates handling of actions to multiple reducers, each managing a slice of the application state.

**Explain how combineReducers assembles the new state tree.**
`combineReducers` combines the states returned by each reducer into a single state object. Each reducer manages a slice of the state, and `combineReducers` merges these slices into the final state tree.

**How would you define initial state in an app using combineReducers?**
You define initial state for each slice of the state tree in the individual reducers. `combineReducers` then combines these initial states into the initial state of the entire application.

**Why will you want to split your reducing functions as your app becomes more complex?**
Splitting reducers allows you to handle specific parts of state management separately, which improves code organization and scalability as your application grows.

**The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.**
The `combineReducers` helper function turns an object whose values are individual reducing functions into a single reducing function you can pass to `createStore`.

**What is a popular convention when naming reducers?**
A popular convention is to name reducers based on the slice of state they manage, such as `todosReducer` for managing todo items or `userReducer` for managing user-related state.
