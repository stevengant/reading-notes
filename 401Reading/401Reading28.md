# Reading Class 28

## useEffect hook

[React - Reference useEffect](https://react.dev/reference/react/useEffect#reference)
1. What is the main intended use case for the useEffect hook?
    - lets you keep your component synchronized with some external system

2. How does the effect’s logic interact with the component?
    - When your component is first added to the DOM, React will run your setup function.  

3. What is the importance of the return value from the effect’s logic function?
    - Your setup function can return a cleanup function. 