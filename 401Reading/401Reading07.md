# 401 Reading 07

## Intro to JWT

1. What is a JSON Web Token (JWT)?
    [What is JSON Web Token](https://jwt.io/introduction/)
    - JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

2. When should we use JSON Web Tokens?
    - Authorization and information Exchange

3. Claims are expected in which structural component of a JWT?
    - In the payload

## Are JWTs Secure?

1. If I get a JWT and I can decode the payload, how can we call that secure?
    [If you can decode JWT, how are they secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)
    - Because you also need the secret

2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
    - The hash

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
    - The JWT is sent in two parts; the data and a secret. Both parties need to know the secret in order to decode the message.

## Videos

## JWTs Explained

1. Why use JWT?
    [What is JWT ? JSON Web Token Explained](https://www.youtube.com/watch?v=926mknSW9Lo)
      - For authentication and Information exchange

2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
    - JWT is compact to the point where it can be quickly transmitted and sent in many different ways. It also contains information about the user and avoids querying the database more than once which speeds the process.

3. What are the three components (the structure) of a JWT signature?
    - Header, Payload and Signature

## Bookmark and Review
npm jsonwebtoken docs


## Reflection
1. What are your learning goals after reading and reviewing the class README?
    Learn about tokens