# Vulnerability Scanner Task 
## Task 3

A comprehensive vulnerability assessment of Metasploitable2 using Tenable Nessus scanner, identifying critical security flaws in network services and web applications.

---

## Assessment Overview

**Target**: Metasploitable2 (`192.168.13.5`)  
**Scanner**: Tenable Nessus Essentials  
**Date**: May 29, 2025

---

## Vulnerability Summary

| Severity   | Network Scan | Web App Scan |
|------------|--------------|--------------|
| **Critical** | 5            | 2            |
| **High**     | 4            | 4            |
| **Medium**   | 13           | 13           |
| **Low**      | 6            | 2            |
| **Info**     | 72           | 49           |
| **Total**    | **100**      | **70**       |

---

## Critical Findings

- **Debian SSH/SSL RNG Weakness** (CVSS: 10.0) - Predictable crypto keys
- **VNC Default Password** (CVSS: 10.0) - Remote desktop access
- **PHP-CGI Code Execution** (CVSS: 9.8) - Web shell capability
- **Bind Shell Backdoor** (CVSS: 9.8) - System compromise
- **phpMyAdmin SQLi** (CVSS: 9.8) - Database access

---

## Key Vulnerable Services

- **SSH/SSL** - Weak random number generation  
- **VNC** - Default credentials  
- **Apache/PHP** - Remote code execution  
- **Samba** - Badlock vulnerability  
- **NFS** - World-readable shares  
- **Web Apps** - phpMyAdmin, TWiki, Mutillidae, DVWA



---

## Report Files

- [`my-first-network-scan-_audh5f.pdf`](./my-first-network-scan-_audh5f.pdf) - Network vulnerability scan  
- [`Web-Application-Scan-Task-3_30j7wg.pdf`](./Web-Application-Scan-Task-3_30j7wg.pdf) - Web application assessment

---

> **Educational Use Only**  
> Metasploitable2 is an intentionally vulnerable system for security training.This was used to understand and show different types of vulnerabilities.

---


