# AWS Cloud Practicioner Exam Prep

## What is Cloud Computing:
- The practice of using a network of remote servers hosted on the internet to store, managem and process data rather than a local server of personal computing

**Dedicated Server**: One machine, single business. Very expensive, high maintenence, high security

**Virtual Private Server**: One machine, single business, machine virtualized into sub machines. Better utilization and isolation of resources

**Shared Hosting**: One machine, hundreds of businesses. Relies on tenants under-utilizing. Cheap, limited funt, poor isolation

**Cloud Hosting**: Multiple machines that act as one, cloud services. Flexible, scalable, secure, cost effective, high configurability

## What is Amazon:

American multinational computer tech corp headed in Seattle Washington. Founded in 1994 by Jeff Bezos and the company was started as an online store for books and it expanded to other products.

Expanded beyond this and expanded into cloud computing, digital streaming, grocery stores, AI, Low orbit satellites, etc.

## What is AWS
AWS is Amazon Web Services. It is a collection of cloud services unified under one interface that can be used to create a lot of different types of workloads.

CSP: Cloud Service Provider

The first service was published in 2004. It was known as SQS. Then S3 or simple storage service. Then EC2 was launched in August (Most commonly used.) In 2010 all of Amazons retail sites was migrated to it. The current CEO is Adam Selipsky.

## What is a CSP: Cloud Service Provider:

A CSP is a company that provides
- Multiple CLoud Services
- Services can be chained together to make cloud architecture
- Accessible via single unified APO
- utilize mtered billing
- rich monitorung built in
- Infrastructure as a Service (IaaS) offering
- offers automation as Infrastructire as Code (IaC)

If all these are not met then it is just a cloud platform and not a CSP

## Landscape of CSPs
Has tiers: 
- Tier 1: Early to market, wide offering, strong synergy, well recognized in industry. Ex: AWS, Microsoft Azure, Google Cloud Platform (GCP), Alibaba Cloud (Primarily only used in China)
- Tier 2: Backed by well-known companies, but they are slow to innovate and turned to specialization. IBM Cloud, Oracle Cloud, Rackspace (OpenStack)
-  Tier 3 (light tier): Virtual Private Servers (VPS) turned to offer core IaaS offering. Simple, cost effective. Vultr, Difital Ocean, Linode
-  

## Gartner Magic Quadrant for Cloud

Magic Quadrant (MQ) is a series of market research reports published by IT consulting firm Gartbner that rely on proprietary qualitative data analysis methods to demonstrate market trends such as direction, maturity and participants.

## Common Cloud Services

Can have hundreds of cloud services. Core includes:
- Compute: Virtual computer that can run app, programs, and code
- Networking
- Storage
- Databases

AWS has 200+ cloud services

## AWS tech overview

CSPs that are IaaS will always have 4 core cloud service offerings:

For AWS:
- Compute: EC2
- Storage: EBS Virtual Hard Drives
- Database: RDS SQL Database
- Networking: VPC Private CLoud Network

AWS has many other offerings

## Evolution of Computing
 (Most to least wasted space?)
Dedicated -> VMs -> Containers -> Functions

Dedicated: Physical server wholly utilized by a single customer. You have to guess capacity, you'll overpay for an underutilized server, can't vertical scale, replacing a server is difficult, limited by Host OS, Multiple apps can result in conflicts in resource sharing, benefits: guarentee of security, privacy, and full utility of underlying resources.

Virtual Machines: Can run mult Virtual Machines on one machine, physical server shared by multiple customers, pay a fraction of a server, pay for an underutilized VM, limited by guest OS, Mult apps on a VM can result in issues. ***HyperVisor** is the software layer that lets you run the VMs* Easy to export or import umages for migration, easy to scale horzontally or vertically.


Containers: VM running multiple containers. ***Docker Deamon** is the name of the software later that lets you run mult containers*. Can  maximize the util of the availabile capacity which is more cost effective, share underlying OS, Multiple apps can run side by side w/o worrying of OS req . No conflict during resource sharing

Functions: Are managed VMs running managed containers. Known as Serverless Compute, Upload piece of code, choose mem and duration, Only responsible for cde and data, very cost effective. Cold starts is a side effect, may take time to start up

## Types of Cloud Computing

