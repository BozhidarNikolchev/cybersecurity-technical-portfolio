# Virtualisation Basics

## Platform

TryHackMe

## Module

Module 02 - Linux Fundamentals

## Overview

This room introduced the fundamentals of virtualization and explained why it has become a critical technology within modern IT infrastructure.

The room explored how organizations historically deployed applications on dedicated physical servers, the limitations of this approach, and how virtualization significantly improves hardware utilization, flexibility, scalability, and deployment efficiency.

It also introduced hypervisors, virtual machines, containers, container images, and network ports.

---

## Learning Objectives

- Understand why managing applications on individual physical servers is inefficient.
- Learn how virtualization improves hardware utilization.
- Understand scalability and resource optimization.
- Understand the role of hypervisors.
- Understand the components of a lab machine (virtual machine).
- Learn how containers further optimize application deployment.

---

## Why Virtualization Exists

Traditionally, organizations often deployed one application per physical server.

Example:

```text
Server 1 → Email Service
Server 2 → Website
Server 3 → Database
```

This approach introduced several problems:

- High hardware costs
- Poor resource utilization
- Increased power consumption
- Complex management
- Limited scalability

Many servers used only a fraction of their available CPU, RAM, and storage resources.

Virtualization was created to solve these challenges.

---

## Virtualization

### Definition

Virtualization allows a single physical computer to behave like multiple independent computers.

Instead of running one operating system and one application, a single machine can host multiple virtual environments simultaneously.

Example:

```text
Physical Computer
│
├── Virtual Machine 1
├── Virtual Machine 2
├── Virtual Machine 3
└── Virtual Machine 4
```

Each virtual machine functions as its own independent system.

---

## Hypervisor

### Definition

A hypervisor is the software responsible for creating, managing, and running virtual machines.

It acts as a resource manager between the physical hardware and the virtual systems.

Responsibilities include:

- Allocating CPU resources
- Allocating RAM
- Managing storage
- Managing virtual networking
- Running virtual machines

Without a hypervisor, virtualization would not be possible.

---

## Lab Machines (Virtual Machines)

### Definition

A lab machine is a complete virtual computer running inside a physical computer.

Characteristics:

- Has its own operating system
- Has its own memory allocation
- Has its own storage allocation
- Operates independently from the host system

Examples:

```text
Ubuntu VM
Windows VM
Kali Linux VM
```

### Cybersecurity Benefits

Virtual machines provide:

- Safe testing environments
- Isolation from the host system
- Easy recovery through snapshots
- Controlled learning environments

Virtual machines are heavily used in cybersecurity training platforms such as TryHackMe.

---

## Containers

### Definition

A container is a lightweight isolated environment designed to run a specific application.

Unlike virtual machines, containers do not require a complete operating system.

Example:

```text
Host Operating System
│
├── Container A
├── Container B
└── Container C
```

Containers share the host system's kernel while remaining isolated from one another.

---

## Container Images

### Definition

Container images serve as templates used to create containers.

A container image contains:

- Application files
- Dependencies
- Configuration information
- Runtime requirements

The image can be reused to create identical containers repeatedly.

Think of a container image as a pre-packaged blueprint or recipe for an application.

---

## Network Ports

### Definition

Network ports are numbered communication endpoints used by applications and services.

Examples:

```text
80   - HTTP
443  - HTTPS
22   - SSH
53   - DNS
```

Ports allow multiple services to communicate over a network simultaneously.

Containers and virtual machines commonly expose services through network ports.

---

## Benefits of Virtualization

Virtualization provides several advantages for organizations and individuals.

### Cost Savings

Fewer physical servers are required to host applications.

### Better Resource Usage

Hardware resources can be shared efficiently across multiple virtual systems.

### Safe Testing

Virtual environments allow experimentation without affecting production systems.

### Faster Deployment

New systems can be created rapidly from templates.

### Flexibility

Environments can be customized to meet specific requirements.

### Portability

Virtual machines can be moved between physical systems.

### Scalability

Resources and services can be expanded as demand increases.

### Centralized Management

Administrators can manage multiple systems from a centralized platform.

---

## Practical Cybersecurity Relevance

Virtualization is heavily used in cybersecurity because it allows professionals to:

- Create testing environments
- Build isolated labs
- Analyze malware safely
- Conduct security research
- Deploy vulnerable practice machines
- Simulate networks

Examples include:

- TryHackMe Lab Machines
- Penetration Testing Labs
- Security Research Environments
- Blue Team Training Labs

---

## Lessons Learned

- Virtualization maximizes hardware efficiency.
- Hypervisors manage and run virtual machines.
- Virtual machines behave like complete computers.
- Containers provide lightweight application isolation.
- Container images act as reusable templates.
- Ports enable network communication between systems and services.
- Virtualization improves scalability, flexibility, and deployment speed.

---

## Reflection

This room demonstrated why virtualization has become a foundation of modern IT infrastructure. By allowing multiple systems and applications to share hardware resources efficiently, organizations can reduce costs, improve scalability, and deploy services more effectively.

Virtualization also plays a critical role in cybersecurity by providing safe environments for training, testing, research, and investigation.

---

## Key Takeaways

- Virtualization enables one physical computer to operate as multiple computers.
- Hypervisors create and manage virtual machines.
- Virtual machines provide complete isolated operating environments.
- Containers offer lightweight application isolation.
- Container images serve as reusable deployment templates.
- Network ports enable communication between services.
- Virtualization improves efficiency, flexibility, scalability, and security testing capabilities.  