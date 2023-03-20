# Reading Class 26

## React Quick Start

### Read the React Quick Start quide, to refresh your memory on React.

1. What are the building blocks of a React app?
    [React Quick Start](https://react.dev/learn)
    - React apps are made out of components

2. What is the difference between an HTML element and a React component?
    - React components start with a capital letter

3. What is JSX and why do we use it?
    - JSX allows us to use markup similar to HTML, but more strict. 

4. Describe the process of embedding JavaScript expressions in JSX.
    - By enclosing the variable in curly braces {}.

5. Does React or JSX have any special features for iteration or conditional logic?
    - No, loops and if statements can be used just like in JavaScript.

6. How does React know to respond to a user’s inputs?
    - By using an event handler inside components

7. What word indicates that a React component manages data with a Hook?
    - Functions starting with use are called hooks

8. How can two react components share data?
    - In order to make both components update together, you need to move the state from each upwards to the closest component containing both

## Render and Commit

1. What are the three steps of refreshing a React UI?
    [React Render and Commit](https://react.dev/learn/render-and-commit)
    1. Triggering a render (delivering the guest’s order to the kitchen)
    2. Rendering the component (preparing the order in the kitchen)
    3. Committing to the DOM (placing the order on the table)

2. How do you trigger updates to a component after the initial render?
    - You can update the state with the <set> function

3. Does React recreate DOM nodes on every rerender?
    - During the initial render, React will create the DOM nodes for <section>, <h1>, and three <img> tags.
    - During a re-render, React will calculate which of their properties, if any, have changed since the previous render. It won’t do anything with that information until the next step, the commit phase.

4. After React has updated the DOM, what still needs to happen before the user sees the change?
    - After rendering is done and React updated the DOM, the browser will repaint the screen.