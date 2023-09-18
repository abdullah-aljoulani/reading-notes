## Asynchronous Actions

### async actions

**Why use Redux middleware?**
1- To handle asynchronous actions. Middleware allows you to intercept actions before and after they reach the reducer.
2- For logging and debugging
3- To extend Redux functionality

**Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.**

The flow begins with a user taking an action like clicking a button. This triggers an action creator function which returns a plain JavaScript object called an action.The action is passed to the store's dispatch method. Dispatch sends the action to each middleware that has been added to the store's middleware chain.

**How are we accommodating async in our Redux app?**

1- Use Redux Thunk middleware: Thunk middleware allows action creators to return functions instead of plain objects
2- Use Redux Saga middleware: Sagas are generator functions that handle asynchronous side effects.
3- Use Redux Observable middleware:
Observables allow dispatching streams of actions over time.

### thunk middleware

**Why would you need redux-thunk middleware?**

1- To dispatch asynchronous actions. Thunk middleware allows action creators to return functions instead of plain objects.
2- To dispatch multiple actions. Thunk actions can dispatch multiple actions sequentially or conditionally based on previous actions or API responses.
3- To access getState(). Thunk actions receive the store's dispatch and getState methods.

**Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.**

Redux Thunk middleware allows you to write action creators that return a function instead of an action.

**Describe how any return value from the inner thunk function will be made available.**

When an action creator returns a function (a thunk) instead of a plain action object, the thunk function is passed the dispatch and getState functions as arguments.Any return value from the inner thunk function will be ignored by Redux Thunk middleware. The return value is not passed back to the component or used further in the Redux flow.
