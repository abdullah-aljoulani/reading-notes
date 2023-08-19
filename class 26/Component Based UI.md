## Component Based UI

**What are the building blocks of a React app?**

1-Components , 2-JSX , 3-Hooks , 4-Reconciliation

**What is the difference between an HTML element and a React component?**

An HTML element represents a specific piece of the web page structure.
A React component is a reusable piece of UI logic that can encapsulate one or more HTML elements along with their behavior and state.

**What is JSX and why do we use it?**

JSX stands for JavaScript XML. It's a syntax extension for JavaScript that allows you to write HTML-like code within your JavaScript files. JSX makes it easier to describe the structure of UI components, and it's then transformed into plain JavaScript by tools like Babel.

**Describe the process of embedding JavaScript expressions in JSX.**

Curly Braces: JavaScript expressions are enclosed in curly braces {} within JSX.

Inserting Expressions: You can insert any valid JavaScript expression inside the curly braces.

Dynamic Content: The evaluated result of the JavaScript expression will be inserted into the JSX where the curly braces are located.

**Does React or JSX have any special features for iteration or conditional logic?**

React provides special syntax to handle iteration and conditional logic within JSX. For iteration, you can use the map() function to generate a list of elements based on an array.

**How does React know to respond to a user’s inputs?**

React responds to user inputs through event handlers. Event handlers are functions that you define within your components to respond to events like clicks, key presses, etc.

**What word indicates that a React component manages data with a Hook?**

The term that indicates a React component manages data with a hook is the word "Hook" itself. React Hooks are special functions that allow functional components to manage state and side effects.

**How can two react components share data?**

1- Props: You can pass data from a parent component to a child component using props.
2- Context API: React's Context API allows you to create a global state that can be accessed by any component.
3- Redux : For larger applications, state management libraries like Redux can be used to maintain a centralized store that can be accessed by any component.

### Render and Commit

**What are the three steps of refreshing a React UI?**

Render: The component re-renders based on changes in its state or props.

Reconciliation: React's reconciliation algorithm compares the previous virtual DOM with the new one to determine the minimal set of changes needed to update the actual DOM.

Commit: The identified changes are applied to the actual DOM. This step is known as the "commit" phase.

**How do you trigger updates to a component after the initial render?**

1- State Changes 2- Props Changes 3- Context Changes 4- Force Update

**Does React recreate DOM nodes on every rerender?**

No, React does not recreate all DOM nodes on every re-render.

**After React has updated the DOM, what still needs to happen before the user sees the change?**

Even after React has updated the DOM, the browser might not immediately reflect these changes to the user. This is because the browser has its own rendering pipeline, which includes additional steps such as layout and painting.
