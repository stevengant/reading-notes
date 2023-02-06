# Reading 15

## What is OAuth

1. What is OAuth?
    [CSOnline - 0Auth definition](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)
    - Open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.

2. Give an example of what using OAuth would look like.
    - You can use your Google login info to fill info in on another site - like GitHub

3. How does OAuth work? What are the steps that it takes to authenticate the user?
    - First website connects to the second website on behalf of the user, providing the user’s verified identity.
    - Second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
    - First site gives this token and secret to the initiating user’s client software.
    - Client’s software presents the request token and secret to their authorization provider
    - If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
    - The user approves a particular transaction type at the first website.
    - The user is given an approved access token.
    - The user gives the approved access token to the first website.
    - The first website gives the access token to the second website as proof of authentication on behalf of the user.
    - The second website lets the first website access their site on behalf of the user.
    - The user sees a successfully completed transaction occurring.

4. What is OpenID?
    - Authentication

## Authorization and Authentication flows

1. What is the difference between authorization and authentication?


2. What is Authorization Code Flow?


3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?


4. What is Implicit Flow with Form Post?


5. What is Client Credentials Flow?


6. What is Device Authorization Flow?


7. What is Resource Owner Password Flow?