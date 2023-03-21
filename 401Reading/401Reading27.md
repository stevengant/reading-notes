# Reading Class 27

## [Thinking in React](https://react.dev/learn/thinking-in-react)

1. Summarize the five steps of thinking in react.

    - **Step 1**: Break the UI into a component hierarchy; start by drawing boxes around each component and subcomponent and naming them in a mockup.

    - **Step 2**: Build a static version in React; the most straightforward approach is to build a version that renders the UI from your data model without adding any interactivity.

    - **Step 3**: Find the minimal but complete representation of UI state; to make the UI interactive, you need to let users change your underlying data model. You will use state for this.

    - **Step 4**: Identify where your state should live; you need to identify which component is responsible for changing this state, or owns the state.

    - **Step 5**: Add inverse data flow; to change the state according to user input, you will need to support data flowing the other way: the form components deep in the hierarchy need to update the state.

## [State: A Component's Memory](https://react.dev/learn/state-a-components-memory)

1. What is one reason a local variable isn’t sufficient for managing a React component?
    - Local variables don't persist between renders
    - Local changes won't trigger renders 

2. What is the argument to the useState hook, and what are the two parts of its return array?
    - state variable
    - state setter

3. How can Component A access state from Component B?
    - Remove state from components A and B and move to nearest shared parent component