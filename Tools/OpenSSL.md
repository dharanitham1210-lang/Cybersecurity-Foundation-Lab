# OpenSSL

## Overview

OpenSSL is an open-source toolkit used to implement SSL/TLS protocols and perform cryptographic operations such as encryption, decryption, hashing, and certificate management.

---

## Features

- File Encryption and Decryption
- SSL/TLS Support
- Certificate Generation
- Hash Generation
- Digital Signature Support

---

## Installation

### Kali Linux

```bash
sudo apt update
sudo apt install openssl
```

---

## Common Commands

### Check OpenSSL Version

```bash
openssl version
```

Displays the installed OpenSSL version.

### Encrypt a File

```bash
openssl enc -aes-256-cbc -salt -in file.txt -out file.enc
```

Encrypts a file using AES-256 encryption.

### Decrypt a File

```bash
openssl enc -aes-256-cbc -d -in file.enc -out file.txt
```

Decrypts the encrypted file.

---

## Applications

- Secure Communication
- File Encryption
- SSL/TLS Certificate Management
- Data Integrity Verification

---

## Advantages

- Open Source
- Highly Secure
- Cross-platform
- Industry Standard

---

## Learning Outcome

Learned the basics of encryption, decryption, SSL/TLS, and certificate management using OpenSSL.

---

## Screenshot

> Screenshot will be added after completing the practical lab.
