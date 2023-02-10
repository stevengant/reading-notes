# HTML Forms

##### [Your First Web Form](Your first Web Form. How To Structure A Web Form)

1. Why are forms so important in web development?
    [MDN - What are web forms?](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)
    WEb forms allow users to interact with websites. They allow users to enter data that is sent to a server for processing and storage, or used client-side to immediately update the interface (like adding items to a shopping cart).

2. When designing a form, what are some key things to keep in mind when it comes to user experience?
    [MDN - Designing your form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form#designing_your_form)
    Keep it simple - if the form is too big, the user may lose interest. Ask only for the data you actually need.

3. List 5 form elements and explain their importance.
    <form> - all forms start with the form element.
    <label> - this is similar to a title or header for a specific section of the form.
    <input> - this element creates a space for specific info: email, phone, etc.
    <textarea> - this element creates a text box where users can enter comments, reviews, etc.
    <button> - this allows users to "save" changes.

# Learn JS

##### [Intro to Events](Introduction To Events)

1. How would you describe events to a non-technical friend?
    [MDN - Introduction to events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
    An example of an event is when you interact with the website, like clicking the "Add to Cart" button. It tells the website that you added something to your cart and it changes the appearance of the cart logo. 

2. When using the addEventListener() method, what 2 arguments will you need to provide?
    [MDN - UsingaddEventListener](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#using_addeventlistener)
    The name of the event and the code/function that makes up the handler function.

3. Describe the event object. Why is the target within the event object useful?
    [MDN - Event objects](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#event_objects)
    The event object is a function created that can be reused where needed.

4. What is the difference between event bubbling and event capturing?
    [MDN - Event bubbling](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#event_bubbling)
    Event bubbling targets nested elements - starts with the innermost element, like the button and bubbles out from there.
    Event capture is the reverse of bubbling. It fires on the outermost element and works its way in. By default, capture is disabled and must be enabled by adding the option: eg - container.addEventListener('click', handleClick, { capture: true });


