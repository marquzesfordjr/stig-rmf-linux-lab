# STIG-Aligned Linux Hardening Lab (RMF-Oriented Project)

## Overview

This project documents the implementation of **DISA STIG-aligned hardening controls** on a Debian-based Raspberry Pi system deployed behind an OPNsense firewall.

The project follows an **RMF-inspired lifecycle**, including:

- System Categorization
- Control Selection
- Control Implementation
- Security Assessment
- Continuous Monitoring

This lab simulates a defense-oriented security environment aligned with NIST 800-53 control families.

---

## Objectives

- Implement STIG-aligned Linux hardening controls  
- Map implemented controls to NIST 800-53 families  
- Perform baseline and post-hardening security assessments  
- Document implementation in a System Security Plan (SSP)-style format  
- Simulate core RMF lifecycle steps  

---

## Lab Architecture

ISP/Modem
↓
- Travel Router (WiFi as WAN)
↓
- OPNsense Firewall (NAT / DHCP / DNS / IDS)
↓
- Switch
↓
- Raspberry Pi 5 (Hardened Debian-Based System)
