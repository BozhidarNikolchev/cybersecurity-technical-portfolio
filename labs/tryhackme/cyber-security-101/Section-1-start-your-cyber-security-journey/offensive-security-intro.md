# Offensive Security Intro

## Platform

TryHackMe

## Path

Pre Security

## Overview

This room introduced the concept of Offensive Security and demonstrated how attackers identify weaknesses in web applications through reconnaissance and enumeration techniques.

The lab involved discovering a hidden administrative page within a vulnerable banking application and using exposed functionality that should not have been accessible to regular users.

---

## Learning Objectives

- Understand the purpose of Offensive Security.
- Learn how attackers think during reconnaissance.
- Discover hidden web pages using directory enumeration.
- Understand the risks of exposed administrative functionality.
- Develop an attacker mindset when assessing web applications.

---

## Key Concepts

### Offensive Security

Offensive Security focuses on identifying vulnerabilities by thinking and acting like an attacker.

Examples include:

- Penetration Testing
- Vulnerability Assessments
- Red Team Operations
- Web Application Testing

### Reconnaissance

Reconnaissance is the process of gathering information about a target before attempting exploitation.

Examples:

- Identifying hidden pages
- Discovering exposed services
- Finding administrative interfaces

### Enumeration

Enumeration is the process of actively discovering resources exposed by a target system.

It is often one of the earliest stages of a security assessment.

### Attack Surface

The attack surface includes all accessible components that could potentially be targeted.

Examples:

- Login pages
- Administrative panels
- Hidden directories
- File upload functions

---

## Tools Used

### dirb

Purpose:

- Discover hidden web pages
- Identify exposed directories
- Expand understanding of a target's attack surface

Example resources that may be discovered:

- /admin
- /login
- /backup
- /uploads

---

## Practical Exercise

### Hidden Page Discovery

A hidden administrative page was discovered within the FakeBank application through directory enumeration techniques.

### Administrative Functionality

The exposed page provided privileged functionality that should have required additional protection.

The exercise demonstrated how security weaknesses can occur when sensitive functionality is accessible without proper controls.

---

## Security Lessons Learned

- Hidden pages are not a security control.
- Administrative functions must be protected by authentication and authorization.
- Enumeration is often one of the first phases of an attack.
- Attackers actively search for resources that developers assume users will never find.

---

## Career Relevance

The concepts introduced in this room are used by:

- Penetration Testers
- Red Team Operators
- Security Consultants
- Web Application Security Analysts

---

## Reflection

This room demonstrated how attackers discover functionality that is not immediately visible to users. It highlighted the importance of reconnaissance and showed that security should never rely solely on obscurity.

---

## Key Takeaways

- Offensive Security focuses on proactively finding weaknesses.
- Enumeration is a critical step in security testing.
- Hidden functionality can create serious security risks.
- Security should never depend on pages being difficult to find.  