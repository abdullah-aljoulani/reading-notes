## Additional Topics

### Redux Toolkit (RTK)

**What concerns are addressed by Redux Toolkit?**

Redux Toolkit is a library that simplifies and streamlines the use of Redux.

Redux Toolkit addresses several concerns related to using Redux efficiently and effectively

1-boilerplate Reduction.
2- Improved Performance.
3- Immutable Updates.

**What does configureStore() do?**

configureStore() is a function provided by Redux Toolkit

1-Reducer Configuration: It allows you to pass in one or more reducer functions to specify how your application's state should be updated in response to dispatched actions
2- Enhanced Error Handling: configureStore() sets up some enhanced error handling and warnings for common Redux mistakes.

**How would I use createSlice()?**

1- Import Dependencies.
2- Define Initial State.
3- Create a Slice: Use createSlice() to create a Redux slice.
4- Export Reducers and Actions
5- Use in Redux Store Configuration
6- Use Action Creators

### MobX

**What is Mobx?**

MobX is a state management library for JavaScript and TypeScript applications. It is commonly used in front-end development, particularly in the context of web and mobile applications built with frameworks like React, Angular, and Vue.js.

**How does MobX make it “impossible” to produce an inconsistent state?**

1- Observables: MobX introduces the concept of "observables," which are objects or data structures that can be automatically tracked for changes.
2- Actions: In MobX, changes to observables must be made within "actions."
3- Automatic Dependency Tracking: MobX automatically tracks the dependencies between observables and reactions.

**How would we build a reactive user interface?**

Building a reactive user interface with MobX typically involves creating React components that automatically re-render when relevant data changes. MobX provides the observer higher-order component (HoC) from the mobx-react or mobx-react-lite package to make your React components reactive.

### Tutorial

**What take-away(s) did this tutorial provide?**

* Redux Toolkit Quick Starts:
Quick Start Tutorial: Offers a quick introduction to adding and using Redux Toolkit in a React application.

* Using Redux Toolkit:
RTK Usage Guide: Explains standard usage patterns for each of Redux Toolkit's APIs