SaaS: Software as a Service (For customers)
- A product that is run and managed by the service provider. Don't worry about how service is maintained it just works and remains available: Gmail, Office 365

PaaS: Platform as a Service (For Developers)
- Focus on deployment and management of your apps. Don't worry about provicioning, configuring, or understanding the hardware or OS. Ex. Heroku

IaaS: Infrastructure as a Service
- Basic building blocks for cloud IT. Provides access to networking features, computers, and data storage space. Don't worry about IT staff, data centers, and hardware. Ex. AWS, Microsoft Azure, Oracle Cloud.

## CLoud Computing Deployment Models:

Public Cloud: Everything is built on the CSP. Also known as Cloud-Native or Cloud First

Private Cloud: Everything is built on company's datacenters. Also known as on-premise. The cloud could be OpenStack

Hybrid: Using both On-Premise and a Cloud Service Provider

Cross-Cloud: Using multiple Cloud Providers. AKA multi-cloud

## Deployment Model Use Cases:

Cloud: Startups, SaaS offerings, new projects and companies.

Hybrid: Orgs that started with their own datacenter, but can't fully move to a cloud due to effort of migration or security compliance. Ex. Banks, Fintech

On-Premise: Orgs that cant run on cloud due to strict regulatory compliance or sheer size of org. Ex. Govs and hospitals

## Innovation Waves

Kondratiev waves are hypothesized cycle-like phenomena in the global world economy. The phenomenon is closely connected with Technology life cycles.

Each wave irreversibly changes the society on a global scale. The latest wave is cloud technology

Burning Platform - Company abandons old technology for new tech.  

Digital Tranformation checklist: checklist which helps in transitioning to using AWS.

## Evolution of Computing Power

Computing Power - the throughput at which a computer can complete a computational task

## Benefits of Cloud

- Agility
- Pay-as-you-go pricing
- Economy of sclae
- Global reach
- Security
- Reliability
- High Availability
- Scalability
- Elasticity

## Six Advantages to Cloud

1. Trade capital expense for variable expense: Pay on demand and pay for only what you use
2. Benefit from massive economes of sale
3. Stop guessing capacity
4. Increased speed and agility
5. Stop spending money on running and maintaining data centers
6. Go global in minutes

## Seven Advantages to Cloud (Modern version of prev)

1. Cost Effective: Pay what you consume
2. Global: Launch anywhere in world
3. Secure
4. Reliable
5. Scalable
6. Elastic: automate scaling
7. Current: Hardware/Software issues patched and upraded regularly

## AWS Global Infrastructure Interview

What is it: globally distributed hardware and datacenters that are physically networked together to act as one large resource

Madu up of: 
- 25 regions
- 81 availability zones
- 108 direct connection locations
- 275+ points of presence
- 11 local zones
- 17 wavelength zones

## AWS Well Architected Framework

5 Pillars:
- Operational Excellence: Run and monitor systems (automated)
- Security: Protect data and systems
- Reliablilty: Mitigate and recover from disruptions
- Performance Efficiency: Efficient use of resources
- Cost Optimization: Get lowest price.

## Operational Excellence Pillar

- Perform Operations as Code
  - Limit human error, enable automation, improve response time
- Make small, frequent, reversible changes
  - Don't overhaul entire application in a couple changes. Test changes on certain components so you ca update them regularly
- Anticipate failure
  - When things break analyze the cause and learn from it, write test code that is designed to break your architecture so you can test recovery.
- Refine operational procedures frequently
  - Draw on past events to find continuous opportunities to improve your operations.

## Security Pillar

- Implement a strong identity foundation: centralize identities and implement principle of least priviledge
- Enable traceability which helps monitor actions and changes to your environment in real time
- Automate security best practices
- Protect data in transit and at rest
- Keep people away from data
- Anticipate security events to automate recovery

## Reliability Pillar

- Automatically recover from failure: Monitor KPI's and trigger automation
- Test recovery procedures: Simulate failures to prove recovery procedures
- Scale horizontally to increase availability: Replace one large resource with multiple small resources to reduce the impact of a single failure
- Stop guessing capacity
- Manage change via automation

## Performance Efficiency Pillar

- Democratize advanced technology
- Go global in minutes
- Utilize serverless architecture
- Experiment often: To find the best fit for project

