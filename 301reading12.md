# Reading12

## Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:

+ 100’s = Informational only: usually tell client header info has been received
+ 200’s = Success codes:tell client that request has been received
+ 300’s = Redirection codes: tell the client the requested resources aren't available at expected location
+ 400’s = Client error codes: tell client that request is invalid
+ 500’s = Server error codes: usually due to overwhelmed servers

2. What is a status code 202?
    - Asynchronous processing of request

3. What is a status code 308?
    - Permanent redirect

4. What code would you use if an update didn’t return data to a client?
    - 204

5. What code would you use if a resource used to exist but no 
longer does?
    - 308

6. What is the ‘Forbidden’ status code?
    - 403