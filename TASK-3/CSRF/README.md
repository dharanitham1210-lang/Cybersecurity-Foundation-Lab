# Cross-Site Request Forgery (CSRF)

## Objective
Understand and demonstrate a CSRF vulnerability in a controlled web security lab environment.

## Lab
PortSwigger Web Security Academy – CSRF

## What I Learned
- Understanding how CSRF attacks work
- Identifying requests that perform sensitive actions
- Understanding the role of CSRF tokens
- Learning how token-based protection prevents unauthorized requests

## Demonstration
The vulnerability will be tested in a controlled lab environment.

## Evidence
Screenshots and demonstration video will be added after completing the lab.

## Mitigation
- Use unpredictable CSRF tokens
- Validate CSRF tokens on state-changing requests
- Use appropriate SameSite cookie settings
- Require re-authentication for highly sensitive actions

## Key Takeaway
CSRF exploits the trust a web application places in a user's authenticated browser. Proper CSRF token validation helps prevent unauthorized state-changing requests.
