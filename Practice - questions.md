
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


# Module 5: Storage and Data Base:

### Instance Stores and Amazon Elastic Block Store (Amazon EBS):

1. Which of the following are characteristics of the Amazon EBS service? (Select TWO.)
Ans: ```Best for data that requires retention and
Separate drives from the host computer of an EC2 instance```

2. Which statement or statements are TRUE about Amazon EBS volumes and Amazon EFS file systems?
Ans: ```EBS volumes store data within a single Availability Zone. Amazon EFS file systems store data across multiple Availability Zones.```


### Amazon Simple Storage Service (Amazon S3)

1. You want to store data that is infrequently accessed but must be immediately available when needed. Which Amazon S3 storage class should you use?
Ans: ```S3 Standard-IA```

2. Which Amazon S3 storage classes are optimized for archival data? (Select TWO.)
Ans: ``` Amazon S3 Glacier Flexible Retrieval and
Amazon S3 Glacier Deep Archive```

3. You want to store data in an object storage service. Which AWS service is best for this type of storage?
Ans: ``` mazon Simple Storage Service (Amazon S3)```


### Amazon Elastic File System (Amazon EFS)

### Amazon Relational Database Service (Amazon RDS): 

```Amazon Relational Database Service (Amazon RDS)(opens in a new tab) is a service that enables you to run relational databases in the AWS Cloud.```

1. What are the scenarios in which you should use Amazon Relational Database Service (Amazon RDS)? (Select TWO.)
Ans: ```
Using SQL to organize data
Storing data in an Amazon Aurora database ```


### Amazon DynamoDB

```Amazon DynamoDB(opens in a new tab) is a key-value database service. It delivers single-digit millisecond performance at any scale.```

DynamoDB is serverless: which means that you do not have to provision, patch, or manage servers. 
You also do not have to install, maintain, or operate software.

Automatic scaling: As the size of your database shrinks or grows, DynamoDB automatically scales to adjust for changes in capacity while maintaining consistent performance. 
This makes it a suitable choice for use cases that require high performance while scaling.


1. Which statement best describes Amazon DynamoDB?
Ans: ``` A serverless key-value database service```

### Amazon Redshift

```Amazon Redshift(opens in a new tab) is a data warehousing service that you can use for big data analytics. It offers the ability to collect data from many sources and helps you to understand relationships and trends across your data```

1. Which service is used to query and analyze data across a data warehouse?
Ans: ```Amazon Redshift```


### AWS Database Migration Service

``` AWS Database Migration Service (AWS DMS)(opens in a new tab) enables you to migrate relational databases, nonrelational databases, and other types of data stores```

With AWS DMS, you move data between a source database and a target database. The source and target databases(opens in a new tab) can be of the same type or different types. During the migration, your source database remains operational, reducing downtime for any applications that rely on the database. 

### Additional database services:

```Amazon DocumentDB``` is a document database service that supports MongoDB workloads.

```Amazon Neptune``` is a graph database service. 

```Amazon Quantum Ledger Database (Amazon QLDB)``` is a ledger database service. 

```Amazon Managed Blockchain``` is a service that you can use to create and manage blockchain networks with open-source framework

```Amazon ElastiCache``` is a service that adds caching layers on top of your databases to help improve the read times of common requests. 

```Amazon DynamoDB ```Accelerator (DAX) is an in-memory cache for DynamoDB. 



### In Module 5, you learned about the following concepts:

Amazon EC2 instance store and Amazon EBS

Amazon S3

Amazon EFS

Relational databases and Amazon RDS

Nonrelational databases and DynamoDB

Amazon Redshift
AWS DMS
Additional database services and accelerators

# Module 6: Security

### The AWS shared responsibility model: 

```Customer: Security in cloud ``` - Customers are responsible for the security of everything that they create and put in the AWS Cloud.
When using AWS services, you, the customer, maintain complete control over your content. You are responsible for managing security requirements for your content, including which content you choose to store on AWS, which AWS services you use, and who has access to that content. You also control how access rights are granted, managed, and revoked.

```AWS: Security of the cloud``` - AWS is responsible for security of the cloud: AWS operates, manages, and controls the components at all layers of infrastructure.
This includes areas such as the host operating system, the virtualization layer, and even the physical security of the data centers from which services operate. 

