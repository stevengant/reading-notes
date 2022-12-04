# Read Class 06

## JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?
    [MDN - Working with Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)
    A JavaScript object can be compared to a physical object: Objects have properties; eg: a cup has color, design, weight, material it is made of.

2. What are some advantages to creating object literals?
    [MDN - Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
    The use of an Object Literal makes the transfer of a series of structured, related data more efficient, as one single object is being sent.

3. How do objects differ from arrays?
    [towardsdatascience - insertion](https://towardsdatascience.com/practical-javascript-arrays-vs-objects-3c1f895907bd)
    Arrays have order; in order to insert data into an array, you would need to know the index. Objects do not keep track of order, so adding a property to the object would be much more simple.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
    [codeburst.io](https://codeburst.io/javascript-quickie-dot-notation-vs-bracket-notation-333641c0f781)
    Bracket notation allows you to use variables to access properties in an object.

5. Evaluate the code below. What does the term <this> refer to and what is the advantage to using <this>?
    [MDN - What is This](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#what_is_this)
    The <this> tag refers to the current object (dog). The advantage of using the <this> tag is that when writing multiple object literals <this> enables you to use the same method definition for every object created - efficiency.



## Introduction To The DOM

1. What is the DOM?
    [MDN - DOM Intro](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
    Document Object Model - Data representation of the objects that make up the structure and content of a web document. The DOM is a programming interface. It represents the document as nodes and objects so that programming languages can interact with the page.

2. Briefly describe the relationship between the DOM and JavaScript.
    [MDN - DOM and JavaScript](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
    The DOM is accessed directly in JS by creating a <script>.