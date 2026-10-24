# IqraSec Academy — Phase 2 VAPT Project

## Overview
This project documents a lab-based Vulnerability Assessment and Penetration Testing (VAPT) exercise using Kali Linux and Metasploitable 2 in Oracle VirtualBox.

## Objectives
- Identify exposed network services using Nmap.
- Enumerate FTP and HTTP services.
- Review a deliberately vulnerable web application in the lab.
- Record findings, evidence, limitations, and remediation recommendations.

## Tools Used
- Kali Linux
- Metasploitable 2
- Oracle VirtualBox
- Nmap
- Metasploit Framework
- DVWA (Damn Vulnerable Web Application)

## Repository Structure
- `01_Screenshots/` — Evidence screenshots
- `02_Scan_Results/` — Scan output and enumeration logs
- `03_Report/` — VAPT report in PDF and Word formats

## Key Observations
- FTP service banner identified as vsftpd 2.3.4; the result requires careful validation and should be interpreted alongside the recorded test evidence.
- HTTP service and server headers were enumerated.
- phpMyAdmin displayed an mcrypt-extension warning.
- DVWA baseline behavior was observed at the configured security level.

## Scope and Ethics
All testing was intended for the deliberately vulnerable local lab environment. Do not use these techniques against systems without explicit authorization.

## Deliverables
The report and supporting evidence are provided in the folders above.

