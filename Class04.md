# Read: Class 04

## Learn HTML

##### Creating Hyperlinks

1. To create a basic link, we wrap text or other content inside what element?
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

    <a href="https://www.someurl.com">Some URL</a>

2. The href attribute contains what information?
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

    Hypertext Reference - target

3. What are some ways we can ensure links on our pages are accessible to all readers?
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

    By adding plain text between the opening and closing <a> tags.


## CSS Layout

##### CSS Layout: Normal Flow CSS Layout: Positioning

1. What is meant by “normal flow”?
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)

    Normal flow is the default layout of a browser if no CSS has been applied.

2. What are a few differences between block-level and inline elements?
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)

    - Block-level fills available inline space of the parent element and grows along the block element to accomodate its content.
    - Inline elements size does not change.
    - Block-level elements will appear on a line below the last element.
    - Inline elements will appear along the same line as the last element.


3. ___ positioning is the default for every html element.
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)

    Static positioning

4. Name a few advantages to using absolute positioning on an element.
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)

    - Absolute positioning allows you to put an element in a certain position of the screen where it won't interfere.
    - Also allows for things like Sticky Headers and navbars that stay at the top of the screen where they are easily accessible - so user doesn't have to scroll to the top.
    - Also allows for nav buttons like a 'Top' button where user can quickly move to the top of the page without scrolling.

5. What is a key difference between fixed positioning and absolute positioning?
    [W3 Schools](https://www.w3.org/wiki/CSS_absolute_and_fixed_positioning?source=post_page#:~:text=Absolutely%20positioned%20elements%20are%20positioned,is%20always%20their%20containing%20block.)
    
    - Absolutely positioned elements are positioned in respect to a containing block, or if there is no containing block, the viewport will be the containing block.
    - Fixed positioned elements are fixed with respect to the viewport only.


## Learn JS

##### Functions – Reusable Blocks of Code

1. Describe the difference between a function declaration and a function invocation.
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions#invoking_functions)

    - Function Declaration is where the function parameters are defined.
    - Invoking a function is when the defined function is actually used.


2. What is the difference between a parameter and an argument?
    [MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions#invoking_functions)

    - Parameters are set when declaring a function.
    - Arguments are set when invoking a function.


## Miscellaneous

##### 6 Reasons for Pair Programming

1. Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.

    - Greater Efficiency. When two people are looking at and working on the same code, it should be easier to catch errors. Also would help when one person gets stuck.
    - Learning from fellow students. Not everyone learns at the same pace. If one of the pair is stronger, the weaker/less experienced dev would benefit from collaborating with a stronger individual by learning new tricks or gaining deeper understanding of what they are working on.