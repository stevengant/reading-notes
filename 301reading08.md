# API Design Best Practices

1. What does REST stand for?
    [RESTful web API design](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
    - Representational State Transfer

2. REST APIs are designed around a ____.
    [What is REST?](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
    - Resource

3. What is an identifier of a resource? Give an example.
    - A URI that uniquely identifies that resource

4. What are the most common HTTP verbs?
    - GET, POST, PUT, PATCH, and DELETE

5. What should the URIs be based on?
    [Organize the API design around resources](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
    - URIs should be based on nouns (the resource) and not verbs (the operations on the resource)

6. Give an example of a good URI.
    - A list of your orders on Amazon. 

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
    - Web APIs that expose a large number of small resources. This is bad because it could impose too much load on the web server.

8. What status code does a successful GET request return?
    - 200

9. What status code does an unsuccessful GET request return?
    - 204

10. What status code does a successful POST request return?
    - 201

11. What status code does a successful DELETE request return?
    - 204