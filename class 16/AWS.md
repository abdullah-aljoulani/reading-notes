## AWS: Cloud Servers

### AWS EC2

**What is an EC2 Instance?**

is a virtual server provided by Amazon Web Services (AWS). It is a fundamental building block of the AWS cloud computing platform, allowing users to rent virtual machines on which they can run their applications.

**Name 2 use cases for EC2.**

1-Web Hosting and Application Deployment
2-Data Processing and Analysis

**Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.**

Seamless Integration with AWS Ecosystem: If you are already heavily invested in the AWS ecosystem and using various other AWS services, choosing Amazon ECS can provide a seamless integration experience

### EC2 For Humans

**Where can we find EC2 on the AWS Console?**

we can find the "EC2" service in the list of AWS services.

**Explain the general difference between T2 Micro and XL.**

T2 Micro is the lower-end option suitable for lightweight tasks and applications with modest processing requirements and memory needs. It is cost-effective for low-demand scenarios. On the other hand, T2 XL offers more compute capacity, memory, and is better suited for resource-intensive workloads and applications that require higher performance and processing capabilities.

**Explain a “Compute Cycle” to a non-technical friend.**

A compute cycle is a fundamental unit of work that allows a computer to process information, perform calculations, and run all the programs and applications we use in our daily lives. The more compute cycles a computer can handle per second, the more powerful and efficient it is at getting things done.

### Elastic Beanstalk

**What is Elastic Beanstalk?**

Elastic Beanstalk is a fully managed service provided by Amazon Web Services (AWS) that simplifies the deployment and management of web applications and services. It allows developers to quickly deploy applications and handle the underlying infrastructure without having to deal with the complexities of provisioning and managing servers, load balancers, and other resources.

**Describe the relationship between EC2 and Elastic Beanstalk.**

Amazon EC2 provides the core infrastructure for running virtual servers, while Elastic Beanstalk builds on top of EC2 to provide a managed platform for deploying, managing, and scaling applications. Elastic Beanstalk abstracts away much of the infrastructure complexity, allowing developers to focus on application code and development while still having control and flexibility when needed. This relationship provides an optimal balance between ease of use and customization for deploying and managing applications on AWS.

**Name some benefits of using Elastic Beanstalk.**

1-Support for Multiple Platforms and Languages: Elastic Beanstalk supports a variety of programming languages and platforms, including Java, .NET, Node.js, Python, Ruby, Go, and Docker
2-Cost-Effective: Elastic Beanstalk's automated environment management and scaling capabilities optimize resource usage, leading to cost savings.
3-Easy Application Deployment: Elastic Beanstalk simplifies the deployment process, allowing developers to quickly deploy applications with just a few clicks or commands.