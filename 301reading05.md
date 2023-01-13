# Reading05

## React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?
    [Reactjs - Step 1: Break The UI Into A Component Hierarchy](https://reactjs.org/docs/thinking-in-react.html)
    - A component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

2. What does it mean to build a ‘static’ version of your application?
    [Reactjs - Step 2: Build A Static Version in React](https://reactjs.org/docs/thinking-in-react.html)
    Means to build a version of your app with no interactivity - does not use state

3. Once you have a static application, what do you need to add?
    - Add state

4. What are the three questions you can ask to determine if something is state?
    [Reactjs - Step 3: Identify The Minimal (but complete) Representation Of UI State](https://reactjs.org/docs/thinking-in-react.html)
    1. Is it passed in from a parent via props? If so, it probably isn’t state.
    2. Does it remain unchanged over time? If so, it probably isn’t state.
    3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. How can you identify where state needs to live?
    [Reactjs - Step 4: Identify Where Your State Should Live](https://reactjs.org/docs/thinking-in-react.html)
    - For each piece of state in your application:

      - Identify every component that renders something based on that state.
      - Find a common owner component (a single component above all the components that need the state in the hierarchy).
      - Either the common owner or another component higher up in the hierarchy should own the state.
      - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## Higher-Order Functions

1. What is a “higher-order function”?
    [eloquentjavascript - Higher-order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)
    - Functions that operate on other functions, either by taking them as arguments or by returning them

2. Explore the greaterThan function as defined in the reading. 
    - It looks like greaterThan may be used similar to filter function

3. In your own words, what is line 2 of this function doing?
    - Returns m where m is greater than n

4. Explain how either map or reduce operates, with regards to higher-order functions.
    - The map method transforms an array by applying a function to all of its elements and building a new array from the returned values