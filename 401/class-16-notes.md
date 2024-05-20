# AWS: Cloud Servers

**What is an EC2 Instance?**

An EC2 instance is a virtual server provided by Amazon Web Services (AWS) that allows you to run applications in the cloud. It gives you scalable computing capacity, meaning you can easily increase or decrease resources as needed.

**Name 2 use cases for EC2.**

1. **Hosting Websites:** EC2 instances can host dynamic websites, handling traffic and scaling according to demand.
2. **Data Processing:** They can be used for processing large datasets, such as running analytics or machine learning models.

**Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.**

ECS provides deeper integration with other AWS services, allowing for more complex and scalable architectures that benefit from AWS's extensive ecosystem.

**Where can we find EC2 on the AWS Console?**

You can find EC2 under the "Compute" section of the AWS Management Console.

**Explain the general difference between T2 Micro and XL.**

A T2 Micro instance offers minimal resources (1 vCPU, 1 GB RAM) suitable for lightweight applications, while an XL instance provides significantly more resources (e.g., 4 vCPUs, 16 GB RAM) for heavier workloads.

**Explain a “Compute Cycle” to a non-technical friend.**

A compute cycle is like the amount of time a computer’s brain spends working on a task; it’s how computers measure the work they do to run programs and process data.

**What is Elastic Beanstalk?**

Elastic Beanstalk is an AWS service that makes it easy to deploy and manage applications by handling the infrastructure and scaling for you, allowing developers to focus on writing code.

**Describe the relationship between EC2 and Elastic Beanstalk.**

Elastic Beanstalk uses EC2 instances to run your applications, automatically managing the EC2 instances and other resources needed to keep your application running smoothly.

**Name some benefits of using Elastic Beanstalk.**

Elastic Beanstalk simplifies the deployment process, handles the infrastructure management automatically, and provides built-in monitoring and scaling capabilities, which can save time and reduce operational complexity for developers.