1. Which tasks are the responsibilities of customers? (Select TWO.)
Ans: ```Patching software on Amazon EC2 instances and Setting permissions for Amazon S3 objects```

### User Permissions and Acces: AWS Identity and Access Management (IAM)

```IAM users``` - An IAM user is an identity that you create in AWS. It represents the person or application that interacts with AWS services and resources. It consists of a name and credentials.

```IAM group``` -  An IAM group is a collection of IAM users. When you assign an IAM policy to a group, all users in the group are granted permissions specified by the policy.

```IAM Roles``` - An IAM role is an identity that you can assume to gain temporary access to permissions.
                  IAM roles are ideal for situations in which access to services or resources needs to be granted temporarily, instead of long-term.  

```IAM policies ```- An IAM policy is a document that allows or denies permissions to AWS services and resources

```Multi-factor authentication``` - In IAM, multi-factor authentication (MFA) provides an extra layer of security for your AWS account.


1.Which statement best describes an IAM policy?
Ans: ```A document that grants or denies permissions to AWS services and resources```

2. An employee requires temporary access to create several Amazon S3 buckets. Which option would be the best choice for this task?
Ans: ``` IAM Role```

3. Which statement best describes the principle of least privilege?
Ans: ``` Granting only the permissions that are needed to perform specific tasks```

### AWS Organizations & Organizational units:

1. You are configuring service control policies (SCPs) in AWS Organizations. Which identities and resources can SCPs be applied to? (Select TWO.)
Ans: ``` An individual member account and 
An organizational unit (OU)```

### Compliance

```AWS Artifact``` - AWS Artifact(opens in a new tab) is a service that provides on-demand access to AWS security and compliance reports and select online agreements. 
                      AWS Artifact consists of two main sections: AWS Artifact Agreements and AWS Artifact Reports

```` AWS Artifact Agreements```` - In AWS Artifact Agreements, you can review, accept, and manage agreements for an individual account and for all your accounts in AWS Organizations. Different types of agreements are offered to address the needs of customers who are subject to specific regulations, such as the Health Insurance Portability and Accountability Act (HIPAA).

```AWS Artifact Reports``` - AWS Artifact Reports provide compliance reports from third-party auditors. 
These auditors have tested and verified that AWS is compliant with a variety of global, regional, and industry-specific security standards and regulations.
AWS Artifact Reports remains up to date with the latest reports released. You can provide the AWS audit artifacts to your auditors or regulators as evidence of AWS security controls. 

```Customer Compliance Center```- The Customer Compliance Center contains resources to help you learn more about AWS compliance. 

1. Which tasks can you complete in AWS Artifact? (Select TWO.)
Ans: ```Access AWS compliance reports on-demand. and
Review, accept, and manage agreements with AWS.```

### Denial-of-service attacks: A denial-of-service (DoS) attack is a deliberate attempt to make a website or application unavailable to users.

```AWS Shield``` - AWS Shield is a service that protects applications against DDoS attacks. AWS Shield provides two levels of protection: Standard and Advanced.
```AWS Shield Standard``` - automatically protects all AWS customers at no cost. It protects your AWS resources from the most common, frequently occurring types of DDoS attacks. 
```AWS Shield Advanced``` - is a paid service that provides detailed attack diagnostics and the ability to detect and mitigate sophisticated DDoS attacks. 

1. Which service helps protect your applications against distributed denial-of-service (DDoS) attacks?
Ans: ```AWS Shield```

### Additional Security Services:

```AWS Key Management Service (AWS KMS)``` - enables you to perform encryption operations through the use of cryptographic keys
```AWS WAF``` - AWS WAF is a web application firewall that lets you monitor network requests that come into your web applications.
```Amazon Inspector``` 
```Amazon GuardDuty```

1. Which task can AWS Key Management Service (AWS KMS) perform?
Ans: ``` Create cryptographic keys.```


### In Module 6, you learned about the following concepts:

The shared responsibility model

Features of AWS Identity and Access Management

Methods of managing multiple accounts in AWS Organizations

AWS compliance resources

AWS services for application security and encryption

# Module 7 - Monitoring and Analytics

### Amazon CLoud Watch

