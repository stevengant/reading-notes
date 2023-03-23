# Class 29 Reading

## Extracting State Logic into a Reducer

[React - Extracting State Logic into a Reducer](https://react.dev/learn/extracting-state-logic-into-a-reducer)

1. What is the motivation for adding a reducer?
    - When components have many state updates spread across many event handlers.

2. What are actions in the context of a reducer? How are they different than setting state directly?
    - State setting logic is removed and instead of telling React what to do by setting state, you specifiy what the user just did by dispatching actions from event handlers. 

3. What common list operation is useReduce named for, and why?
    - The `reduce()` function allows you return a single value from an array

4. When should you switch from useState to useReducer?
    - Debugging: When you have a bug with `useState`, it can be difficult to tell where the state was set incorrectly, and why.
    - Testing: A reducer is a pure function that doesn’t depend on your component. This means that you can export and test it separately in isolation.