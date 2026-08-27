# SQL Injection

## Objective
Identify and exploit a SQL Injection vulnerability in a controlled web security lab environment.

## Lab
PortSwigger Web Security Academy – SQL Injection

## Vulnerability
The application was vulnerable to SQL Injection through a product category filter.

## What I Learned
- Understanding SQL Injection vulnerabilities
- Identifying injectable input parameters
- Manipulating SQL queries through user-controlled input
- Retrieving hidden/unreleased data
- Understanding the importance of parameterized queries

## Evidence
Screenshots and demonstration video are included as proof of concept.

## Mitigation
- Use prepared statements / parameterized queries
- Validate and sanitize user input
- Apply least-privilege database permissions
- Avoid dynamically constructing SQL queries from user input
