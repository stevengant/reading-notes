# Reading02

## React Lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
    [medium.com - What are component lifecycle events?](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

    - Render happens before componentDidMount.

2. What is the very first thing to happen in the lifecycle of React?
    [medium.com - What are component lifecycle events?](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

    - Mounting is the first phase in the component lifecycle.

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
    [medium.com - What are component lifecycle events?](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

    1. constructor
    2. render
    3. React Updates
    4. componentDidMount
    5. componentWillUnmount

4. What does componentDidMount do?
    [reactjs.org - componentDidMount()](https://reactjs.org/docs/react-component.html#componentdidmount)

    - Allows you to load data from a remote endpoint.

## React State vs Props

1. What types of things can you pass in the props?
    [Video: React State vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

    - title, description

2. What is the big difference between props and state?
    - State is handled and updated inside component.
    - Props is handled and updated outside component.

3. When do we re-render our application?
    - when state is changed

4. What are some examples of things that we could store in state?
    - input, checkbox, selection of form
