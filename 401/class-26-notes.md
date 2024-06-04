# Component Based UI

**What are the building blocks of a React app?**
The building blocks of a React app are components. Components can be thought of as custom, reusable HTML elements that React uses to build the user interface. Each component can contain its own state and logic, making it easier to manage and maintain the application's structure.

**What is the difference between an HTML element and a React component?**
An HTML element is a basic building block of a web page, representing a part of the document's structure, like a paragraph or a button. A React component, on the other hand, is a more complex and reusable piece of the user interface. React components can contain both HTML and JavaScript logic, allowing them to manage their own state and behavior.

**What is JSX and why do we use it?**
JSX stands for JavaScript XML. It is a syntax extension for JavaScript that allows developers to write HTML-like code within JavaScript files. We use JSX because it makes it easier to visualize the structure of the UI and to write code that is both maintainable and understandable. It also allows us to embed JavaScript expressions directly within our HTML-like code.

**Describe the process of embedding JavaScript expressions in JSX.**
In JSX, JavaScript expressions can be embedded by enclosing them in curly braces `{}`. This allows you to include dynamic content and logic directly within your JSX code. For example, you can embed variables, function calls, and any valid JavaScript expression inside the curly braces.

**Does React or JSX have any special features for iteration or conditional logic?**
Yes, React and JSX support iteration and conditional logic. For iteration, you can use JavaScript's array methods like `map()` to loop through data and render components for each item. For conditional logic, you can use JavaScript conditional operators like `if`, `else`, and the ternary operator within the curly braces in JSX.

**How does React know to respond to a user’s inputs?**
React responds to user inputs through event handlers. Event handlers are functions that you define to handle specific events like clicks, form submissions, and keyboard inputs. These handlers are typically passed to React components as props and are triggered when the specified event occurs.

**What word indicates that a React component manages data with a Hook?**
The word "use" typically indicates that a React component is managing data with a Hook. For example, `useState` and `useEffect` are common hooks used to manage state and side effects in functional components.

**How can two React components share data?**
Two React components can share data by lifting state up to a common ancestor component. This means moving the shared state to the nearest common parent component and passing it down to the child components as props. This way, the parent component manages the state and the child components receive the state as props and can also pass data back to the parent via callback functions.

**What are the three steps of refreshing a React UI?
The three steps of refreshing a React UI are:
1. **State Update:** The state of a component is updated.****
2. **Re-render:** React re-renders the component to reflect the new state.
3. **DOM Update:** React updates the actual DOM to match the new virtual DOM representation.

**How do you trigger updates to a component after the initial render?**
Updates to a component after the initial render can be triggered by changing the component's state or props. In a functional component, this is typically done using the `useState` hook to update the state or by passing new props to the component.

**Does React recreate DOM nodes on every rerender?**
No, React does not recreate all DOM nodes on every rerender. Instead, React uses a virtual DOM to keep track of changes. When a component re-renders, React compares the new virtual DOM with the previous version and only updates the parts of the actual DOM that have changed, making the update process more efficient.

**After React has updated the DOM, what still needs to happen before the user sees the change?**
After React has updated the DOM, the browser still needs to repaint the screen. This involves rendering the updated DOM elements and displaying them to the user. This process is handled by the browser's rendering engine.

**Naming Conventions in the Airbnb React/JSX Style Guide**
1. **PascalCase for Component Names and Filenames**:
   - React components and their filenames should use PascalCase (e.g., `ReservationCard.jsx`, `MyComponent`).

2. **camelCase for Props and Instance Variables**:
   - Props and instance variables should use camelCase (e.g., `userName`, `phoneNumber`).

3. **Filename Matches Component Name**:
   - The filename of a component should match the component name (e.g., `ReservationCard.jsx` should contain a component named `ReservationCard`).

4. **Index Files for Root Components**:
   - Use `index.jsx` for the root component of a directory and name the component after the directory (e.g., `Footer/index.jsx` should export a component named `Footer`).

5. **Higher-Order Component Naming**:
   - Higher-order components should use a composite name combining the higher-order component’s name and the passed-in component’s name (e.g., `withFoo(Bar)`).

6. **Avoid DOM Component Prop Names for Different Purposes**:
   - Avoid using common DOM prop names like `style` and `className` for different purposes to prevent confusion.