## Cost Optimization Pillar
- Implement Cloud Financial Management
- Adopt a consumption model: Pay only for what you use
- Measure Overall efficiency
- Stop spending money on heavy lifting: Let AWS take care of it
- Analyze and attribute expenditure: Measure your ROI and act accordingly

## 5 Tenets of AWS architecture

To deliver the best possible customer experience, your AWS workloads should adhere to the following tenets
- High Availability: eliminate single points of failure
- Scalability: Add or remove resources on demand
- Elasticity: Automate workloads
- Fault Tolerance: Handle falures well
- High Durability: Recover from failures well

## High Availability

Your services should remain highly available by not having on single point of failure. Done by having cloud workloads running in multiple regions and/or availability zones. Use services like Elastic Load Balancer

## Scalability

Ability to scale up or down. Vertical (scale up) or horizontal (scale out). First is to improve or upgrade server and the other is adding more servers.

## Elasticity

The ability to automatically increase or decrease your resources based on metrics you are tracing. Utilize a service such as auto scaling groups.

## Fault Tolerance

The ability to ensure that there is no single point of failure. Primarily uses failover strategies, for example having a secondary copy of your database ready to start using if your primary one in a different region fails.

## High Durability

The ability to recover from a disaster with minimal data loss.

2 business strategies to consider here:
- Recovery Time Objective (RTO) - Max amount of time your business can afford to be offline due to an incident without incurring a substantial loss
- Recovery Point Objective (RPO) - Max amount of data that can be lost due to an incident

## Management and development tools

You can use 3 tools to manage AWS resources
- Management Console: User friendly web based interface
- Software Developer Kits (SDKs): make your code compatible to run and manage AWS Resources
- Command Line Interfaces (CLI): Used to programmatically make changes to your AWS resources

Alwas secure access and limit who can get into your resources.

## AWS Account IDs

Is a unique 12 digit series that references an AWS account. Used when logging in with non root account, giving shared access to resources in another account. Keep private if you can

## AWS API

API stands for Application Programming Interface. In this context, it is software that allows for two services to talk to each other. The most common is HTTP/S request.

This API can be utilized with either the AWS console, AWS SDK, or AWS CLI

## AWS management console

The most user friendly way to interact to interact with and manage AWS resources.Each service has its own console. Long term the command line interface will be the most efficient way to work with AWS.

## AWS SDK

An SDK is a set of tools used to build software, the SDK is specific to the platform.

Provides support for many programming languages. If interested in using them look for it by googling AWS \<Programming language\> SDK.

## AWS CLI

A Command Line Interface (CLI) is a tool you can use to create and run scripts to automate processes in AWS.

## Access Keys

Required to have programmatic access to AWS resources outside of the console. 2 components of access keys include: the Access Key ID, and the secret Access Key. They have the same permissions as the user they are attached to. Can deactivate and regenerate new ones for a user on demand. These should never be shared with anyone.

## AWS Compute

Compute is the tier of service that is used to process workloads, handle app logic, evaluate rules, react to conditions etc.

Essentially, you need it for erverything and the main services consist of EC2 and Lambda.

### EC2

Flagship AWS compute service that allows you to launch virtual machines (VMs) called instances.
- VM is an evaluation of a physical computer using software
- Multiple VMs can run on the same physical server, allowing you to share costs of that server with other customers.

Can be configured to meet any business requirements.

Amazon Machine Images (AMIs) are templates for creating EC2 instances. You can configure components such as
- Amount of memory (RAM)
- Amount of CPU's (processor cores)
- Amount of network bandwidth
- OS (Windows, Linux, etc.)

### EC2 Instance Types:

5 types of instance families that you can use depending on use cases:
- General Purpose - Balance of compute, memory, and networking resources
- Compute Optimized - Ideal when high processing power is needed
- Memory Optimized - Used for workloads processing large data sets in memory
- Accelerated Optimized - Primarily used in Machine Learning
- Storage Optimized - High read/write access to large data sets on local storage.

### EC2 tenacy type

Tenacy is what allows for cost savings between customers. 3 types:
- Shared (default) - Multiple AWS accounts are using same phys hardware
- Dedicated Instance - Instance runs on single tenant hardware not on entire host
- Dedicated host - instance runs on its own phsycial server that you can control and configure

