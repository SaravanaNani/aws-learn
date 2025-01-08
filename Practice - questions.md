
# Module 1

1. What is cloud computing?
Ans: ```On-demand delivery of IT resources and applications through the internet with pay-as-you-go pricing```

2. What is another name for on-premises deployment?
Ans: ```Private cloud deployment```

3. How does the scale of cloud computing help you to save costs?
Ans: ```The aggregated cloud usage from a large number of customers results in lower pay-as-you-go prices.```

  
# Moudle 2

### Instance Type:

1. Which Amazon EC2 instance type is suitable for data warehousing applications?
Ans: ``` Storage optimized```

2. Which Amazon EC2 instance type balances compute, memory, and networking resources?
Ans: ```General purpose```

3. Which Amazon EC2 instance type is ideal for high-performance databases?
Ans: ```Memory optimized```

4. Which Amazon EC2 instance type offers high-performance processors?
Ans: ```Compute optimized```

5. You want to use an Amazon EC2 instance for a batch processing workload. What would be the best Amazon EC2 instance type to use?
Ans: ```Compute optimized```



### Instance Pricing:

1. Which Amazon EC2 pricing option provides a discount when you specify a number of EC2 instances to run a specific OS, instance family and size, and tenancy in one Region?
Ans: ``` Standard Reserved Instances ```

2. Which Amazon EC2 pricing option provides a discount when you make an hourly spend commitment to an instance family and Region for a 1-year or 3-year term?
Ans: ``` EC2 Instance Savings Plans ```

3. What are the contract length options for Amazon EC2 Reserved Instances? (Select TWO.) Ans ``` 1 year and 3 years```

4. You have a workload that will run for a total of 6 months and can withstand interruptions. What would be the most cost-efficient Amazon EC2 purchasing option?
``` Spot Instance ```

### Auto Scaling:

### Directing Traffic  with Elastic Load Balancer:

1. Which process is an example of Elastic Load Balancing?
Ans: ```Ensuring that no single Amazon EC2 instance has to carry the full workload on its own```

### Messaging and Queuing:

1. Which AWS service is the best choice for publishing messages to subscribers?
Ans: ``` Amazon Simple Notification Service (Amazon SNS)``` 

### Serverless and other computing resources: 

1. You want to deploy and manage containerized applications. Which service should you use?
Ans: ```Amazon Elastic Kubernetes Service (Amazon EKS)```

# Module 3

### Global InfraStructure - High Avvailability:

1. Which statement best describes an Availability Zone?
Ans: ```A single data center or group of data centers within a Region```
2. Which statement is TRUE for the AWS global infrastructure?
Ans: ```A Region consists of three or more Availability Zones.```
3. Which factors should be considered when selecting a Region? (Select TWO.)
Ans: ``` 1-Compliance with data governance and legal requirements
   2-Proximity to your customers```

### Edge locations

An edge location is a site that Amazon CloudFront uses to store cached copies of your content closer to your customers for faster delivery.

1. Which statement best describes Amazon CloudFront?
Ans: ```A global content delivery service ```

2. Which site does Amazon CloudFront use to cache copies of content for faster delivery to users at any location?
Ans: ```Edge location```



### Provision AWS Resources

### Ways to interact with AWS services:
1. AWS Management Console
2.  AWS Command Line Interface (AWS CLI).
3. software development kits (SDKs)
   
### AWS Elastic Beanstalk
### AWS CloudFormation

1. Which action can you perform with AWS Outposts?
Ans: ```Extend AWS infrastructure and services to different locations including your on-premises data center.```

In Module 3, you learned about the following concepts:

AWS Regions and Availability Zones
Edge locations and Amazon CloudFront
The AWS Management Console, AWS CLI, and SDKs
AWS Elastic Beanstalk
AWS CloudFormation

# Module 4 - Amazon Virtual Private Cloud, or VPCs

### Connectivity to AWS

1. Your company has an application that uses Amazon EC2 instances to run the customer-facing website and Amazon RDS database instances to store customers’ personal information. How should the developer 
   configure the VPC according to best practices?

   Ans: ```Place the Amazon EC2 instances in a public subnet and the Amazon RDS database instances in a private subnet.```

2. Which component can be used to establish a private dedicated connection between your company’s data center and AWS?
Ans: ```AWS Direct Connect```

3. Which component is used to connect a VPC to the internet?
Ans: ```Internet gateway```

### Subnets and Network Access Control Lists 

1. Which statement best describes an AWS account’s default network access control list?
Ans: ```It is stateless and allows all inbound and outbound traffic```

2. Which statement best describes security groups?
Ans: ```They are stateful and deny all inbound traffic by default.```


   
### Global Networking

1. Which statement best describes DNS resolution?
Ans: ```Translating a domain name to an IP address```

2. Which service is used to manage the DNS records for domain names?
Ans" ```Amazon Route 53```



In Module 4, you learned about the following concepts:

-> Structuring and connecting to a VPC

-> Securing VPC resources with network access control lists and security groups

-> Using Amazon Route 53 and Amazon CloudFront to deliver content
