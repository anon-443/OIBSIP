# Network Scanning with Nmap - Task 01

## Overview
Network scanning report for OASIS Infobyte Cyber Security Internship Task 01. This report documents the network reconnaissance performed on a local virtual machine using Nmap.

## Tools Used
- **Nmap** - Network discovery and security auditing tool
- **Kali Linux** - Penetration testing distribution
- **VirtualBox/VMware** - Virtualization platform

## What is Nmap?
Nmap (Network Mapper) is an open-source tool used for:
- Network discovery and mapping
- Port scanning and service detection
- OS fingerprinting
- Vulnerability assessment
- Security auditing

## Why Network Scanning Matters
- Identifies open ports and running services
- Discovers outdated/vulnerable software
- Maps network attack surface
- Essential for security audits
- Helps in vulnerability assessment

## Ethical Use Guidelines

**✅ DO:**
- Scan only systems you own or have permission to test
- Document all findings
- Follow responsible disclosure

**❌ DO NOT:**
- Scan without authorization (illegal)
- Exploit vulnerabilities without permission
- Use for malicious purposes

## 📊 Scan Results

| Port | Service | Version | Risk Level |
|------|---------|---------|------------|
| 21/tcp | FTP | vsftpd 3.0.5 | 🔴 CRITICAL |
| 22/tcp | SSH | OpenSSH 10.2p1 | 🟡 MEDIUM |
| 80/tcp | HTTP | Apache 2.4.66 | 🟠 HIGH |
| 3306/tcp | MySQL | MariaDB 11.8.6 | 🔴 HIGH |

## 📁 Repository Structure