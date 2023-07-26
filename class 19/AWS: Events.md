## AWS: Events

### AWS SQS vs SNS

**What is the difference betweeen SQS and SNS?**

use SQS when you need to decouple components in a distributed system with a message queue, and use SNS when you want to broadcast messages to multiple subscribers or applications using a publish-subscribe pattern.

**What are some use cases for both SNS and SQS?**

Use Cases for SNS
1-Real-time Alerts and Notifications
2-Application Monitoring and Alarms
3-Email Communication

Use Cases for SQS
1-Message Decoupling and Load Balancing
2-Order Processing
3-Cross-Region Communication

### AWS SNS and SQS

**Describe how to use SQS and SNS in a “fanout” pattern.**

Using SQS and SNS in a "fanout" pattern is a common architectural approach in distributed systems where a single message is broadcasted to multiple consumers (subscribers). This pattern allows decoupling between publishers and subscribers, ensuring that each subscriber independently receives a copy of the message

**Explain how “push notifications” work, using SNS.**
1-Create an SNS :First, you create an SNS topic in your AWS account
2-Subscribe Endpoints to the SNS :Mobile devices, web browsers, or other endpoints that want to receive push notifications need to subscribe to the SNS topic.
3-Link Endpoints with Device Tokens

### SQS and SNS Basics

**How might a large scale, distributed application make use of a Queue system like SQS?**

Integrating SQS into a large-scale, distributed application can significantly improve the system's performance, reliability, and scalability. It enables better resource management, efficient handling of tasks, and seamless communication between different components, all of which are vital for building and operating a robust distributed application.