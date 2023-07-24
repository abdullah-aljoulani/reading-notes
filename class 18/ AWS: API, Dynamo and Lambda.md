##  AWS: API, Dynamo and Lambda

### AWS API Gateway Overview

**What is Amazon API Gateway?**

Amazon API Gateway is a fully managed service provided by Amazon Web Services (AWS) that makes it easy to create, publish, maintain, monitor, and secure APIs (Application Programming Interfaces). It acts as a front-door for applications to access data, business logic, or functionality from backend services, serverless functions, or other AWS resource

**Why is Amazon API Gateway an important part of the Serverless ecosystem?**

1-API Management: In serverless architectures, different components and services are often connected through APIs.
2-Front-door for Serverless Functions: In serverless applications, the backend logic often resides in AWS Lambda functions.
3-Security: Security is a vital aspect of serverless applications.

**How does API Gateway integrate with other AWS services?**

Amazon API Gateway integrates with various AWS services, allowing you to seamlessly connect your APIs to backend resources, serverless functions, and other AWS offerings.

### AWS API Gateway

**What are the some benefits of using Amazon API Gateway?**

1-Scalability: API Gateway is a fully managed service that automatically scales to handle any level of incoming API traffic.
2-Serverless Integration: API Gateway seamlessly integrates with AWS Lambda, making it easy to build serverless APIs.
3-Monitoring and Logging: API Gateway offers detailed logging and monitoring capabilities.

**What two API types might you choose from?**

1-RESTful APIs: REST (Representational State Transfer) is a widely used architectural style for designing networked applications. 
2-WebSocket APIs: WebSocket is a protocol that enables bidirectional communication between clients and servers over a single, long-lived connection.

### AWS DynamoDB Guide

**What is DynamoDB?**

DynamoDB is a fully managed NoSQL database service provided by Amazon Web Services (AWS). It is designed to provide fast and predictable performance with seamless scalability, making it a popular choice for building highly responsive and scalable applications.

**Under what circumstances would you recommend DynamoDB over MongoDB?**

1-Fully Managed Service: If you prefer a fully managed database service with minimal operational overhead, DynamoDB is a better choice.
2-Global Distribution: If you need a database that can span across multiple geographic regions to provide low-latency access to users worldwide, DynamoDB Global Tables allow you to replicate data globally with ease.
3-Serverless Architecture: If you are building a serverless application on AWS, DynamoDB integrates seamlessly with other AWS services like AWS Lambda and Amazon API Gateway.

### AWS DynamoDB

**Explain to a non-technical friend how DynamoDB works**

DynamoDB is a powerful and intelligent database service that stores and manages your digital information (items) on a cloud-based bookshelf. It's incredibly fast, automatically scales to handle any number of requests, and keeps your data safe and secure. Whether you're building a small application or a giant one used by millions of people, DynamoDB is the magical bookshelf that makes it all possible

### Dynamoose

**What is Dynamoose?**

Dynamoose is a popular Node.js library and Object Data Modeling (ODM) tool designed to simplify the interaction with Amazon DynamoDB, the fully managed NoSQL database service provided by Amazon Web Services (AWS). It acts as a bridge between your Node.js application and DynamoDB, making it easier to work with DynamoDB by providing a higher-level abstraction for data modeling and querying.

**What are some key features of Dynamoose?**

1-Automatic Schema Creation: When you define a model in Dynamoose, it automatically creates the corresponding table schema in DynamoDB.
2-Query Building: Dynamoose simplifies the process of building and executing queries for DynamoDB.
3-Transactions: Dynamoose supports transactional operations, which enable you to perform multiple operations as a single, atomic unit