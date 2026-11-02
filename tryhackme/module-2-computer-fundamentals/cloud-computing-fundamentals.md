# Cloud Computing

## Platform

TryHackMe

## Module

Module 02 - Linux Fundamentals

## Overview

This room introduced the fundamentals of cloud computing and explained how modern organizations use cloud technologies to deliver scalable, reliable, and cost-effective services.

The room explored cloud deployment models, cloud service models, and the advantages that cloud computing provides over traditional on-premises infrastructure.

Cloud computing builds upon concepts such as virtualization, containers, automation, and networking to provide resources and services on demand.

---

## Learning Objectives

- Understand what cloud computing is.
- Learn the cloud service models:
  - IaaS
  - PaaS
  - SaaS
- Understand cloud deployment types:
  - Public Cloud
  - Private Cloud
  - Hybrid Cloud
- Understand the benefits of cloud computing.
- Learn how large organizations use cloud environments.

---

## What is Cloud Computing?

Cloud computing is the delivery of computing services over the internet.

Instead of purchasing and maintaining physical servers, organizations can rent computing resources from cloud providers whenever they need them.

Examples of cloud resources:

- Virtual machines
- Storage
- Databases
- Networking
- Applications
- Development platforms

Cloud computing allows users to access services from anywhere with an internet connection.

---

## Cloud Types

### Public Cloud

A public cloud is a cloud environment shared by many users and organizations.

Examples:

- Amazon Web Services (AWS)
- Microsoft Azure
- Google Cloud Platform (GCP)

Characteristics:

- Accessible over the internet
- Managed by a cloud provider
- Highly scalable
- Cost-effective

---

### Private Cloud

A private cloud is dedicated to a single organization.

Characteristics:

- Greater control
- Higher customization
- Enhanced privacy
- Organization-managed environment

Private clouds are commonly used by organizations with strict security or compliance requirements.

---

### Hybrid Cloud

A hybrid cloud combines public and private cloud environments.

Example:

```text
Private Cloud
       ↕
Public Cloud
```

Benefits:

- Flexibility
- Scalability
- Cost optimization
- Enhanced workload management

Organizations can keep sensitive systems private while leveraging public cloud resources when needed.

---

## Cloud Service Models

### Infrastructure as a Service (IaaS)

IaaS provides access to fundamental computing resources.

Resources include:

- Virtual servers
- Storage
- Networking
- Computing power

Example:

```text
AWS EC2
```

With IaaS, the customer manages:

- Operating systems
- Applications
- Configurations

The provider manages:

- Physical hardware
- Networking infrastructure
- Datacenter facilities

---

### Platform as a Service (PaaS)

PaaS provides a ready-to-use environment for building and running applications.

Developers focus on application development while the provider manages infrastructure.

Benefits:

- Faster development
- Simplified deployment
- Reduced administration

Examples:

- Application hosting platforms
- Development environments
- Managed runtime services

---

### Software as a Service (SaaS)

SaaS provides complete software applications through the internet.

Users simply access the application without installing or managing it.

Examples:

- Gmail
- Zoom
- Microsoft 365

Benefits:

- No installation required
- Accessible from anywhere
- Automatic updates
- Minimal maintenance

---

## Amazon EC2

### What is EC2?

EC2 (Elastic Compute Cloud) is Amazon's cloud-based virtual machine service.

EC2 allows users to:

- Create virtual servers
- Scale resources as needed
- Deploy applications quickly
- Pay only for resources consumed

Benefits:

- Flexibility
- Scalability
- Rapid deployment

---

## Benefits of Cloud Computing

### Scalability

Resources can be increased or decreased based on demand.

Example:

```text
More users
    ↓
More computing resources
```

---

### On-Demand Self-Service

Users can provision resources whenever needed without waiting for hardware installation.

---

### Pay Only for What You Use

Organizations pay for consumed resources rather than purchasing expensive hardware in advance.

---

### Security

Cloud providers offer numerous security features, including:

- Access controls
- Encryption
- Monitoring
- Security management tools

---

### High Availability

Cloud infrastructure is designed for reliability and minimal downtime.

Services can remain available even if individual components fail.

---

### Global Access

Cloud resources can be accessed from different geographic locations around the world.

This enables:

- Remote work
- Global collaboration
- Worldwide service delivery

---

## How Large Organizations Use the Cloud

Modern organizations use cloud computing for:

- Website hosting
- Application deployment
- File storage
- Databases
- Software development
- Data analytics
- Collaboration services

Cloud environments allow companies to quickly expand infrastructure without purchasing additional hardware.

---

## Relationship to Virtualization

Cloud computing relies heavily on virtualization technologies.

Example:

```text
Physical Server
        ↓
Hypervisor
        ↓
Virtual Machines
        ↓
Cloud Services
```

Virtualization allows cloud providers to efficiently share hardware resources among many customers.

---

## Cybersecurity Relevance

Cloud computing plays a major role in modern cybersecurity.

Security professionals must understand:

- Cloud infrastructure
- Identity and access management
- Cloud security controls
- Shared responsibility models
- Cloud monitoring and logging

Many organizations now operate partially or entirely within cloud environments.

---

## Lessons Learned

- Cloud computing delivers computing resources through the internet.
- Public, private, and hybrid clouds serve different business needs.
- IaaS provides infrastructure resources.
- PaaS provides development platforms.
- SaaS provides fully managed software applications.
- Cloud computing improves scalability and flexibility.
- Organizations only pay for the resources they consume.
- Virtualization is a foundational technology behind cloud computing.

---

## Reflection

This room demonstrated how cloud computing has transformed modern IT infrastructure. Instead of relying entirely on physical hardware, organizations can rapidly deploy resources, scale services, and provide global access through cloud platforms.

Understanding cloud concepts is important because cloud technologies are now widely used across nearly every industry and play a major role in modern cybersecurity environments.

---

## Key Takeaways

- Cloud computing provides on-demand computing resources via the internet.
- Public, private, and hybrid clouds offer different deployment models.
- IaaS, PaaS, and SaaS provide different levels of service.
- EC2 allows users to deploy scalable virtual servers in the cloud.
- Cloud computing improves scalability, flexibility, and availability.
- Organizations pay only for the resources they use.
- Virtualization makes cloud computing possible.
- Cloud knowledge is an essential cybersecurity skill.  