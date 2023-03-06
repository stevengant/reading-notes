# Class 16 Reading

## AWS EC2

1. What is an EC2 Instance?
    [Amazon Elastic Compute Cloud Documentation](https://docs.aws.amazon.com/ec2/index.html?nc2=h_ql_doc_ec2)
    - Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides resizable computing capacity—literally, servers in Amazon's data centers—that you use to build and host your software systems.

2. Name 2 use cases for EC2.
    [Amazon EC2 - Use Cases](https://aws.amazon.com/ec2/)
    - Run cloud-native and enterprise applications
    - Scale for High Performance Computing (HPC) applications

3. Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.
    - Speed

## EC2 For Humans

1. Where can we find EC2 on the AWS Console?
    [EC2 for Humans | Amazon Web Services BASICS](https://www.youtube.com/watch?v=lZMkgOMYYIg)
    - In the AWS Services console, under the Compute section

2. Explain the general difference between T2 Micro and XL.
    - The number of virtual CPUs: Micro has one, XL has four
    - Amount of memory: Micro has one GiB, XL has 16

3. Explain a “Compute Cycle” to a non-technical friend.
    [The Free Dictionary - Instruction Cycle](https://encyclopedia2.thefreedictionary.com/Computer+cycle)
    - Compute cycle refers to the sequence of steps that a CPU performs. The CPU transfers an instruction from RAM to the register and decodes it, then executes it.

## Elastic Beanstalk

1. What is Elastic Beanstalk?
    [Introduction to AWS Elastic Beanstalk](https://www.youtube.com/watch?v=SrwxAScdyT0)
    - Elastic Beanstalk is a service that deploys, manages and scales web apps and services

2. Describe the relationship between EC2 and Elastic Beanstalk.
    - Elastic Beanstalk manages the EC2 instance(s)

3. Name some benefits of using Elastic Beanstalk.
    - Load Balancing
    - Provisioning
    - Automatic Scaling
    - Application Health Monitoring
