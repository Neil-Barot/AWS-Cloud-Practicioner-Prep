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