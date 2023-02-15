# Class 03 Reading

## Review: ES6 Classes

[MDN - Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
1. Classes are a template for creating ____.
    - objects

2. Can a class declaration be hoisted?
    - No

3. How would you describe a constructor and contextual “this” to a non-technical friend?
    - A constructor is a method of creating an object in JavaScript (like puppy). "This" refers to an attribute of that puppy

## Using Express Routing

[Expressjs.com - Routing](https://expressjs.com/en/guide/routing.html)
1. Within Express, what does routing refer to?
    - Routing refers to how an app's endpoints respond to client requests

2. What is the difference between a route path and a route method?
    - Route method is derived from HTTP request methods
    - Route paths define endpoints at which requests can be made

3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
    - When there are multiple callback functions, next will move on to the next middleware

## Express Routing

1. What is an Express Router?
    [Digital Ocean - Express Router](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)
    - An Express Router is a mini express application that only contains routing

2. By what mean do we initialize express.Router() in an express server?
    - const router = express.Router();

3. What do we use route middleware for?
    - Using a middleware is a way to do something before a request is processed - such as logging data

## Reflection

1. What are your learning goals after reading and reviewing the class README?
    - I still want to get a good hold on tests, but after the readings and reading the README, I look forward to learning more about REST API 