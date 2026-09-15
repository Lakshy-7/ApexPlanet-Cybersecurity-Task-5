# ApexPlanet Task 5 — DVWA Web Application Pentest

## Project Overview

This project presents a controlled web application security assessment
of the Damn Vulnerable Web Application (DVWA) in a local Kali Linux lab.

## Objective

The objective was to assess the security of the DVWA application,
identify security weaknesses, collect technical evidence, and document
appropriate mitigation and incident-response actions.

## Scope

- Target: Local DVWA installation
- Environment: Kali Linux
- Web Server: Apache
- Database: MariaDB
- Testing restricted to the authorized local laboratory environment

## Tools Used

- Kali Linux
- DVWA
- Apache
- MariaDB
- Nmap
- cURL
- Browser
- Apache access logs

## Methodology

1. Project planning
2. Lab and application verification
3. Network and service reconnaissance
4. Web application assessment
5. Evidence collection
6. Finding and risk documentation
7. Incident detection through access logs
8. Simulated containment and recovery
9. Post-incident documentation

## Key Findings

### SQL Injection
A controlled SQL Injection test was performed against the DVWA
SQL Injection functionality. The corresponding request was also
identified in the Apache access log.

### Web Application Exposure
The intentionally vulnerable DVWA application was accessible through
the local Apache web server.

### Log Monitoring
Apache access logs provided useful evidence for identifying suspicious
requests during the assessment.

## Incident Response

The simulated SQL Injection activity was identified through Apache logs.
Apache was temporarily stopped as a containment action and subsequently
restarted to recover the lab environment.

## Mitigation

- Use prepared/parameterized SQL statements.
- Validate and sanitize user input.
- Apply least-privilege database permissions.
- Monitor web-server logs for suspicious requests.
- Restrict vulnerable applications to authorized testing environments.
- Maintain secure web-server configuration.

## Evidence

Screenshots and supporting files are maintained in the project evidence
directory.

## Disclaimer

This project was performed only in an authorized, isolated laboratory
environment using DVWA for cybersecurity training and educational
purposes. No unauthorized systems were targeted.
 ## LINKDIN VIDEO LINK [https://lnkd.in/p/dtGej7KT?utm_source=chatgpt.com](https://www.linkedin.com/posts/lakshy-choudhary-728250318_cybersecurity-ethicalhacking-websecurity-ugcPost-7505709060214931458-PVJq/)
