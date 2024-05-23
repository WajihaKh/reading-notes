# AWS: Events

1. **What is the difference between SQS and SNS?**
   - SQS (Simple Queue Service) is a message queuing service, while SNS (Simple Notification Service) is a pub/sub messaging service.

2. **What are some use cases for both SNS and SQS?**
   - SQS is used for decoupling and asynchronous communication between microservices, while SNS is used for push-based messaging and event-driven architectures.

3. **Describe how to use SQS and SNS in a “fanout” pattern.**
   - In a "fanout" pattern, you publish a message to an SNS topic, and multiple SQS queues subscribe to that topic to receive copies of the message simultaneously.

4. **Explain how “push notifications” work, using SNS.**
   - With SNS push notifications, applications subscribe to topics, and when a message is published to the topic, SNS delivers it to all subscribed endpoints (e.g., mobile devices) in real-time.

5. **How might a large scale, distributed application make use of a Queue system like SQS?**
   - In a large-scale, distributed application, SQS can manage tasks or messages between different components or microservices, ensuring reliable and scalable communication without overwhelming any single part of the system.
