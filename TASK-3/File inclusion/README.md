# File Inclusion

## Objective
Identify and understand File Inclusion vulnerabilities in a controlled web security lab environment.

## Lab
PortSwigger Web Security Academy – File Inclusion

## Vulnerability
File Inclusion occurs when an application improperly handles user-controlled file paths, potentially allowing unintended files to be accessed or included.

## What I Learned
- Understanding Local File Inclusion (LFI)
- Understanding Remote File Inclusion (RFI)
- Identifying vulnerable file parameters
- Understanding the security impact of improper file handling
- Learning techniques to prevent unauthorized file access

## Demonstration
The vulnerability will be tested in a controlled lab environment using a safe proof-of-concept.

## Evidence
Screenshots and demonstration video will be added after completing the lab.

## Mitigation
- Validate and restrict file paths
- Use allowlists for permitted files
- Avoid directly using user input in file paths
- Apply proper access controls
- Disable unnecessary remote file inclusion functionality

## Key Takeaway
Improper file path handling can allow attackers to access or include unintended files. Strong input validation and access controls help prevent File Inclusion vulnerabilities.
