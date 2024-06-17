# Application State with Redux

The first principle of Redux is that the entire state of your application is represented by a single JavaScript object.

**What is a store and what do we use our reducers for within that store?**

A **store** in Redux is a centralized place where the state of your application lives. **Reducers** are functions that specify how the state changes in response to actions sent to the store.

**Name three Redux store methods given to us by createStore and describe their use.**

1. **getState()**: Returns the current state of the application.
2. **dispatch(action)**: Sends an action to the store to update the state.
3. **subscribe(listener)**: Adds a listener that runs whenever an action is dispatched.

**Explain to a non-technical recruiter what combineReducers() does and why it is useful.**

**combineReducers()** is a utility that combines multiple reducer functions into a single reducer, allowing different parts of the state to be managed separately but cohesively. This makes the code more modular and maintainable.
