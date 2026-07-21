# Netcat

## Overview

Netcat (nc) is a command-line networking utility used for reading and writing data across network connections. It is often called the "Swiss Army Knife" of networking because of its versatility in testing, debugging, and transferring data.

---

## Features

- TCP and UDP communication
- Port listening
- Port scanning
- File transfer
- Banner grabbing
- Network debugging

---

## Installation

### Kali Linux

```bash
sudo apt update
sudo apt install netcat
```

---

## Common Commands

### Listen on Port 4444

```bash
nc -lvp 4444
```

Starts Netcat in listening mode.

### Connect to a Remote Host

```bash
nc 192.168.1.10 4444
```

Connects to the specified host and port.

---

## Applications

- Connectivity Testing
- Port Listening
- File Transfer
- Network Troubleshooting
- Banner Grabbing

---

## Advantages

- Lightweight
- Easy to use
- Cross-platform
- Useful for network testing

---

## Learning Outcome

Learned how to establish simple client-server communication and perform basic network testing using Netcat.

---

## Screenshot

> Screenshot will be added after completing the practical lab.
