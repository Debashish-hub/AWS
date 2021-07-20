# Section 3: Introduction to Amazon Web Services

## What are Web services?

In general, a web service is any piece of software that makes itself available over the internet or on private (intranet) networks. A web
service uses a standardized format—such as Extensible Markup Language (XML) or JavaScript Object Notation (JSON)—for the request and the 
response of an application programming interface (API) interaction. It is not tied to any one operating system or programming language. It’s 
self-describing via an interface definition file and it is discoverable.

## What is AWS?

Amazon Web Services (AWS) is a secure cloud platform that offers a broad set of global cloud-based products. Because these products are 
delivered over the internet, you have on-demand access to the compute, storage, network, database, and other IT resources that you might 
need for your projects—andthe tools to manage them. You can immediately provision and launch AWS resources. The resources are ready for you 
to use in minutes. 
AWS offers flexibility. Your AWS environment can be reconfigured and updated on demand, scaled up or down automatically to meet usage 
patterns and optimize spending, or shut down temporarily or permanently. The billing for AWS services becomes an operational expense instead of a capital expense.
AWS services are designed to work together to support virtually any type of application or workload. Think of these services like building 
blocks, which you can assemble quickly to build sophisticated, scalable solutions, and then adjust them as your needs change.

## Categories of AWS Services

AWS services fall under different categories, and each category contains one or more services. You can select the services that you want from these different categories to build your solutions.

For example, say you’re building a database application. Your customers might be sending data to your Amazon Elastic Compute Cloud (Amazon EC2) instances, which is a service in the compute category. These EC2 servers batch the data in one-minute increments and add an object per customer to Amazon Simple Storage Service (Amazon S3), the AWS storage service you’ve chosen to use. You can then use a nonrelational database like Amazon DynamoDB to power your application, for example, to build an index so that you can find all the objects for a given customer that were collected over a certain period. You might decide to run these services inside an Amazon Virtual Private Cloud (Amazon VPC), which is a service in the networking category.
The purpose of this simple example is to illustrate that you can select web services from different categories and use them together to build a solution (in this case, a database application). Of course, the solutions you build can be quite complex.

## Choosing a service

Which service you choose to use will depend on your business goals andtechnology requirements. In the example you just looked at, the solution made use of Amazon EC2 as the compute service. However, that is only one of many compute services that AWS offers. Here are some other AWS compute offerings that you might choose to use for the following example use cases:
• Amazon EC2: You want complete control over your AWS computing resources.
• AWS Lambda: You want to run your code and not manage or provision servers.
• AWS Elastic Beanstalk: You want a service that deploys, manages, and scales your web applications for you.
• Amazon Lightsail: You need a lightweight cloud platform for a simple web application.
• AWS Batch: You need to run hundreds of thousands of batch workloads.
• AWS Outposts: You want to run AWS infrastructure in your on-premises data center.
• Amazon Elastic Container Service(Amazon ECS), Amazon Elastic Kubernetes Service(Amazon EKS), or AWS Fargate: You want to implement a containers or microservices architecture.
• VMware Cloud on AWS: You have an on-premises server virtualization platform that you want to migrate to AWS.

Similarly, there are a variety of services for you to choose from in the other categories, and the number of offerings keeps growing.

## Three ways to interact with AWS

You might wonder how to access the broad array of services that are offered by AWS. There are three ways to create and manage resources on the AWS Cloud:
• AWS Management Console: 
    The console provides a rich graphical interface to a majority of the features offered by AWS. (Note: From time to time, new features might not have all of their capabilities included in the console when the feature initially launches.)
• AWS Command Line Interface (AWS CLI):
    The AWS CLI provides a suite of utilities that can be launched from a command script in Linux, macOS, or Microsoft Windows.
• Software development kits (SDKs):
    AWS provides packages that enable accessing AWS in a variety of popular programming languages. This makes it easy to use AWS in your existing applications and it also enables you to create applications that deploy and monitor complex systems entirely through code. 
    
All three options are built on a common REST-like API that serves as the foundation of AWS.

