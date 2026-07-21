# Common Cybersecurity Commands

## Linux Commands

### Display Current Directory

```bash
pwd
```

Displays the current working directory.

---

### List Files

```bash
ls
```

Lists files and directories.

---

### Change Directory

```bash
cd folder_name
```

Changes the current directory.

---

### Create Directory

```bash
mkdir test
```

Creates a new directory.

---

### Create File

```bash
touch file.txt
```

Creates an empty file.

---

## Networking Commands

### Display IP Address

```bash
ip a
```

Shows IP address and network interface details.

---

### Test Network Connectivity

```bash
ping google.com
```

Checks whether the system can reach another host.

---

### Display Active Connections

```bash
netstat -tuln
```

Shows active network connections and listening ports.

---

## Nmap Commands

### Basic Scan

```bash
nmap 192.168.1.1
```

Scans the target for open ports.

---

### Service Version Detection

```bash
nmap -sV 192.168.1.1
```

Detects the version of running services.

---

## OpenSSL Commands

### Check OpenSSL Version

```bash
openssl version
```

Displays the installed OpenSSL version.

---

### Encrypt a File

```bash
openssl enc -aes-256-cbc -salt -in file.txt -out file.enc
```

Encrypts a file using AES-256 encryption.

---

## Netcat Commands

### Start a Listener

```bash
nc -lvp 4444
```

Starts Netcat in listening mode.

---

### Connect to a Host

```bash
nc 192.168.1.10 4444
```

Connects to a remote host on port 4444.

---

# Learning Outcome

This document summarizes commonly used Linux, networking, scanning, encryption, and communication commands that are frequently used in cybersecurity labs.
