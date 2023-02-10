This exercise teaches new devs to use docs for a given language as a helpful tool to make their job easier. Shows us that we don't need to memorize everything.
## Getting Started

1.**Compose a short poem describing how HTTP sends data between computers.**
[How the Web Works - Mozilla.org](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works#:~:text=The%20browser%20sends%20an%20HTTP,internet%20connection%20using%20TCP%2FIP.)
The Client Browser sends a message via HTTP
to the DNS Server, "There's a web page I'd like to see. Can you give that address to me?"
The Server says, "Certainly, since you have asked so nicely,
here is your package. I shall display it for you promptly"

2.**Describe how HTML, CSS, and JS files are “parsed” in the browser.**
[How the Web Works - Mozilla.org](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works#:~:text=The%20browser%20sends%20an%20HTTP,internet%20connection%20using%20TCP%2FIP.)
The  browser parses HTML files first, as they are the most basic building block of a web page. From there, the browser will recognize any <link> to external CSS files, along with 
<script> elements referring to JavaScript files, and requests those from the server.

3.**How can you find images to add to a Website?**
[MDN - What Will Your Website Look Like(https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)]
The quickest way to find images is to do a Google search for your desired image. Once you've found your image, right-click the image and choose Save Image As..., or you can
copy the image's URL and use that inside an <img> tag.

4.**How do you create String vs a Number in JavaScript?**
[MDN - JavaScript basics(https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)]
String example - let myVariable = 'Ten';  Strings should be surrounded by quotes(' or ", as long as they are the same).
Number example - let myVariable = 10; Numbers are not to be surrounded by quotes.

5.**What is a Variable and why are they important in JavaScript?**
[MDN - JavaScript basics(https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)]
Variables are containers that store a value. They are important because they allow the developer to refer to that variable, rather than writing the same code over and over.

## Introduction to HTML

1.**What is an HTML attribute?**
[MDN - Introduction to HTML(https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started#attributes)]
HTML attributes contain additional information about an HTML element, that allows for specific styling or adding a hyperlink to an <a> tag.

2.**Describe the anatomy of an HTML element.**
[MDN - Introduction to HTML(https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started#attributes)]
The element starts with an opening tag (such as a paragraph <p> tag and ends with a closing tag (</p). In between those tags is the content (usually text for a <p> 
element).

3.**What is the difference between <article> and <section> element tags?**
[MDN - Introduction to HTML(https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure#Enter_HTML5_structural_elements)]
An <article> encloses a block of related content. Can be used on its own, or could include <section> tags. <section> tags can be used to group together single bits of
information relating to specific parts of web page (ie: a theme).

4.**What Elements does a “typical” website include?**
<!DOCTYPE html>
<html lang="en-US">
<head>
<meta charset="utf-8">
<title></title>
</head>
<body>
</body>
</html>

5.**How does metadata influence Search Engine Optimization?**
[Stacksteam - What is Metadata?(https://www.stacksteam.com/blog/how-metadata-can-improve-your-seo-ranking)]
Metadata is data written in a language a browser can understand. It helps to generate more traffic as the browser is able to quickly pick out relevant information
about your page through the use of keywords found in the metadata.

6.**How is the <meta> HTML tag used when specifying metadata?**
[W3 Schools(https://www.w3schools.com/tags/tag_meta.asp#:~:text=The%20tag%20defines%20metadata,the%20document%2C%20and%20viewport%20settings.)]
The <meta> tag is used to specify character set, page description, keywords , author and viewport settings.

## Miscellaneous

1.**What is the first step to designing a Website?**
[MDN - Thinking before coding(https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)]
The first step in designing a website is to ask yourself a few questions:
  - What do I want to accomplish?
  - How will a website help me reach my goals?
  - What needs to be done, in what order, to reach my goals?
  
2.**What is the most important question to answer when designing a Website?**
What do I want to accomplish? 

## Semantics

1.**Why should you use an <h1> element over a <span> element to display a top level heading?*
[MDN(https://developer.mozilla.org/en-US/docs/Glossary/Semantics)]
An <h1> tag can make a <span> element look like a top level heading.

2.**What are the benefits of using semantic tags in our HTML?**
[MDN(https://developer.mozilla.org/en-US/docs/Glossary/Semantics)]
An <h1> tag helps the code within to stand out more when reading the code. It also tells the browser that this bit of code has more importance.

## What is JavaScript?

1.**Describe 2 things that require JavaScript in the browser.**
[Hack Reactor(https://www.hackreactor.com/blog/what-is-javascript-used-for)]
Interactive items in browsers require JavaScript. A couple of examples would be a SearchBox used to enter keywods or items to search for, and  embedded video players.

2.**How can you add JavaScript to an HTML document?**
[MDN - What is JavaScript?(https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript#a_high-level_definition)]
In order to add JavaScript to HTML file, you would add a <script> tag just before the closing </head> tag. You can then write JavaScript inside that element, or you
write an external JS file and reference/link it using an attribute (<script src="script.js">).


## Things I want to know more about 
