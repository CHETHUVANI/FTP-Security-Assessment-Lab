<<<<<<< HEAD
# FTP-Security-Assessment-Lab
FTP penetration testing lab using Kali Linux and Ubuntu vsftpd
=======
# FTP Security Assessment Lab

## Overview

A penetration testing lab demonstrating FTP security assessment on an Ubuntu server running vsftpd.

## Environment

Attacker:
- Kali Linux

Target:
- Ubuntu Server

## Tools Used

- Nmap
- FTP Client
- Gobuster
- Nikto

## Assessment Steps

1. Service Enumeration
2. FTP Anonymous Login Testing
3. File Upload Testing
4. Sensitive Data Exposure Analysis
5. Web Server Enumeration

## Findings

### Anonymous FTP Login Enabled

Severity: Medium

Anonymous users were able to access FTP resources.

### Anonymous FTP Upload Enabled

Severity: High

Anonymous users were able to upload files.

### Sensitive File Exposure

Severity: High

Backup files were accessible through FTP.

## Remediation

- Disable anonymous FTP access
- Restrict FTP permissions
- Remove sensitive files
- Use SFTP/FTPS
>>>>>>> 5c28a83 (Added project documentation README)
