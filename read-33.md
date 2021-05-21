# Redux - Additional Topics

## 1 -What's the best practice for "pre-loading" data into the store (on application start) in a Redux application?

*The best practice is to wrap the opening preloaded in useEffect. With this, you need to take the function outside of the props that you passed into the component.*

---

## 2 - When using a thunk/async action that dispatches the actual action, which do you export from your reducer?

*You will still be exporting the new data to replace the state from the reducer. The action calling the reducer will be sent as a function rather than an object.*

---

## Important Terms


Word | Definition 
------------ | -------------
middleware |  In Redux, middleware provides a third-party extension point between the when an action is dispatched and the moment it reaches the reducer. It needs to be used for asynchronous calls with Redux. 
thunk | Thunk is a redux middleware that allows you to do async functions in conjunction with Redux.

---

## Redux Toolkit

**What is Redux Toolkit?**

*is our official, opinionated, batteries-included toolset for efficient Redux development.*


**`Redux Toolkit` was originally created to help address three common concerns about Redux**:

- "Configuring a Redux store is too complicated"
- "I have to add a lot of packages to get Redux to do anything useful"
- "Redux requires too much boilerplate code"

**Why You Should Use Redux Toolkit**

*Redux Toolkit makes it easier to write good Redux applications and speeds up development, by baking in our recommended best practices, providing good default behaviors, catching mistakes, and allowing you to write simpler code.*

**What's Included**

*Redux Toolkit includes:*

- A `configureStore()` function with simplified configuration options. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes `redux-thunk` by default, and enables use of the Redux DevTools Extension.
- A `createReducer()` utility that lets you supply a lookup table of action types to case reducer functions, rather than writing switch statements. 
- A `createAction() `utility that returns an action creator function for the given action type string. The function itself has toString() defined, so that it can be used in place of the type constant.
- A `createSlice()` function that accepts a set of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.

- The `createSelector` utility from the Reselect library, re-exported for ease of use.


---

# `T` `H` `E` `E` `N` `D`
