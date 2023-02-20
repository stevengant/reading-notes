# 401 Reading 06

## Securing Passwords

1. Explain to a non-technical friend how you would safely hash and store a password.
    [The Hacker News -Securing Passwords with Bcrypt Hashing Function](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)
      - I would use something like Bcrypt to secure the information. If an attacker is successful in getting information, they will only get information that is unreadable.

2. What is Bcrypt?
      - Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm. It introduces a work factor that allows you to determine how expensive the hash function will be. 

3. Why might you use something like Bcrypt?
      - Bcrypt will slow down attacks, allowing for the information to be preserved

## Basic Auth

1. What is Basic Authentication?
    [Basic Access Authentication](https://en.wikipedia.org/wiki/Basic_access_authentication)
      - Basic Authentication is when a user provides user name and password and does not require cookies

2. What properties are necessary in the header of a Basic Auth request?
      - In basic HTTP authentication, a request contains a header field in the form of Authorization: Basic <credentials>, where credentials is the Base64 encoding of ID and password joined by a single colon :.

3. How are username:password in Basic Auth encoded?
      - Encoded with Base64 in transit and not encrypted or hashed in any way.

## OWASP auth cheatsheet

1. Define the authentication process to a non-technical recruiter.
    [OWASP Authentication Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)
      - Authentication is the process verifying that a person is who they say they are. It is the process of requiring a user to provide information that only that individual should know.

2. How should your error messaging respond (both HTTP and HTML)? Why?
    - Error messages should be generic in order to avoid potentially giving away information to a potential attacker.

3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.


## Bookmark and Review

[bcrypt docs](https://www.npmjs.com/package/bcrypt)

## Additional Questions

1. Looking ahead at this module’s course schedule, What do you look forward to learning?
    - I am honestly looking forward to learning about authentication in general

2. What are your learning goals after reading and reviewing the class README?
    - to learn how to encrypt users' information