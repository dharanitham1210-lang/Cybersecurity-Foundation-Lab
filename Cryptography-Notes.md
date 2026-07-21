# Cryptography Fundamentals

## Introduction

Cryptography is the practice of securing information by converting plaintext into ciphertext. It protects data from unauthorized access and ensures confidentiality, integrity, and authenticity.

---

# Objectives of Cryptography

- Confidentiality
- Integrity
- Authentication
- Non-Repudiation

---

# Types of Cryptography

## Symmetric Encryption

Symmetric encryption uses the same key for both encryption and decryption.

### Examples

- AES (Advanced Encryption Standard)
- DES (Data Encryption Standard)

### Advantages

- Fast
- Efficient for large amounts of data

### Disadvantages

- Secure key sharing is required.

---

## Asymmetric Encryption

Asymmetric encryption uses two different keys.

- Public Key
- Private Key

### Examples

- RSA
- ECC (Elliptic Curve Cryptography)

### Advantages

- Secure key exchange
- Digital signatures

### Disadvantages

- Slower than symmetric encryption.

---

# Hashing

Hashing converts data into a fixed-length value.

Examples:

- MD5
- SHA-1
- SHA-256

Hashing is mainly used for password storage and integrity verification.

---

# SSL/TLS

SSL (Secure Sockets Layer) and TLS (Transport Layer Security) are protocols used to secure communication over the internet.

Example:

HTTPS uses TLS encryption.

---

# Digital Certificates

A digital certificate verifies the identity of a website or user.

It contains:

- Public Key
- Certificate Owner
- Issuing Certificate Authority (CA)
- Validity Period

---

# OpenSSL

OpenSSL is an open-source tool used for encryption, decryption, certificate generation, and cryptographic operations.

Example command:

```bash
openssl version
```

---

# Conclusion

Cryptography plays a vital role in cybersecurity by protecting sensitive information, securing communications, and verifying data integrity.
