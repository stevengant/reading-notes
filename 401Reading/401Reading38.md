# Class 38 Reading

## Redux Toolkit (RTK)

[Getting Started with Redux Toolkit](https://redux-toolkit.js.org/introduction/getting-started)
1. What concerns are addressed by Redux Toolkit?
  - "Configuring a Redux store is too complicated"
  - "I have to add a lot of packages to get Redux to do anything useful"
  - "Redux requires too much boilerplate code"

2. What does `configureStore()` do?
  - Wraps `createStore` to provide simplified configuration options and defaults. It can automatically combine slice reducers and adds Redux middleware. Also includes `redux-thunk` and enables the use of Redux DevTools Extension.

3. How would I use `createSlice()`?
  - accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.

## MobX

[Ten minute introduction to MobX and React](https://mobx.js.org/getting-started.html)
1. What is Mobx?
  - `MobX` is a simple, scalable and battle tested state management solution

2. How does MobX make it “impossible” to produce an inconsistent state?
  - By making sure that everything that can be derived from application state will be derived automatically.

3. How would we build a reactive user interface?
  - The `observer` HoC wrapper from the `mobx-react-lite` package fixes that by basically wrapping the React component in autorun. This keeps the component in sync with the state.

## Tutorial

[Redux Toolkit tutorial](https://redux-toolkit.js.org/tutorials/overview)
1. What take-away(s) did this tutorial provide?
  - `RTK Query` is a powerful data fetching and caching tool. It is designed to simplify common cases for loading data in a web application, eliminating the need to hand-write data fetching & caching logic yourself.
  