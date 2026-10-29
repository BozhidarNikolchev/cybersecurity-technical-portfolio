# Search Skills

## Platform

TryHackMe

## Path

Pre Security

## Module

Introduction to Cyber Security

## Overview

This room introduced essential search and research techniques used by cybersecurity professionals. Effective searching allows analysts, investigators, penetration testers, and defenders to quickly locate information about vulnerabilities, systems, tools, threats, and security incidents.

The room explored several important resources commonly used throughout the cybersecurity industry.

---

## Learning Objectives

- Learn how cybersecurity professionals conduct research.
- Understand how to gather publicly available information.
- Explore vulnerability databases and threat intelligence sources.
- Learn how to search technical documentation.
- Understand how publicly available information can benefit both attackers and defenders.

---

## Key Concepts

### Open Source Intelligence (OSINT)

OSINT refers to the collection and analysis of publicly available information.

Common OSINT sources include:

- Search engines
- Technical documentation
- Security databases
- Public websites
- Domain information
- Security research publications

Cybersecurity professionals regularly use OSINT during investigations, assessments, and incident response activities.

---

## Shodan

### What Is Shodan?

Shodan is a search engine that indexes internet-connected devices.

Unlike traditional search engines that index websites, Shodan discovers and catalogs exposed devices and services.

Examples include:

- Web servers
- Routers
- Cameras
- Industrial control systems
- Firewalls
- Internet-facing applications

### Security Relevance

Security professionals use Shodan to:

- Discover exposed assets
- Identify publicly accessible services
- Assess external attack surfaces
- Investigate potential security risks

### Key Lesson

Anything connected to the internet may be discoverable if improperly configured.

---

## VirusTotal

### What Is VirusTotal?

VirusTotal is a threat intelligence platform used to analyze:

- Files
- URLs
- Domains
- IP Addresses
- File Hashes

### Security Relevance

Analysts use VirusTotal to determine whether an artifact has been associated with malicious activity.

Common use cases include:

- Malware investigations
- Suspicious file analysis
- Phishing investigations
- Threat hunting

### Key Lesson

VirusTotal helps analysts quickly gather intelligence about suspicious files and internet resources.

---

## CVE

### What Is A CVE?

CVE stands for Common Vulnerabilities and Exposures.

A CVE is a publicly documented cybersecurity vulnerability assigned a unique identifier.

Example:

```text
CVE-2024-0001
```

### Why CVEs Matter

CVEs allow security professionals to:

- Track vulnerabilities
- Perform risk assessments
- Prioritize patching
- Research known security issues

### Key Lesson

Understanding CVEs is essential for vulnerability management and security assessments.

---

## Linux Manual Pages (man)

### What Is Man?

The Linux command:

```bash
man
```

opens the manual page for a command.

Example:

```bash
man ls
```

### Why It Is Important

Manual pages provide:

- Command descriptions
- Usage information
- Available options
- Examples

### Cybersecurity Relevance

Security professionals frequently rely on manual pages to:

- Learn unfamiliar commands
- Verify syntax
- Understand tool functionality

### Key Lesson

The man command is one of the most valuable built-in learning resources available on Linux systems.

---

## Proof of Concept (PoC)

### What Is A PoC?

A Proof of Concept (PoC) demonstrates whether a vulnerability can be successfully exploited.

A PoC helps validate that a security issue actually exists.

### Purposes Of A PoC

- Vulnerability verification
- Security research
- Demonstrations
- Testing defensive controls

### Key Lesson

PoCs help security professionals understand how vulnerabilities behave and what impact they may have.

---

## SQL Injection

### What Is SQL Injection?

SQL Injection is a web application vulnerability that occurs when user-supplied input is improperly handled within database queries.

Attackers may attempt to manipulate database operations through crafted input.

### Potential Impacts

- Unauthorized data access
- Data disclosure
- Authentication bypass
- Data modification

### Defensive Measures

- Parameterized queries
- Input validation
- Prepared statements
- Least-privilege access controls

### Key Lesson

SQL Injection remains one of the most widely known web application vulnerabilities and highlights the importance of secure coding practices.

---

## Practical Skills Learned

During this room, the following resources and concepts were explored:

- Shodan
- VirusTotal
- CVE Databases
- Linux Manual Pages
- Proof of Concept Research
- SQL Injection Fundamentals

These resources are frequently used by security analysts, penetration testers, incident responders, and security researchers.

---

## Security Lessons Learned

- Effective searching is a core cybersecurity skill.
- Publicly available information can reveal valuable security insights.
- Vulnerability research helps organizations identify risks.
- Threat intelligence platforms accelerate investigations.
- Technical documentation is an important learning resource.
- Security professionals rely heavily on research and continuous learning.

---

## Career Relevance

The concepts introduced in this room are commonly used by:

- Security Analysts
- SOC Analysts
- Penetration Testers
- Threat Intelligence Analysts
- Incident Responders
- Vulnerability Management Teams

Research and search skills are fundamental across nearly every cybersecurity discipline.

---

## Reflection

This room demonstrated that cybersecurity professionals spend a significant amount of time researching. Understanding how to locate information efficiently is just as important as understanding the technologies themselves.

The ability to search for vulnerabilities, investigate suspicious indicators, review documentation, and gather intelligence is a foundational skill that supports both offensive and defensive security roles.

---

## Key Takeaways

- Effective searching is a critical cybersecurity skill.
- Shodan helps identify internet-facing systems.
- VirusTotal assists with threat intelligence and malware analysis.
- CVEs provide standardized vulnerability tracking.
- Linux man pages are valuable learning resources.
- PoCs help validate vulnerabilities.
- SQL Injection demonstrates the importance of secure coding practices.  