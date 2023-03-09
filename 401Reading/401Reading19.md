# Class 19 Reading

## AWS SQS vs SNS

1. What is the difference betweeen SQS and SNS?
    [Medium - AWS — Difference between SQS and SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)
    - SNS (Simple Notification Service)is a distributed publish-subscribe service
    - SQS (Simple Queue Service) is a distributed queueing service

2. What are some use cases for both SNS and SQS?
    - SNS can be used to send push notifications to many subscribers of a certain type
    - SQS cannot be sent to multiple receivers. Messages are saved in a queue for a specific amount of time and receivers must poll SQS to receive notifications (like a newsletter)

## AWS SNS and SQS

1. Describe how to use SQS and SNS in a “fanout” pattern.
    [SNS vs SQS Comparison? Whats the difference? | Learn with a practical example](https://www.youtube.com/watch?v=mXk0MNjlO7A)
    - Transaction requests can be distributed to multiple processing services using fanout messaging

2. Explain how “push notifications” work, using SNS.
    - Using SNS, push notifications can easily be sent to specific subscribers

## SQS and SNS Basics

1. How might a large scale, distributed application make use of a Queue system like SQS?
    [Decouple and Scale Applications Using Amazon SQS and Amazon SNS - 2017 AWS Online Tech Talks](https://www.youtube.com/watch?v=UesxWuZMZqI)
    - Separate throughput from latency
    - Use batch APIs wherever relevant
    - Tradeoff message durability and latency