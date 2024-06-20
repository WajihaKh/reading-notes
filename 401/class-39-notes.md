# Redux - Additional Topics

1. **What concerns are addressed by Redux Toolkit?**
   Redux Toolkit addresses concerns like boilerplate reduction, simplified store setup, and improved developer experience when working with Redux in React applications.

2. **What does `configureStore()` do?**
   `configureStore()` in Redux Toolkit combines several Redux-related setup steps into a single function call, including creating the Redux store with middleware and enhancers configured.

3. **How would I use `createSlice()`?**
   You would use `createSlice()` in Redux Toolkit to define a slice of your Redux state, including reducer functions and action creators, in a concise manner using a "slice" of state and automatically generated action types.

4. **What is Mobx?**
   MobX is a state management library for JavaScript applications that allows for transparent reactive programming.

5. **How does MobX make it “impossible” to produce an inconsistent state?**
   MobX ensures state consistency by tracking dependencies between observables (state variables) and automatically updating any part of the application that depends on them when they change.

6. **How would we build a reactive user interface?**
   To build a reactive user interface with MobX, you would define observables for your state, use them in your components to automatically track changes, and let MobX update the UI whenever those observables change.

7. **What take-away(s) did this tutorial provide**
    Only god knows.
    