### EC2 Pricing Models

- On demand (default)
  - Pay as you go
  - Pricing works on hourly rates
- Reserved Instance
  - Best for apps that have a steady predictable usage
  - Can commit to 1 or 3 years of usage (more time - more savings)
  - Can be standard or convertible
  - Can pay upfront, partial, or no upfront. More upfront = more savings
  - Can be shared between accounts, and if not being used you can sell your reserved instances on AWS marketplaces
- Spot Instances
  - Unused compute capacity you can buy from AWS with up to 90% savings compared to on demand.
  - Designed for workloads that have a flexible start and end times because AWS can take back spot computing capacity at any time if it is needed by other on-demand customers.

### Auto Scaling groups and Load Balancers

- These 2 services together are what allows you to achieve high elasticity and scalability for compute workloads
- Auto scaling groups - can automatically add or remove instances to meet your performance requirements
- Elastic Load Balancers (ELB) - distribute traffic between instances to achieve best possible latency. 2 primary types of ELBs.
  - Application Load Balancer - Used for distributing traffic from the web to targets in your network (targets could be EC2 instances, containers, or other things) HTTP/S traffic
  - Network Load Balancer - Used to handle millions of requests per second. TCP traffic.

### VMs and Containers (Go back to 19:30)

VM uses software to replicate an actual server
- Amazon Lightsail - managed VM service (user friendly EC2)

Containers have everything an application needs to run on a server
- Elastic Container Service (ECzs) - supports Docker Containers
- ECS Fargate - More hands-off container management service
- Elastic Kubernetes Service (EKS) - More hands-on container management service that utilizes Kubernetes

### Serverless

This doesn't mean no servers just an absence of physical dedicated servers. Your programs and workloads aren't tied to a specific server.

AWS Lambda is th eprimary serverless compute tool. Used to run code without provisioning servers.

AWS Elastic Beanstalk is a fully managed service to allow you to deploy serverless web applications. You tell AWS what kind of resources your app needs to run and AWS will deploy and manage them for you, allowing you to focus on your app and not infrastructure.
- Based off of CloudFormation templates

### Key Concepts

Storage is different from database in that with storage you have more flexibility on how data you store is formatted
- Databases typically requires data to be formatted a certain way. Relational DB with columns/rows for example.

Best way to keep and analyze log files is in a storage solution like s3

Can automate uploads/removals of objects to your storage

Think file management system on your laptop

### Types of storage services 

Elastic Block Storage (EBS)
- Block Storage
- Most compatible with EC2 instances

Elastic File System (EFS)
- File storage
- Useful when multiple users need access to the same drive (think folders and files)

Simple Storage Service (S3)
- Object storage
- Offers virtually unlimited amounts of storage
- Most widely used AWS storage service

AWS snow family
- Used to migrate data in or out of AWS cloud

### S3 

Object based storage service with unlimited storage capacity.

Consists of objects and buckets
- Objects - what actually contains your data, similar to a file. Consists primarily of key/value pairs
- Bucket - What holds your objetcs, can contain folders. Name must be globally unique, meaning no bucket anywhere in AWS can have the same name.

### S3 storage classes

Storage classes are very useful when considering costs

S3 standard (default)
- Most expensive, 99.99% availability, 11 9's durability, replicates across at least 3 AZ's. Very fast data retrieval.

S3 Intelligent tiering
- Uses ML to move objects to most appropriate storage class

S3 standard IA (Infrequent Access)
- Best if objects are accessed less than once a month
- Cheaper than standard, still has fast data retrieval

S3 one zone IA
- Same as standard IA but data only lives in one AZ, so it's cheaper

S3 Glacier
- Longe term storage ideal for archives. Very cheap but data retrieval takes minutes to hours

S3 Glacier Deep Archive
- Same as Glacier but cheaper and slower

### AWS Snow Family

Physical devices used to move data in and out of the AWS cloud

AWS Snowcone
- Supports 8tb of storage for HDD, 14TB for SSD

AWS Snowball
- Snowball Edge Storage optimized - 80TB HDD
- Snowball Edge Compute optimized - 28TB SSD

AWS Snowmobile
- A literal semi truck of storage
- 100 PB or more

### Elastic File System (EFS)

File system that automatically grows or shrinks based on usage

