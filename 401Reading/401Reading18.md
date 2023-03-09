# Class 18 Reading

## AWS API Gateway Overview

1. What is Amazon API Gateway?
    [What is Amazon API Gateway?](https://www.serverless.com/guides/amazon-api-gateway)
    - Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.

2. Why is Amazon API Gateway an important part of the Serverless ecosystem?
    - API Gateway is the piece that ties together Serverless functions and API definitions. Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups: it enables a truly serverless architecture for web applications. When using API Gateway together with other AWS services, it’s possible to build a fully functional customer-facing web application without maintaining a single server yourself.

3. How does API Gateway integrate with other AWS services?
    - AWS Lambda: run Lambda functions to generate HTTP API responses.
    - AWS SNS: publish SNS notifications when an HTTP API endpoint is accessed.
    - Amazon Cognito: provide authentication and authorization for your HTTP APIs.

## AWS API Gateway

1. What are the some benefits of using Amazon API Gateway?
    [AWS API Gateway - Benefits](https://aws.amazon.com/api-gateway/)
    - Eficient API development
    - Performance at any scale
    - Cost efficient at any scale
    - Easy monitoring
    - Flexible security controls
    - RESTful API options

2. What two API types might you choose from?
    - RESTful
    - Websocket

## AWS DynamoDB Guide

1. What is DynamoDB?
    [dynamodb.com - What is DynamoDB?](https://www.dynamodbguide.com/what-is-dynamo-db/)
    - DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS)

2. Under what circumstances would you recommend DynamoDB over MongoDB?
    - when working with large amounts of data

## AWS DynamoDB

1. Explain to a non-technical friend how DynamoDB works.
    [AWS DynamoDB - How it works](https://aws.amazon.com/dynamodb/)
    - DynamoDB is a fully managed database that can be used in conjunction with AWS serverless services. It offers built-in security, automatic backups and scaling. 

## Dynamoose

1. What is Dynamoose?
    [Dynamoose - Description](https://dynamoosejs.com/getting_started/Introduction)
    - Dynamoose is a modeling tool for Amazon's DynamoDB that is inspired by Mongoose

2. What are some key features of Dynamoose?
    - Type safety
    - High level API
    - Easy to use syntax
    - DynamoDB Single Table Design Support
    - Ability to transform data before saving or retrieving items
    - Strict data modeling (validation, required attributes, and more)
    - Support for DynamoDB Transactions
    - Powerful Conditional/Filtering Support
    - Callback & Promise support
    - AWS Multi-region support