```Amazon CloudWatch``` is a web service that enables you to monitor and manage various metrics and configure alarm actions based on data from those metrics.
CloudWatch uses metrics to represent the data points for your resources. AWS services send metrics to CloudWatch.
CloudWatch then uses these metrics to create graphs automatically that show how performance has changed over time. 

```CloudWatch alarms``` With CloudWatch, you can create alarms(opens in a new tab) that automatically perform actions if the value of your metric has gone above or below a predefined threshold. 
The ```CloudWatch dashboard``` feature enables you to access all the metrics for your resources from a single location


1. Which actions can you perform using Amazon CloudWatch? (Select TWO.)
Ans: ```Monitor your resources’ utilization and performance and
Access metrics from a single dashboard```


### AWS CloudTrail

```AWS CloudTrail```records API calls for your account.
you can use API calls to provision, manage, and configure your AWS resources. With CloudTrail, you can view a complete history of user activity and API calls for your applications and resources. 
Events are typically updated in CloudTrail within 15 minutes after an API call.

``` CloudTrail Insights``` - you can also enable ``` CloudTrail Insights``` This optional feature allows CloudTrail to automatically detect unusual API activities in your AWS account. 

1. Which tasks can you perform using AWS CloudTrail? (Select TWO.)
Ans: ```Track user activities and API requests throughout your AWS infrastructure 
Filter logs to assist with operational analysis and troubleshooting```

### AWS Trusted Advisor

```AWS Trusted Advisor``` - is a web service that inspects your AWS environment and provides real-time recommendations in accordance with AWS best practices.
Trusted Advisor compares its findings to AWS best practices in five categories: cost optimization, performance, security, fault tolerance, and service limits.

```AWS Trusted Advisor dashboard``` - When you access the Trusted Advisor dashboard on the AWS Management Console, 
you can review completed checks for cost optimization, performance, security, fault tolerance, and service limits.

For each category:

The ```green check ```indicates the number of items for which it detected ```no problems```.

The ```orange triangle ``` represents the number of ```recommended investigations```.

The ```red circle ```represents the ```number of recommended actions.```



1. Which service enables you to review the security of your Amazon S3 buckets by checking for open access permissions?
Ans: ``` AWS Trusted Advisor```

2. Which categories are included in the AWS Trusted Advisor dashboard? (Select TWO.)
Ans: ```Performance and Fault tolerance```



### In Module 7, you learned about the following concepts:

Amazon CloudWatch
AWS CloudTrail
AWS Trusted Advisor


# Module 8 - Billing 


### AWS Free Tier

The AWS Free Tier enables you to begin using certain services without having to worry about incurring costs for the specified period. 

Three types of offers are available: -> 

```Always Free``` - These offers do not expire and are available to all AWS customers.

```For example```- AWS Lambda allows 1 million free requests and up to 3.2 million seconds of compute time per month. Amazon DynamoDB allows 25 GB of free storage per month.


```12 Months Free``` - These offers are free for 12 months following your initial sign-up date to AWS.

``` For Example``` include specific amounts of Amazon S3 Standard Storage, thresholds for monthly hours of Amazon EC2 compute time, and amounts of Amazon CloudFront data transfer out.


``` Trials``` - Short-term free trial offers start from the date you activate a particular service. The length of each trial might vary by number of days or the amount of usage in the service.

```For example``` Amazon Inspector offers a 90-day free trial.

### Quiz:

1. The AWS Free Tier includes offers that are available to new AWS customers for a certain period of time following their AWS sign-up date. What is the duration of this period?

Ans: ``` 12 Months```


### AWS Pricing Concepts

```AWS Pricing Calculator``` - lets you explore AWS services and create an estimate for the cost of your use cases on AWS.
You can organize your AWS estimates by groups that you define. A group can reflect how your company is organized, such as providing estimates by cost center.


### Billing Dashboard

-> Use the``` AWS Billing & Cost Management dashboard``` to pay your AWS bill, monitor your usage, and analyze and control your costs.

-> Compare your current month-to-date balance with the previous month, and get a forecast of the next month based on current usage.

-> View month-to-date spend by service.

-> View Free Tier usage by service.

-> Access Cost Explorer and create budgets.

-> Purchase and manage Savings Plans.


### Consolidated Billing

