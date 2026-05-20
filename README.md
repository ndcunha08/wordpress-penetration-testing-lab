# WordPress Penetration Testing Lab

## Overview
This project demonstrates a WordPress penetration testing lab completed in a controlled VirtualBox environment using Kali Linux and an Ubuntu target machine.

## Objectives
- Perform network reconnaissance
- Enumerate WordPress services
- Identify security weaknesses
- Demonstrate exploitation in a lab environment
- Recommend remediation steps

## Tools Used
- Kali Linux
- Nmap
- Gobuster
- WPScan
- Hydra
- Curl
- VirtualBox

## Lab Environment
- Attacker Machine: Kali Linux
- Target Machine: Ubuntu Server running WordPress
- Network: VirtualBox Host-Only Network
- IP Range: 192.168.56.0/24

## Project Steps
1. Reconnaissance
2. Service enumeration
3. WordPress enumeration
4. Exploitation testing
5. Command execution validation
6. Remediation recommendations

## Key Findings
- WordPress was exposed on the lab network
- Weak authentication controls were tested
- Theme file editing allowed command execution in the lab
- System access was limited to the web server user

## Remediation
- Update WordPress, themes, and plugins
- Disable theme file editing
- Enforce strong passwords and MFA
- Restrict file permissions
- Monitor logs for suspicious activity

## Disclaimer
This project was performed in a private lab environment for educational purposes only.
