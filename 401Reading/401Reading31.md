# Class 31 - Reading

## Context API

### Choosing the State Structure

[REact - Choosing the State Structure](https://react.dev/learn/choosing-the-state-structure)
1. Summarize the five principles for structuring state.
    1.  Group related state: use if you are always updating two or more state variables at the same time
    2.  Avoid contradictions in state: don't structure state in a way that multiple pieces may contradict eachother
    3.  Avoid redundant state: if you are able to calculate information from props or existing state, don't put that information into the component's state
    4.  Avoid duplication in state: when data is duplicated between multiple state variables, or within nested objects, it is difficult to keep in sync
    5.  Avoid deeply nested state: it is difficult to update deeply nested state

### Passing State Deeply with Context

[React - Passing Data Deeply with Context](https://react.dev/learn/passing-data-deeply-with-context)
1. What problem do Contexts aim to solve?
    - Context lets the parent component make some information available to any component in the tree below it—no matter how deep—without passing it explicitly through props.

2. What is one technique to try before useContext?
    - Pass props

3. What hook complements useContext for complex applications?
    - Reducer