# Reading10

## Understanding the JavaScript Call Stack

1. What is a ‘call’?
    [FreeCodeCamp - The JavaScript Call Stack - What It Is and Why It's Necessary](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)
    - The call stack is primarily used for function invocation


2. How many ‘calls’ can happen at once?
    - One at a time, from top to bottom

3. What does LIFO mean?
    - Last In, First Out

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
    - function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();


5. What causes a Stack Overflow?
    - A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

## JavaScript error messages

1. What is a ‘reference error’?
    [codeburst.io - Types of errors](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
    - When you try to use a variable that has not yet been declared.

2. What is a ‘syntax error’?
    - Occurs when you have something that cannot be parsed.

3. What is a ‘range error’?
    - When you try to manipulate object with invalid length.

4. What is a ‘type error’?
    - When you try to use incompatible types.

5. What is a breakpoint?
    - Will make your program stop at that point if a condition has been met.

6. What does the word ‘debugger’ do in your code?
    - Will add a breakpoint in your program.