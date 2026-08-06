# Passive Reconnaissance

## What is Passive Reconnaissance?

Passive reconnaissance is the process of gathering information about a target **without directly interacting with its systems**. Since there is no direct communication with the target, it is difficult for the target to detect this activity.

Passive reconnaissance is usually the first phase of a penetration test or security assessment.

---

## Objectives

- Gather publicly available information
- Identify domain ownership
- Discover DNS records
- Learn technologies used by the target
- Reduce the chances of detection

---

## Common Passive Recon Techniques

### 1. WHOIS

WHOIS provides registration details of a domain.

Information includes:
- Domain registrar
- Registration date
- Expiration date
- Name servers

Example:

```bash
whois example.com
```

---

### 2. NSLOOKUP

NSLOOKUP is used to query DNS records.

Example:

```bash
nslookup example.com
```

It helps identify:
- IP Address
- Mail Servers
- Name Servers

---

### 3. Google Dorking

Google Dorking uses advanced Google search operators to locate publicly available information.

Examples:

```text
site:example.com
filetype:pdf site:example.com
intitle:"index of"
```

---

### 4. Shodan

Shodan is a search engine that indexes internet-connected devices.

It can identify:

- Open ports
- Running services
- Operating systems
- Publicly exposed devices

Website:

https://www.shodan.io

---

## Advantages

- Difficult to detect
- Safe
- No direct communication with target
- Good starting point for assessments

---

## Limitations

- Information may be outdated
- Cannot identify all vulnerabilities
- Depends on publicly available information

---

## Conclusion

Passive reconnaissance is an important first step in understanding a target before performing active security testing.
