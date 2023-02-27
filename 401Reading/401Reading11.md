# Reading Class 11

## Event Driven Programming

1. What native Node.js module allows us to get started with Event Driven Programming?
  [EventEmitter](https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming)
    - EventEmitter

2. What is the value of Object Oriented Programming used in tandem with Event Driven Programming?
    - The Object Oriented approach promotes the idea that all behavior of an individual object can be handled by code within that unit. By registering event listeners we can actually reverse the flow of communication between our objects. Rather than on object needing to reach inside another object to trigger a function, our objects can just emit events and whichever objects are listening to those event will process it in the way they have been told to. The source of an objects behavior is now entirely contained within itself, rather than needing to be accessed by external objects.

3. Consider your knowledge of Event Driven Programming in the Web Browser, now explain to a non-technical friend how Event Driven Programming might be useful on the backend using Node.js.
    - A link or button can be programmed to do a certain task or set of tasks in the browser (like downloading a file) and should run without risk of conflicts until the task or tasks are completed 


## Bookmark and Review
[Node docs: events](https://nodejs.org/api/events.html)

