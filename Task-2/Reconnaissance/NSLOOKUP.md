# NSLOOKUP

## What is NSLOOKUP?

NSLOOKUP (Name Server Lookup) is a command-line tool used to query the Domain Name System (DNS). It helps retrieve information about domain names, IP addresses, mail servers, and other DNS records.

---

## Why is NSLOOKUP Important?

NSLOOKUP is commonly used during passive reconnaissance to gather DNS information about a target domain without performing intrusive scanning.

---

## Information Retrieved

- IP Address
- Domain Name
- Name Servers (NS)
- Mail Exchange (MX) Records
- Canonical Name (CNAME)
- DNS Records

---

## Basic Syntax

```bash
nslookup <domain_name>
```

Example:

```bash
nslookup example.com
```

---

## Common Commands

### Find IP Address

```bash
nslookup example.com
```

### Find Mail Server (MX Records)

```bash
nslookup -type=MX example.com
```

### Find Name Servers

```bash
nslookup -type=NS example.com
```

### Find IPv6 Address

```bash
nslookup -type=AAAA example.com
```

---

## Advantages

- Easy to use
- Built into most operating systems
- Useful for troubleshooting DNS issues
- Provides valuable DNS information

---

## Limitations

- Only retrieves publicly available DNS information
- Cannot identify vulnerabilities
- Some DNS records may be restricted

---

## Use Cases

- DNS troubleshooting
- Passive reconnaissance
- Domain verification
- Network administration
- Security assessments

---

## Summary

NSLOOKUP is a simple yet powerful tool used to gather DNS-related information about a domain. It is widely used during reconnaissance to understand a target's DNS configuration.
