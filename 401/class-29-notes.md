# Advanced State with Reducers

**What is the motivation for adding a reducer?**
    Reducers help manage state in complex React components by consolidating state update logic into a single function, making it easier to understand and maintain. This centralization enhances code readability and reduces errors.

**What are actions in the context of a reducer? How are they different than setting state directly?**
    In reducers, actions are objects that describe what happened, including a `type` property and any additional information needed for the state update. Unlike directly setting state with `useState`, actions are dispatched to a reducer, which then determines how to update the state.

**What common list operation is useReducer named for, and why?**
    The term `useReducer` is named after the "reduce" list operation, which processes elements of a list to produce a single output. In React, a reducer takes the current state and an action, returning the next state.

**When should you switch from useState to useReducer?**
    Switch to `useReducer` when your component's state logic becomes complex, involving multiple state updates and event handlers. It's particularly useful for managing state transitions that depend on the nature of user interactions.