File systems are most commonly mounted on EC2 instances, but can also be mounted on AWS containers or Lambda functions

4 storage classes to manage costs
- Standard - usedfor regularly accessed files, most expensive
- Standard IA - infrequently accessed files
- One Zone - frequently accessed data that doesn't need the highest durability
- One zone IA - Infrequent access, less durability, cheapest

### Elastic Block Storage (EBS)

Most useful for EC2 instances as it can be directly accessed by the OS of the instance

Can be attached to multiple instances, but only one at a time.

2 primary types:
- SSD based - general purpose and provisioned IOPS
- HDD based - Throughput optimized and cold storage.

## AWS Database

### Key Concepts

Database stores semi structured and structures sata. This is the primary difference between database and storage, as storage is a lot more flexible in the data structure it accepts.

2 types of databases:
- Relational - Rows and Columns (like excel sheets)
- Non-relational - Can be similar to relational, but can also work using key value pairs

Generally a database is used to structure data so it is easier to access and query

### Key-Value pairs

Important concept with NoSQL (non relational) databases are key value pairs.

A key references an attribute of an object and a value describes it.

### AWS Relational DB services

Relational Database Service (RDS)
- Support for most common SQL based databases such as MySQL, MariaDB, PostgreSQL, Oracle, and Microsoft SQL server

Amazon Aurora
- Fully managed RDBS service for mySQL anf PostgreSQL
- Highly available, durable, scalable, and secure
- Can be serverless as well.

### AWS non-relational DB services

DynamoDB
- Primary NoSQL database from WS, designed to be extremely fast, available, and scalable
- Can scale to billions of records with guaranteed consistent data return in seconds

DocumentDB
- NoSQL document database, primarily used for MongoDB.

### Other database services

Redshift
- Data warehouse solution, designed to store data in a manner similar to SQL (relational) and run extremely large and complex queries. Used for Online Analytical Processing (OLAP.)

Elasticache
- Based off of memcached and redis, an in memory data store designed to cache data for quicker access for end users

Database Migration Service (DMS)
- On premise database to AWS
- From two databases in different or dame AWS accounts using different SQL engines
- From SQL to NoSql databases

## AWS Networking

### Networking Overview (Take notes on this section later)

### Virtual Private Cloud (VPC) and subnets

VPC is a logically isolated section of the AWS network where you launch your AWS resources. Uses CIDR notation to specify a range of IPs to be used.

Subnets are smaller partitions within your VPC's that also utilizes IP address ranges. Must have smaller IP range than your VPC
- Subnets can either be public or private.

### Security Groups and NACL's

Security group work at an instance level
- implicitly denies all traffic
- Work off of allow rules only (stateful)

Network Access Control List (NACL) work at subnet level
- Virtual firewall at the network level
- Uses allow and deny rules (stateless)

### VPN and Direct connect

Virtual Private Network (VPN) is generally the equivalent to an on-premise version of VPC. Provides an isolated secure environment to access resources
- Can also establish a VPN between your on-premise resources and the AWS cloud.

AWS direct connect allows you to create a direct, physical connection to AWS from on-premise where your traffic never touches the public internet.

## AWS Security

### Key Concepts

An effectively secured application has security at multiple layers. For applications in the cloud we can consider 7 layers of security
- Data - access to business/customer data, encryption
- Application - apps stay updated and have no vulnerabilities
- Compute - controlled access to VM's
- Network - control access to and communications with resources
- Perimeter - filler large scale attacks is DDos Attacls
- Identity and Access - control access to infrastructure and change management
- Physical - limiting access to a data center to only authorized personnel

### Encryption

Allows your data to stay confidential at all stages of its life cycle

2 primary modes of encryption include
- In transit - SSL/TLS
- At rest - S3 SSE, RDS DB instances, and more

One of the most popular and secure types of encryption is AES-256.

Encrypted and decrypted with encrypt/decrypt keys.

### AWS inspector

Inspector runs a security benchmark against specified EC2 instances

You can check your security and compliance state for,your EC2 resources, and use the results to fix issues.

### AWS Shield

Used specifically to prevent DDos attacks

Inherently used with Route53 and CloudFront

Standard version is free, Advanced is 3000 dollars a month

### Amazon GuardDuty

Threat detection services that continuously monitors your accounts for malicious activity.

