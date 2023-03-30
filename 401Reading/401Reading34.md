# Class 34 Reading

## API Integration



### Review API Server Build

1. Explain the difference between a query string parameter and a path parameter.
  - A query string parameter is a set of key-value pairs in the URL after a "?"; eg: `https://example.com/search?q=flowers&type=images` 
  - A path parameter is specified with curly braces `{ }` in the URL; eg: `https://example.com/products/{productId}`

2. What would our API URL with a path id parameter be given the following information:
  1. Domain: `http://our-site.com`
  2. `v3`
  3. model name: `stuff`
  4. id: `things`
  - `http://our-site.com/v3/stuff/things/`

3. We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
  - Rather than having to write a bunch of code ourselves, we are able to create an interface that interacts with a remote code base that someone else took the time to write (and in a lot of cases maintains and updates).
  We just create a path between our code and the API server to allow them to communicate and get information for us.


### Review Auth Server Build
1. Describe how you would use middleware to implement basic and bearer auth.
  - To implement basic authentication, you could use a middleware function that checks for the presence of the "Authorization" header in the incoming request. If the header is present, the middleware function decodes the header and verifies the credentials against the user database.
  - To implement bearer authentication, you could use a middleware function that checks for the presence of the "Authorization" header in the incoming request. If the header is present, the middleware function verifies that the token is valid by checking against a list of valid tokens.

2. Describe the handshake necessary to implement OAuth.
  - The user is authenticated by providing their credentials to a third party. Once authenticated, the third party will route the user to the appropriate URL. 

3. Describe how Role Based Access Control works to a non-technical friend.
  - For example, Role Based Access Control allows your IT department to set up permissions for groups of people, based on their role in the company.
    - An IT admin would likely be able to Read, Create, Update and Delete all or most information available.
    - A manager may be able to Read, Create and Update information.
    - A regular user would likely only be able to Read