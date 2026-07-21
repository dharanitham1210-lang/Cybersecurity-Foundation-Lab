# Nmap

## Overview

Nmap (Network Mapper) is a free and open-source network scanning tool used to discover hosts, identify open ports, detect running services, and perform basic security assessments. It is one of the most widely used tools by network administrators and cybersecurity professionals.

---

## Features

- Host Discovery
- Port Scanning
- Service Version Detection
- Operating System Detection
- Network Inventory
- Scriptable Scanning using NSE

---

## Installation

### Kali Linux

```bash
sudo apt update
sudo apt install nmap
```

---

## Basic Commands

### Scan a Host

```bash
nmap 192.168.1.10
```

Scans the target system for open ports.

### Service Version Detection

```bash
nmap -sV 192.168.1.10
```

Detects the version of running services.

### Operating System Detection

```bash
nmap -O 192.168.1.10
```

Attempts to identify the operating system.

### Aggressive Scan

```bash
nmap -A 192.168.1.10
```

Performs OS detection, version detection, script scanning, and traceroute.

---

## Applications

- Network Discovery
- Security Auditing
- Vulnerability Assessment
- Device Identification
- Service Enumeration

---

## Advantages

- Easy to use
- Fast and reliable
- Supports advanced scanning techniques
- Available on multiple operating systems

---

## Learning Outcome

By using Nmap, I learned how to discover devices on a network, identify open ports, detect running services, and perform basic network reconnaissance.

---

## Screenshot

> Screenshot will be added after completing the practical lab.