Uses Machibe Learning to analyze CloudTrail, DNS, and VPC Flow logs.

### Virtual Private Networks (VPN)

A VPN lets you establish a secure and private tunnel between your on premise network and personal devices

An AWS VPN establishes the same tunnel but between your network/devices and the AWS global network

2 types of AWS VPNs
- Site-to-site VPN - connect on-premise network to VPC
- Client VPN - connect end users to AWS or on-premise networks

### AWS Web Application Firewall (WAF)

Applicatio level firewall that you can write rules to allow or deny traffic to your AWS resources.

Attaches to either CloudFront or App Load Balancer

Protects against the 10 most dangerous attacks, including SQL injections and Cross Site Scripting.

### AWS Key Management Service (KMS)

KMS is a managed service that makes it easy to create and control encryption keys used to encrypt your data

Best practice is to have complex rotating keys

Uses envelope encryption

## AWS User and Identity Management

### Key Concepts

When giving permissions to users, you should always follow the principle of least privilege
- Only give enough permisiions to a user to accomplish what they need and nothing else

Consider organizational compliance standards

Utilize multiple layers of authentication, such as MFA on top of passwords for access.

### Identity and Access Management (IAM)

IAM is AWS's key service for managing users and permissions, based on JSON documents

You can assign permissions to users and other AWS services

There can be 3 types of IAM identities
- Users - End users that login to the console of need programmatic access
- Groups - Groups of end users that you can setup to share permissions
- Roles - Used to grant other AWS services permissions to do specific API actions

### Key components of an IAM policiy

Statememt ID (SID): Used to label and identify each statement

Effect: Specify if the policy will Allow or Deny

Action: Which actions the policy will allow or deny

Principal: Account, user, or role you want to allow or deny access

Resource: The resource to which the action applies

Condition (optional): Circumstances under which the policy is enacted

### 3rd party identity providers

It is possible to allow access by utilizing a 3rd party identity provider, for example using Facebook, Google, or Apple credentials

Amazon Cognito is the service that handles these, and it does so by having user groups and identity pools
- User pool is a directory of users
- Identity pools let you give temporary credentials to a 3rd party verified user to access AWS services

### Root user account

Special account created upon creation of your AWS account that has full access to everything, and uses email/password to login

Should be well secured with MFA and extremely limited with access. There are only a few certain things you need to login to this account for, everything else can be done with an IAM admin user.
- Changing account settings like email address, account name
- Restore IAM user permissions
- Activate IAM accress to billing console
- Close your AWS account
- Change/Cancel AWS support plan

## Application Integration

### Key Concepts

Application Integration refers to letting multiple independent applications work and communicate with each other, while being facilitated by an intermediate system

By separating our apps into individual components, you reduce the risk of one thing breaking causing everything else to break

Most common systems utilized for application integration are:
- Queueing
- Pub/Sub
- Streaming
- API/Gateways

### Queueing

A queueing system is a non real-time messaging system, used to process messaging and events that will delete messages once they are consumed

Amazon Simple Queue Service (SQS) is a fully managed service that allows you to create queues so you can decouple and scale your systems and applications

### Pub/Sub (Publish/Subscribe)

Commonly used for messaging systems and notifications of events occuring

Amazon Simple Notification System (SNS) is a fully managed servic to handle your pub/sub system

Consists of publishers (message senders), topics (event handlers), and subscribers (message recievers)

SNS flow
- User subscribes to a topic to be notified by email when AWS account charges reacg $10
- When account charges reach $10, SNS sends a notification to that topic
- The message is then filtered and sorted and automatically emailed to the user notifying them of their charges

### Streaming

Utilizing SNS and SQS, users or services can react to events/messages in real time as they are processed

Amazon Kinesis is the primary streaming service to handle analyzing real time incoming events

### API Gateways

API can be thought of as the middleman that sits between your application and your backend systems
- They contain information about a request, for example when you login to facebook an API sends your login credentials to a database, and once verified it sends back the appropriate information to load your profile.

Amazon API Gatewat handles APIs in your cloud environment context, and allows you to format requests and responses.

### Amazon EventBridge

EventBridge is used with CloudWatch, which is a service that monitors how your systems are performing and what is happening with them.
- EventBridge processes events as they happen and can be used to trigger actions from other services

