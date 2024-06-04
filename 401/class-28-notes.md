# Component Lifecycle / useEffect Hook

**1. What is the main intended use case for the `useEffect` hook?**
- The main intended use case for the `useEffect` hook is to handle side effects, such as data fetching, subscriptions, or manually changing the DOM in a React component.

**2. How does the effect’s logic interact with the component?**
- The effect’s logic runs after the component renders, and it re-runs whenever the specified dependencies change, ensuring the component stays in sync with external systems or data.

**3. What is the importance of the return value from the effect’s logic function?**
- The return value from the effect’s logic function is used for cleanup purposes, ensuring that any setup done by the effect is properly undone when the component unmounts or before the effect runs again.
