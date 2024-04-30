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

## Serverless

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

## AWS Snow Family

Physical devices used to move data in and out of the AWS cloud

AWS Snowcone
- Supports 8tb of storage for HDD, 14TB for SSD

AWS Snowball
- Snowball Edge Storage optimized - 80TB HDD
- Snowball Edge Compute optimized - 28TB SSD

AWS Snowmobile
- A literal semi truck of storage
- 100 PB or more

##



