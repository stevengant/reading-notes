# Reading Class 37

## Multiple Reducers Example

[Multiple Reducers with Redux Reducers](https://www.youtube.com/watch?v=gBER4Or86hE)
1. Why create multiple reducers?
  - Creating multiple reducers in Redux provides several benefits:
    - Modularity and Scalability
    - Performance optimization
    - Code reusability
    

2. How would you combine multiple reducers?
  - By using `combineReducers`

3. How will you manage state as an immutable object? why?
  - In Redux, it is recommended to manage state as an immutable object. Because of this, you should create a new copy of state. Doing so offers the following benefits:
    - Predictability
    - Performance optimization
    - Undo/Redo functionality
    - Debugging

## Redux Docs: Using Combined Reducers

[Using `combineReducers`](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)
1. `combineReducers` is a utility function to simplify the most common use case when writing ___ _____ .
  - Redux reducers

2. Explain how `combineReducers` assembles the new state tree.
  - In order to assemble the new state tree, `combineReducers` will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed. So, in that sense, using `combineReducers` does "call all reducers", or at least all of the slice reducers it is wrapping.

3. How would you define initial state in an app using `combineReducers`?
  -  We can define the initial state for each reducer by passing it as the second argument to the corresponding reducer function. The initial state should be an object that represents the default values for each slice of the state tree.

## Redux Docs: Combined Reducer Syntax

[`combineReducers(reducers)](https://redux.js.org/api/combinereducers/)
1. Why will you want to split your reducing functions as your app becomes more complex?
  - As your app becomes more complex, so does managing its state. Splitting up reducing functions into smaller, specialized/focused reducers allows fom much simpler management

2. The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.
  - `combineReducers`
  - `createStore`

3. What is a popular convention when naming reducers?
  - Name reducers after the state slices they manage, so you can use ES6 property shorthand notation