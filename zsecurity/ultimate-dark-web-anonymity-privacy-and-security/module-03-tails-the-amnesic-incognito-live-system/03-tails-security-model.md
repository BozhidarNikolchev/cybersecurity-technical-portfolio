---
Author: Bozhidar Nikolchev
---

# TAILS Security Model

## Isolation

Applications in TAILS are isolated from:

- host operating system
- local file system
- external processes

---

## Forced TOR Routing

All internet traffic:

- is routed through Tor
- cannot bypass Tor network

---

## Sandboxing

Applications (like Tor Browser):

- run in restricted environments
- cannot freely access entire system

---

## Amnesic Design

- No data stored after shutdown
- No logs preserved
- No traces left behind

---

## Key Principle

Least privilege:
Applications only have access to what is necessary.

---

## My Understanding

TAILS reduces attack surface by controlling both network flow and system access.  