Just remember that this service is used primarily to monitor what is happening with your EC2 instances

## Containers

### Key Concepts

Containers allow you to run multiple applications on the same EC2 instance that are completely isolated from each other

A container comes with everything an application needs to run regardless of the underlying Operating System

### Container Services

Amazon Elastic Container Service (ECS)
- Fully managed service that allows you to deploy, manage, and scale containerized applications
- Primarily uses docker

Amazon Elastic Kubernetes Service (EKS)
- Fully managed service that helps Kubernetes control nodes, schedule containers, manage application availability, store cluster data, and other tasks
- Work with Docker
- More hands on

AWS Fargate
- More hands-off container management service that allows you to focus more on building applications and less on dealing with your containers and their nuances.

## AWS Organizations and Accounts

### Key Concepts

AWS organizations is a service that allows you to create new AWS accounts tied to your businesses, and centrally manage billing, compliance, security, and share resources

Root (master) account user sits at the top of the organization

Organizational Units (OUs) are grous of AWS accounts. Can be nested

Service Control Policies act as guardrails for your organization, setting boundaries on what your accounts are able to do.

### Organizations Visualized 2:21:20 (Take notes on this)

### Organizations and SCPs

Organizations are useful if you have a bunch of diferent users/departments that need access to services
- Can enable consolidated billing to send bill to one account. 
- Can see which accounts are incurring which costs
- Automate new account creation and automatically apply appropriate permissions
- Automate infrastructure deployment in specific accounts
- Easily share resources across accounts

Service Control Policies (SCPs) set guardrails for all accounts in your organization (not users or roles)
- They only filter and never add permissions, so still need to use IAM policies as we;;
- Avoid attaching SCPs to the root account of your organization, this could have unwanted effects on accounts in an OU.

## Governance and Compliance

### Key Concepts 

Sometimes your organization, or an organization that you work with requires things to be done in a particular way for compliance reasons, security reasons, or otherwise

AWS has services to automatically ensure your cloud resources are all compliant, and any changes made are recorded and verified with the rules laid out.

AWS Artifact is your one stop shop for security and compliance reports.

### AWS config

Config is a service used to manage changes in your AWS account and make sure they are compliant with processes set by your organization

Region specific

Common use cases
- Ensure a resource stays configured in a specific way
- Keep track of all configuration changes to a resources
- List all resources within a region
- Assist with a security analysis by detailing historical information and changes

### Cloud Formation

CloudFormation is a service that allows you to make templates to specify how you want architecture deployed

You can reuse templates to quickly deploy/edit your architecture configuration automatically

Helps eliminate user error when deploying resources.

### Tagging 

Tagging involves identifying your resources with key value pairs, and is one of the best way to manage costs.

Examples
- Department = Accounting
- Status = Approved
- Environment = Production
- Location = United States

Can group tagged resources into resource groups, allowing you to better organize them and apply permissions to groups of resources

Aside from tracking and managing costs they re helpful for the following reasons:
- manage resources to see how much a certain resource has allocated
- automation
- governance and compliance
- Helps classify data and subsequent security impacts

### AWS License Manager

There are times where certain software requires a license to run, AWS License Manager allows you to centrally manage these licenses.

Licenses can be based on virtual cores (vCPUs), physical cores, sockets, or number of machines

AWS License Manager works with:
- EC2 dedicated instances, dedicated hosts, spot instances
- Oracle databases in RDS

## Logging

### Key Concepts

It is very important to remember that things will go wrong, it is unavoidable.

Logging helps you pinpoint failure points, determine the cause of the failure, and automattically remediate it.

AWS has a few types of logging services but there are 2 primary areas you monitor
- Your infrastructure itself (what is happening)
- Any changes and access to your infrastructure (who did what)

### AWS CloudWatch

Monitors what is happening with your infrastructure, consists of a few different services:
- Logs: centralized area to store log data
- Metrics: time ordered data points (variables) - EventBridge: monitors for specified events and will trigger actions when those events occur
- Alarms: trigger notifications based on metrics
- Dashboards: Visualize what is happening based on collected metrics

CloudWatch alarms have 3 states
- OK: metric within defined threshold
- Alarm: Metric is outside of the defined threshold
- INSUFFICIENT_DATA: alarm has just started of not enough data is available