The ```consolidated billing feature ```of AWS Organizations enables you to receive a single bill for all AWS accounts in your organization. 
By consolidating, you can easily track the combined costs of all the linked accounts in your organization.
The default maximum number of accounts allowed for an organization is 4, but you can contact AWS Support to increase your quota, if needed.


### AWS Budgets
In ``` AWS Budgets``` you can create budgets to plan your service usage, service costs, and instance reservations.
In AWS Budgets, you can also set custom alerts when your usage exceeds (or is forecasted to exceed) the budgeted amount.

### AWS Cost Explorer

```AWS Cost Explorer```is a tool that lets you visualize, understand, and manage your AWS costs and usage over time.



### AWS Support Plans

AWS offers four different Support plan to help you troubleshoot issues, lower costs, and efficiently use AWS services. 

You can choose from the following Support plans to meet your company’s needs: 

-> Basic : ``` Basic Support``` is free for all AWS customers. It includes access to whitepapers, documentation, and support communities. With Basic Support, you can also contact AWS for billing questions and service limit increases.

-> Developer - Business - Enterprise On-Ramp - Enterprise : The Developer, Business, Enterprise On-Ramp, and Enterprise Support plans include all the benefits of Basic Support,
in addition to the ability to open an unrestricted number of technical support cases. These Support plans have pay-by-the-month pricing and require no long-term contracts.

```Technical Account Manager (TAM)``` - The Enterprise On-Ramp and Enterprise Support plans include access to a Technical Account Manager (TAM).

The TAM is your primary point of contact at AWS. If your company subscribes to Enterprise Support or Enterprise On-Ramp, your TAM educates, empowers, and evolves your cloud journey across the full range of AWS services. 


### AWS Marketplace

```AWS Marketplace``` is a digital catalog that includes thousands of software listings from independent software vendors. You can use AWS Marketplace to find, test, and buy software that runs on AWS. 

AWS Marketplace offers products in several categories, such as Infrastructure Software, DevOps, Data Products, Professional Services, Business Applications, Machine Learning, Industries, and Internet of Things (IoT).

# Quiz:


1. Which pricing tool is used to visualize, understand, and manage your AWS costs and usage over time?
Ans: ``` AWS Cost Explorer```

2. Which pricing tool enables you to receive alerts when your service usage exceeds a threshold that you have defined?
Ans: ``` AWS Budegets```

3. Which Support plan includes all AWS Trusted Advisor checks at the lowest cost?
Ans: ```Business```

4. Your company wants to receive support from an AWS Technical Account Manager (TAM). Which support plan should you choose?
Ans: ```Enterprise```

5. Which action can you perform with consolidated billing?
Ans: ```Combine usage across accounts to receive volume pricing discounts.```

6. Which service or resource is used to find third-party software that runs on AWS?
Ans: ```AWS Market Place```


### In Module 8, you learned about the following concepts:

Three types of offers included in the AWS Free Tier: 12 months free, Always free, and Trials

Benefits of consolidated billing in AWS Organizations

Tools for planning, estimating, and reviewing AWS costs

Differences between the five AWS Support plans: Basic, Developer, Business, Enterprise On-Ramp, and Enterprise

How to discover software in AWS Marketplace


# Module-9 Migration and Innovation

### AWS Cloud Adoption Framework (AWS CAF)

Six core perspectives of the Cloud Adoption Framework: Each Perspective addresses distinct responsibilities. 

The planning process helps the right people across the organization prepare for the changes ahead.

In general, the Business, People, and Governance Perspectives focus on business capabilities, whereas the Platform, Security, and Operations Perspectives focus on technical capabilities.


```Business Perspective ```ensures that IT aligns with business needs and that IT investments link to key business results.

Common roles in the Business Perspective include: 

                                Business managers

                                Finance managers

                                Budget owners

                                Strategy stakeholders  

```People Perspective``` supports development of an organization-wide change management strategy for successful cloud adoption.

Common roles in the People Perspective include: 

                                Human resources

                                Staffing

                                People managers

```Governance Perspective``` focuses on the skills and processes to align IT strategy with business strategy. This ensures that you maximize the business value and minimize risks.

Common roles in the Governance Perspective include: 

                                Chief Information Officer (CIO)

                                Program managers

                                Enterprise architects

                                Business analysts

                                Portfolio managers
                                
```Platform Perspective``` includes principles and patterns for implementing new solutions on the cloud, and migrating on-premises workloads to the cloud.

