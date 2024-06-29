# BC_PT
BC_PT Penetration Testing Framework (Cyber Security)
# Link To Video
[Click here to view the project video documentation](https://drive.google.com/file/d/1BKPeTrU0B7JjzzwQpRdPwEccmnwrEbKD/view)

## Overview
BC_PT is a comprehensive penetration testing framework that automates various security assessments using multiple tools.
[Click here to view the detailed project documentation (PDF)](https://github.com/Barel-cohen/BC_PT/blob/main/BC_PT-PDF-Github.pdf)

## Features
- **Network Scans**: TCP and UDP scanning using nmap and masscan.
- **Web Scans**: Web vulnerability scanning using dirb and nikto
- **Passive Scans**: Non-intrusive information gathering using whois and ipinfo.io.
- **Enumerating Scans**: Information gathering from Windows and Samba systems using enum4linux.
- **Weak Credentials Testing**: Password cracking using Hydra.
- **Anonymous Scanning**: Use of TOR and NIPE for anonymous scans.
- **Service Vulnerability Scanner**: Enhance vulnerability detection with nmap NSE for targeted scans.
- **Exploit Analysis**: Use searchsploit to find and analyze exploits based on scan results.

This advanced framework is tailored to elevate penetration testing initiatives, ensuring comprehensive vulnerability assessment and strategic exploit validation to bolster organizational security posture and readiness against cyber threats.

## WorkFlow & Menu 
![image](https://github.com/Barel-cohen/BC_PT/assets/138814830/74442a48-eb64-4e59-b643-5e2be76bd594)
![image](https://github.com/Barel-cohen/BC_PT/assets/138814830/8917e273-e522-4938-b167-610ae0c7e8d6)





**Create Working Directory:** Prompt user to name the folder for storing information, fixed at BC_PT-DB on the Desktop.

**Logging and Auditing:** Log file BC_PT.log records all scan details, located at /var/log.

**Logging Details**

Timestamp: Date and time of the scan

Scan Type: Basic, Full, Passive, Web, Enumeration

Target Information: IP addresses/IP Range, URLs

Anonymity Status: Real or anonymous IP address


## Conclusions
The BC_PT framework represents a sophisticated and structured approach to penetration testing, effectively leveraging automation and the integration of multiple tools to achieve thorough and comprehensive security assessments. By utilizing this framework, penetration testers and users can significantly enhance their ability to identify and mitigate potential security risks within their networks and web applications.
By following the BC_PT framework, penetration testers and security professionals can improve their operational efficiency and effectiveness, ultimately enhancing the overall security posture of the organizations they serve.


## Key Advantages
**Efficiency:** Automation streamlines the testing process, allowing for rapid and consistent identification of vulnerabilities.
**Comprehensive Coverage:** By integrating a diverse array of tools, the framework ensures a wide-ranging detection of vulnerabilities. This includes everything from weak credentials to network misconfigurations and web application flaws, providing a holistic security assessment.
**User-Friendly:** The organized structure of the framework simplifies the testing process, making it accessible even to those with limited penetration testing experience.
**Scalability:** The framework can easily adapt to different environments and scales of operation, from small networks to large enterprise systems.
**Detailed Reporting:** The framework provides detailed and organized reports

## Installation and Running
1. Ensure you have the necessary permissions:
2. chmod 744 BC_PT.sh
4. sudo ./BC_PT.sh