### AWS CloudTrail

If asked how to track API calls or user access, think CloudTrail

Monitors API calls and actions made on an AWS account with the following
- Where: Source IP Address
- When: Event Time
- Who: User
- What: Region/Resource/Action

Trails are stored in S3 and are analyzed with Amazon Athena
- Athena is a serverless SQL like service that is primarily used to analyze data stored in S3

## Pricing and Billing

### Total Cost of Ownership

TCO is one of the largest value adds of using cloud, so it is important to know.

Compare the cost of:
- Owning and maintaining your own on-premise physical servers and data centers, and hiring people to do that.
- Using AWS servers and adopting a pay as you go model.

(write about diagram)

### AWS Pricing Calculator

The pricing calculator is a free tool that can be used to estimate the cost of various AWS services

Contains over 100 services you can use in your estimate

Can be used to figure out your final TCO as you estimate your costs in the cloud, and compare them to your on-premise costs.

### AWS Budgets

Setup budgets that can send you alerts if you are approaching of exceeding your defined budget

Cost, Usage, Reservation budgets

Can be tracked at a monthly, quarterly, yearly levels

Can create budget reports to send out.

### AWS Cost and Usage Reports

Detailed spreadsheets that help you to better analyze and understand your AWS costs

Will contain allocation tags

### AWS Cost Explorer

Helps you visualize, understand, and manage your AWS costs and usage over time.

Can view data at monthly or daily level of granularity

### Cost allocation tags

Allows you to identify each resource so that when costs are reported, you know where each expense came from

Can be 1 of 2 types
- User Defined (Production)
- AWS Generated (aws:createdBy)

### AWS Consolidated Billing

A feature of AWS Organizations that allows you to pay for multiple AWS accounts with one bill

Designate a master account that pays the charges of other member accounts

Use Cost Explorer to visualize usage for consolidated billing

### AWS free services

AWS has a free-tier for a few resources that allow you to use them for free for your first 12 months of signup, or until you reach a specified monthly limit

The below services are free forever, as opposed to the free-tiew which is free up to a point
- IAM
- VPC
- Auto Scaling *May generate paid services
- CloudFormation
- Elastic Beanstalk *May generate paid services
- Opsworks
- Amplify
- Appsync
- Organizations and Consolidated Billing
- AWS Cost Explorer

## AWS Support and Helpful Services

### AWS Support Plans

Basic
- Email support only for Billing and Account
- 7 trusted advisor checks
- Free

Developer
- Tech support via email ~24 hour response time for general guidance and system impaired
- 7 trusted advisor checks
- $29/ month or 3% of monthly AWS usage, whichever is greater

Business
- Tech support via email, chat, and phone 24/7
- Same benefits as developer, with production support
- All trusted advisor checks
- 100 a month or 3-10% of monthly AWS usage

Enterprise
- TAM (Technical Account Manager) and all benefits of everything above. TAM is an AWS employee dedicated to your architecture
- 15000 a month or 3-10% of monthly AWS usage

### AWS Trusted Advisor

A recommendation tool that automatically and actively monitors your AWS account to provide actionable reccomendations across a series of categories

5 categories of AWS Trusted Advisor
- Cost Optimization
- Performance
- Security
- Fault Tolerance
- Service Limits

### AWS Marketplace

A curated digital catalg with thousands of software listings from independent software vendors

Products can be free or paid, charges come with your AWS bill

Products can be offered as:
- AMIs
- AWS CloudFormation templates
- SaaS offerings
- Web ACL
- AWS WAF rules

### AWS Service Health Dashboard

Service Health Dashboard shows the general status of AWS services

### AWS Personal Health Dashboard

Provides alerts and guidance for AWS events that might affect your environment

### Terms of abuse

AWS Trust and Safety is a team that specifically deals with abuse occuring on the AWS platfrm for specific issues.

Typically issues are related to behavior that could cause harm to AWS infrastructure or other customers using the same server

### AWS Partner Network

The APN is a global partner for AWS. Your organization can join it to increase exposure to and opportunities with AWS

Can be 1 of 2 partners:
- Consulting Partner - you help companies utilize AWS
- Tech partner - you build tech on top of AWS as a service offering

## Service Definitions

Review this for last minute test prep before the exa,. (2:47:42)