# Context API

1. **Summarize the five principles for structuring state:**
   - The five principles are **Single Source of Truth**, **State is Read-Only**, **Changes are made with Pure Functions**, **Predictable State Changes with Reducers**, and **Centralization of State Logic**.

2. **What problem do Contexts aim to solve?**
   - Contexts aim to solve the problem of prop drilling, where data needs to be passed through multiple components without being used directly by the intermediary components.

3. **What is one technique to try before useContext?**
   - One technique to try before useContext is **prop drilling**, where data is passed down the component tree through props, even if some intermediary components don't use it.

4. **What hook complements useContext for complex applications?**
   - **useReducer** complements useContext for complex applications, as it allows for more granular control over state updates and management within a context.
