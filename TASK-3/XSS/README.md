# Cross-Site Scripting (XSS)

## Objective
Identify and demonstrate Cross-Site Scripting vulnerabilities in a controlled web security lab environment.

## Vulnerability
XSS occurs when an application includes untrusted user input in a web page without proper validation or output encoding, allowing injected scripts to execute in a victim's browser.

## Lab
PortSwigger Web Security Academy – Cross-Site Scripting (XSS)

## What I Learned
- Understanding the basics of XSS vulnerabilities
- Identifying user-controlled input points
- Understanding Reflected and Stored XSS
- Testing how injected input is processed by the application
- Understanding the impact of client-side script execution
- Learning basic XSS prevention techniques

## Demonstration
The vulnerability was tested in a controlled lab environment using a safe proof-of-concept payload.

## Evidence
Screenshots and demonstration video are included as proof of concept.

## Mitigation
- Properly validate user input
- Encode output before displaying user-controlled data
- Implement Content Security Policy (CSP)
- Use secure frameworks and templating mechanisms
- Avoid inserting untrusted data directly into HTML or JavaScript contexts

## Key Takeaway
XSS demonstrates how improper handling of user input can allow unintended JavaScript execution in a user's browser. Proper input handling and output encoding are essential for preventing XSS attacks.