Common roles in the Platform Perspective include: 

                                Chief Technology Officer (CTO)
      
                                IT managers
                    
                                Solutions architects

```Security Perspective ``` ensures that the organization meets security objectives for visibility, auditability, control, and agility.

Common roles in the Security Perspective include: 

                              Chief Information Security Officer (CISO)

                              IT security managers
                              
                              IT security analysts 

```Operations Perspective``` helps you to enable, run, use, operate, and recover IT workloads to the level agreed upon with your business stakeholders.

Common roles in the Operations Perspective include: 

                              IT operations managers

                              IT support managers


1. Which Perspective of the AWS Cloud Adoption Framework helps you design, implement, and optimize your AWS infrastructure based on your business goals and perspectives?
Ans: ```Platform Perspective```

### Migration Strategies

### 6 - strategies for migration:

When migrating applications to the cloud, six of the most common migration strategies that you can implement are:

```Rehosting``` - Rehosting also known as “lift-and-shift” involves moving applications without changes.

```Replatforming ```- Replatformingalso known as “lift, tinker, and shift,” involves making a few cloud optimizations to realize a tangible benefit. Optimization is achieved without changing the core a 
  architecture of the application.

```Refactoring/re-architecting ```- Refactoring (also known as re-architecting) involves reimagining how an application is architected and developed by using cloud-native features. 
Refactoring is driven by a strong business need to add features, scale, or performance that would otherwise be difficult to achieve in the application’s existing environment.

```Repurchasing``` - Repurchasing involves moving from a traditional license to a software-as-a-service model. 

```Retaining``` - Retaining consists of keeping applications that are critical for the business in the source environment.

```Retiring``` - is the process of removing applications that are no longer needed.

#Question 


1. Which migration strategy involves moving to a different product?
Ans: ```Repurchasing```

### AWS Snow Family

The ```AWS Snow Family``` is a collection of physical devices that help to physically transport up to exabytes of data into and out of AWS.

AWS Snow Family is composed of ```AWS Snowcone``` - ```AWS Snowball``` and ```AWS Snowmobile```


```AWS Snowcone``` is a small, rugged, and secure edge computing and data transfer device. 

It features 2 CPUs, 4 GB of memory, and up to 14 TB of usable storage.

```AWS Snowballoffers``` two types of devices:

    1. Snowball Edge Storage Optimized - devices are well suited for large-scale data migrations and recurring transfer workflows, in addition to local computing with higher capacity needs. 
    
    -> Storage: 80 TB of hard disk drive (HDD) capacity for block volumes and Amazon S3 compatible object storage, and 1 TB of SATA solid state drive (SSD) for block volumes.
    -> Compute: 40 vCPUs, and 80 GiB of memory to support Amazon EC2 sbe1 instances (equivalent to C5).


    
    2. Snowball Edge Compute Optimized - provides powerful computing resources for use cases such as machine learning, full motion video analysis, analytics, and local computing stacks. 

    -> Storage: 80-TB usable HDD capacity for Amazon S3 compatible object storage or Amazon EBS compatible block volumes and 28 TB of usable NVMe SSD capacity for Amazon EBS compatible block volumes. 

    -> Compute: 104 vCPUs, 416 GiB of memory, and an optional NVIDIA Tesla V100 GPU. Devices run Amazon EC2 sbe-c and sbe-g instances, which are equivalent to C5, M5a, G3, and P3 instances.


```AWS Snowmobile``` - is an exabyte-scale data transfer service used to move large amounts of data to AWS. 

You can transfer up to 100 petabytes of data per Snowmobile, a 45-foot long ruggedized shipping container, pulled by a semi trailer truck.


1. What is the storage capacity of Snowball Edge Storage Optimized?
Ans: ```80TB```

### Innovation with AWS

```AWS serverless ```- refers to applications that don’t require you to provision, maintain, or administer servers. You don’t need to worry about fault tolerance or availability. AWS handles these capabilities for you.

AWS offers a variety of services powered by ```artificial intelligence (AI)```. 

For example, you can perform the following tasks:

    Convert speech to text with Amazon Transcribe.
    
    Discover patterns in text with Amazon Comprehend.
    
    Identify potentially fraudulent online activities with Amazon Fraud Detector.
    
    Build voice and text chatbots with Amazon Lex.
    
