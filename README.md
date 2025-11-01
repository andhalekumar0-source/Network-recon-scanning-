# Network-recon-scanning-
A cybersecurity internship project demonstrating ethical network reconnaissance and scanning using Netdiscover and Nmap in a controlled lab environment. Includes host discovery, port scanning, service detection, and a detailed report with methodology, findings, and remediation steps.

# Network Reconnaissance & Scanning — Internship Task

*Author:* Kumar Andhale  
*Date:* 2025-11-01

> This repository contains lab-based reconnaissance and scanning exercises using netdiscover and nmap.
> All scans were performed on authorized lab machines (no unauthorized networks).

## Contents
- scans/ — saved outputs from Netdiscover and Nmap (redacted if required)
- report/ — written report with findings and remediation
- scripts/ — helpful automation scripts to reproduce the scans in a lab

## Tools & Versions
- netdiscover (version: included in Kali)
- nmap (version: included in Kali)

## How to reproduce (lab only)
1. Boot Kali VM and target VMs in an isolated host-only network.
2. Run discovery:
   ```bash
   sudo netdiscover -r 192.168.56.0/24 -P -o netdiscover_192.168.56.0-24.txt
