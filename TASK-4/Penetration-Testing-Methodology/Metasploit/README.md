# Exploitation with Metasploit

## Objective
Exploit a known vulnerability in Metasploitable2 using the Metasploit Framework in a controlled lab environment.

## Lab Environment
- Attacker: Kali Linux
- Target: Metasploitable2
- Tool: Metasploit Framework

## Methodology

1. Identify the target IP address.
2. Scan the target for open ports and services.
3. Select an appropriate Metasploit exploit.
4. Configure the target and payload.
5. Execute the exploit in the authorized lab.
6. Verify the obtained session.
7. Perform basic post-exploitation enumeration.

## Post-Exploitation
After obtaining a session, basic system information can be collected using:

- `sysinfo`
- `hashdump`

## Security Impact
Successful exploitation demonstrates how an exposed and vulnerable service can provide unauthorized access to a system.

## Mitigation
- Keep operating systems and services patched.
- Disable unnecessary services.
- Restrict network access to vulnerable services.
- Use strong authentication and access controls.
- Regularly perform vulnerability assessments.

## Evidence
Screenshots and demonstration video will be added as proof of concept.

## Key Learning
Learned how Metasploit can be used to validate known vulnerabilities and understand their potential security impact in an authorized lab environment.