```Traditional machine learning (ML)``` development is complex, expensive, time consuming, and error prone. AWS offers Amazon SageMaker to remove the difficult work from the process and empower you to build, train, and deploy ML models quickly.

```Amazon Q Developer``` - Amazon Q Developer is a machine learning-powered code generator that provides you with code recommendations in real time.

As you write code, ```Amazon Q Developer ``` analyzes your code and comments as you write code in your integrated development environment (IDE). Amazon Q Developer then automatically generates suggestions based on your existing code and comments.

1. Which service enables you to quickly build, train, and deploy machine learning models?
Ans: ``` Amazon SageMaker```

# Quiz:

1. Which Perspective of the AWS Cloud Adoption Framework helps you structure the selection and implementation of permissions?
Ans: ```Security Perspective```

2. Which strategies are included in the six strategies for application migration? (Select TWO.)
Ans: ```Retaining and Rehosting```

3. What is the storage capacity of AWS Snowmobile?
Ans: ```100 PB```

4. Which statement best describes Amazon Lex?
Ans: ```A service that enables you to build conversational interfaces using voice and text```


### In Module 9, you learned about the following concepts:

The AWS Cloud Adoption Framework
The six strategies for migration
The AWS Snow Family
Innovation with AWS services



# Module 10 


###The AWS Well-Architected Framework

The ```AWS Well-Architected Framework``` helps you understand how to design and operate reliable, secure, efficient, and cost-effective systems in the AWS Cloud. 

The Well-Architected Framework is based on six pillars: 

      Operational excellence
      
      Security
      
      Reliability
      
      Performance efficiency

      Cost optimization

      Sustainability

```Operational excellence``` is the ability to run and monitor systems to deliver business value and to continually improve supporting processes and procedures.  

```Security pillar``` is the ability to protect information, systems, and assets while delivering business value through risk assessments and mitigation strategies. 

```Reliability ```is the ability of a system to do the following:

    Recover from infrastructure or service disruptions
    
    Dynamically acquire computing resources to meet demand
    
    Mitigate disruptions such as misconfigurations or transient network issues


```Performance efficiency``` is the ability to use computing resources efficiently to meet system requirements and to maintain that efficiency as demand changes and technologies evolve. 

```Cost optimization``` is the ability to run systems to deliver business value at the lowest price point. 

```Sustainability``` is the ability to continually improve sustainability impacts by reducing energy consumption and increasing efficiency across all components of a workload by maximizing the benefits from the provisioned resources and minimizing the total resources required.

### Benefits of the AWS Cloud

```Advantages of cloud computing``` - Operating in the AWS Cloud offers many benefits over computing in on-premises or hybrid environments. 

In this section, you will learn about six advantages of cloud computing:

    Trade upfront expense for variable expense.

    Benefit from massive economies of scale.

    Stop guessing capacity.

    Increase speed and agility.

    Stop spending money running and maintaining data centers.

    Go global in minutes.

# Quiz:

1. Which pillar of the AWS Well-Architected Framework includes the ability to run workloads effectively and gain insights into their operations?
Ans:``` Operational Excellence```


2. Which pillar of the AWS Well-Architected Framework focuses on the ability of a workload to consistently and correctly perform its intended functions?
Ans: ```Reliability```

3. What are the benefits of cloud computing? (Select TWO.)
Ans: ``` Increase speed and agility and
Stop spending money running and maintaining data centers```

4. Which process is an example of benefiting from massive economies of scale?
Ans: ```Receiving lower pay-as-you-go prices as the result of AWS customers’ aggregated usage of services```

### In Module 10, you learned about the following concepts:

### The six pillars of the AWS Well-Architected Framework:

Operational excellence

Security

Reliability

Performance efficiency

Cost optimization

Sustainability

### Six advantages of cloud computing:

Trade upfront expense for variable expense.

Benefit from massive economies of scale.

Stop guessing capacity.

Increase speed and agility.

Stop spending money running and maintaining data centers.

Go global in minutes.


# Module 11 - Learning objectives

Exam domains

The AWS Certified Cloud Practitioner exam includes four domains:

1 - Cloud Concepts - 24%

2 - Security and Compliance - 30%

3 - Technology - 34%

4 - Billing and Pricing - 12%

