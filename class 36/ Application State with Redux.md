##  Application State with Redux

**What is the first principle of Redux?**

The first principle of Redux is often referred to as "Single Source of Truth." It means that the entire state of your application is stored in a single JavaScript object, which is often called the "store."

**what is a store and what do we use our reducers for within that store?**

In Redux, a "store" is a central repository that holds the entire state tree of your application. It is a JavaScript object that contains the current state of your application's data. The store serves as the single source of truth for your application's state, which means that all the data needed to render your user interface is stored in this one place.

**Name three Redux store methods given to us by createStore and describe their use.**

1-getState():
Use: The getState() method is used to retrieve the current state of the Redux store.
Description: It returns the current state object, which represents the entire state tree of your application.

2-dispatch(action):
Use: The dispatch(action) method is used to dispatch actions to the Redux store, which triggers the state updates through the reducers.
Description: When you want to change the state in your Redux store, you create an action and dispatch it using this method.

3-subscribe(listener):
Use: The subscribe(listener) method is used to add a listener function that will be called whenever the state in the Redux store changes.
Description: When you subscribe a listener, it will be invoked every time an action is dispatched and the state is updated.

**Explain to a non-technical recruiter what combineReducers() does and why it is useful.**

In a non-technical way, combineReducers() is a function in Redux that helps organize and manage the different pieces of your application's state. It's like a puzzle organizer that arranges your state into categories or slices, making it easier to work with and understand.