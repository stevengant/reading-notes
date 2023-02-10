# Read: Class 03

## Learn HTML
###### Ordered and Unordered Lists

1. When should you use an unordered list in your HTML document?
    [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
    When changing the order of the listed items doesn't effect the meaning of the list.

2. How do you change the bullet style of unordered list items?
    [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul#attr-type)
    You can change the bullet style by using the type attribute and selecting disc, circle, square or none - ie: <ul type="circle">. 

3. When should you use an ordered list vs an unorder list in your HTML document?
    [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
    An ordered list should be used if the order of the items is meaningful - such as steps in a set of instructions.
    Unordered lists can be used when changing the order of the list items does not change the meaning of the list.

4. Describe two ways you can change the numbers on list items provided by an ordered list?
    [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
    You can change the number by using the type attribute (like the unordered list). You can also change the number using CSS list-style-type property.


## Learn CSS
##### The Box Model

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#margins_padding_and_borders)
    Margins are pushy little snits that form a bubble or space around their box. Margins can be bi-polar, often displaying postive and negative values simultaneously.
    Padding is a little more laid back. Padding sits between it's box and the box's border. Padding only displays positive values, which is sometimes not all it's cracked up to be.

2. List and describe the four parts of an HTML elements box as referred to by the box model.
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#block_and_inline_boxes)
    CONTENT BOX: The area where content is displayed.
    PADDING BOX: The padding surrounds the Content Box with white space.
    BORDER BOX: The Border Box wraps the Content and Padding.
    MARGIN BOX: Outer most layer; wraps around Content, Padding and Border as whitespace between this box and other elements.


## Learn JS

1. What data types can you store inside of an Array?
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
    Strings, numbers, objects and other arrays.

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
    Yes. You can access the information using something like:
    console.log(people)[0].

3. List five shorthand operators for assignment in javascript and describe what they do.
    [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
    x=f() : Assignment operator - Assigns value to variable
    x += f(): Addition operator - Adds given arguments
    x -= f(): Subtraction operator - Subtracts given arguments
    x *= f(): Multiplication operator - Multiplies given arguments
    x /= f(): Division operator - Divides given arguments

4. Read the code below and evaluate the last expression and explain what the result would be and why.
    [Repl](https://replit.com/@sgant/ExemplaryDangerousMicrokernel#index.js)
    The output is 10dog when you console.log. 
    I believe this is because 'false' is being treated as zero. Then, the string 'dog' is being added to the end of the sum. 

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
    A good example of the use of coinditional statements would be when a user is asked to make choices on a page - such as surveys or quizzes.

6. Give an example of when a Loop is useful in JavaScript.
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
    A perfect example of when a loop would be a good idesa in JS is when you want to 'draw' lots of images on the screen, so you don't have to write the same code for each individual image.