# Final Assessment - Quiz:

1. Which tool provides automation actions for AWS services and applications through scripts?
Ans: ``` Command Line Interface ```

2. A cloud engineer wants to store data in a volume that is attached to an Amazon EC2 instance. Which service should they use?
Ans: ```Amazon Elastic Block Store (Amazon EBS)```

3. Which tool provides the capability to visualize, understand, and manage AWS costs and usage over time?
Ans: ```AWS Cost Explorer```

4. Which statement best describes AWS Marketplace?
Ans: ```  A digital catalog that includes thousands of software listings from independent software vendors```

5. An application developer wants to send and receive messages between distributed application components. Which service should they use?    
Ans: ```Amazon Simple Queue Service (Amazon SQS)```

6.  Which Amazon EC2 pricing option reduces costs when a business makes an hourly spend commitment to an instance family and Region for a 1-year or 3-year term?
Ans: ``` EC2 Instance Savings Plans```

7.  Which tasks are the responsibilities of AWS? (Select TWO.)
Ans: ```Maintaining virtualization infrastructure and
Configuring AWS infrastructure devices```

8. Which action can a person perform in Amazon CloudFront?
Ans: ```Deliver content to customers through a global network of edge locations.```

9. Which service runs containerized applications on AWS?
 Ans: ```Amazon Elastic Kubernetes Service (Amazon EKS)```

10. Which actions can a person perform in Amazon Route 53? (Select TWO.)
Ans: ```Connect user requests to infrastructure in AWS and outside of AWS and
Manage DNS records for domain names.```

11. Which statement best describes Amazon GuardDuty?
Ans: ```A service that provides intelligent threat detection for AWS infrastructure and resources```

12. Which statement best describes an Availability Zone?
Ans: ```A fully isolated portion of the AWS global infrastructure```

13. Which statement best describes Elastic Load Balancing?
Ans: ``` A service that distributes incoming traffic across multiple targets, such as Amazon EC2 instances```

14.  Which Perspective of the AWS Cloud Adoption Framework focuses on recovering IT workloads to meet the requirements of business stakeholders?
Ans: ```Operations Perspective```

15. Which service consolidates and manages multiple AWS accounts from a central location?
Ans: ```AWS Organizations```

16. Which Support plans include access to all AWS Trusted Advisor checks? (Select TWO.)
Ans: ```Business and Enterprise```

17. Which service provides review details for user activities and API calls that have occurred within an AWS environment?
Ans: ```AWS CloudTrail```

18. An application developer wants to store data in a key-value database. Which service should they use?
Ans: ```Amazon DynamoDB```

19. Which migration strategy involves changing how an application is architected and developed, typically by using cloud-native features?
Ans: ```Refactoring```

20. Which statement is TRUE for AWS Lambda?
Ans: ```Businesses pay only for compute time while their code is running.```

21. Which service provides the capability to quickly deploy and scale applications on AWS?
Ans: ```AWS Elastic Beanstalk```

22. Which service is used to transfer up to 100 PB of data to AWS?
Ans: ```AWS Snowmobile```

23. Which component or service establishes a dedicated private connection between an on-premises data center and virtual private cloud (VPC)?
Ans: ```AWS Direct Connect```

24. A cloud engineer is running an Amazon EC2 instance and wants to store data in an attached resource. Their data is temporary and will not be kept long term. Which resource should they use?
Ans: ```Instance store```

25. Which pillar of the AWS Well-Architected Framework focuses on using computing resources in ways that meet system requirements?
Ans: ```Performance Efficiency```

26. Which service builds the workflows that are required for human review of machine learning predictions?
Ans: ```Amazon Augmented AI```

27. A cloud architect wants Amazon S3 to monitor object access patterns. Which storage class should they use? 
Ans: ```Amazon S3 Intelligent-Tiering```

28. In the S3 Intelligent-Tiering storage class, Amazon S3 moves objects between a frequent access tier and an infrequent access tier. Which storage classes are used for these tiers? (Select TWO.)
Ans: ```S3 Standard and S3 Standard - IA```

29. Which virtual private cloud (VPC) component controls inbound and outbound traffic for Amazon EC2 instances?
Ans: ```Security group```

30. Which AWS Trusted Advisor category includes checks for high-utilization EC2 instances?
Ans: ```Performance```
