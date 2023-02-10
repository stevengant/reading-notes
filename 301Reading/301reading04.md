# Reading 04

## React Docs - Forms

1. What is a ‘Controlled Component’?
    [Reactjs - Controlled Components](https://reactjs.org/docs/forms.html)

    - A React component that renders a form and controls what happens based on user input.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

  - State updates with user responses - state updates with every keystroke.

3. How do we target what the user is entering if we have an event handler on an input field?
    [Medium - Recommended Way of Working with Forms in React](https://medium.com/capital-one-tech/how-to-work-with-forms-inputs-and-events-in-react-c337171b923b)

    - Developers need to implement an event handler to capture changes with onChange.


## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?
    [codeburst - Starting With the Basics — The if statement](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

    - Easier to read and more effiecient.

2. Rewrite the following statement using a ternary statement:

if(x===y){
  console.log(true);
} else {
  console.log(false);
}

x===y = (true ? 'True' : 'False';)