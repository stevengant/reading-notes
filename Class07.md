# Class07

## Domain Modeling

1. Explain why we need domain modeling.
    [MDN - Model epic fails videos](https://github.com/codefellows/domain_modeling#domain-modeling)
    Using models enables a dev to duplicate code quickly and efficiently by building self-contained objects with same attributes, making future changes much easier.


## HTML Table Basics

1. Why should tables not be used for page layouts?
    [MDN -When should you NOT use HTML tables?](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
    - Tables reduce accessibilty
    - Tables create tag soup; code is harder to read
    - Tables are not responsive automatically

2. List and describe 3 different semantic HTML elements used in an HTML table.
    [MDN - HTML table basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
      <th> - table header: goes at beginning of table row/column. The <th> tag makes the wrapped text stand out, making the table easier to read.
        <tr> - table row: each subsequent <tr> tag creates a new row below the preceding one in the table.
          <td> - table data: is the smallest container in a table. Contains specific data about the subject.


## Introducing Constructors

1. What is a constructor and what are some advantages to using it?
    [MDN - Introducing constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)
    When called, a constructor will create a new object, binds this to the new object. A constructor is a more efficient way to create new objects of similar description.

2. How does the term this differ when used in an object literal versus when used in a constructor?
    [MDN - What is "this"](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#what_is_this)
    In obect literals, this refers to the object. In constructors, this refers to attributes of objects.


## Object Prototypes Using A Constructor

1. Explain prototypes and inheritance via an analogy from your previous work experience.
NOTE: This is a very common front end developer interview question
    [UI.dev - ](https://ui.dev/beginners-guide-to-javascript-prototype)
    [MDN - Inheritance with the prototype chain](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain#inheritance_with_the_prototype_chain)
    Prototype: Think of a prototype as creating an order. You are creating a new order for almost every contractor you speak with; this is a common pattern that can easily be repeated using prototype.

    Inheritance: Inheritance allows you to access orders of a specific prototype. 



## I would like to learn:

    More about inheritance of prototypes.