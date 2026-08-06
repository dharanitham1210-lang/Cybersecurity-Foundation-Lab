# WHOIS

## What is WHOIS?

WHOIS is a protocol and lookup service used to retrieve publicly available registration information about a domain name or IP address. It helps identify ownership and administrative details of a domain.

---

## Why is WHOIS Important?

WHOIS is commonly used during the reconnaissance phase of a security assessment because it provides valuable information without directly interacting with the target's systems.

---

## Information Provided by WHOIS

- Domain Name
- Domain Registrar
- Registration Date
- Expiration Date
- Updated Date
- Name Servers
- Registrant Information (if public)
- Administrative Contact
- Technical Contact

> **Note:** Many domain owners use privacy protection services, so personal details may be hidden.

---

## Command

```bash
whois example.com
```

---

## Example

```bash
whois openai.com
```

The output may include:

- Registrar
- Name Servers
- Creation Date
- Expiration Date
- Domain Status

---

## Advantages

- Easy to use
- Publicly available
- No direct interaction with the target
- Useful for gathering domain information

---

## Limitations

- Personal information may be hidden due to privacy protection.
- Some records may not be fully up to date.
- Does not reveal system vulnerabilities.

---

## Use Cases

- Domain ownership verification
- Security investigations
- Penetration testing
- Incident response
- Digital forensics

---

## Summary

WHOIS is one of the first tools used during passive reconnaissance to gather domain registration information. It provides valuable insights while remaining non-intrusive.
