STIG-Aligned Linux Hardening Lab (RMF-Oriented Project)

Overview
This project documents the implementation of DISA STIG-aligned hardening controls on a Debian-based Raspberry Pi system deployed behind an OPNsense firewall. The project follows an RMF-inspired lifecycle including categorization, control selection, implementation, assessment, and monitoring.

Objectives
  Implement STIG-aligned Linux hardening controls
  Map controls to NIST 800-53 families
  Perform baseline and post-hardening security assessments
  Document implementation in an SSP-style format
  Simulate RMF lifecycle steps

Lab Architecture
  OPNsense firewall (NAT, DHCP, DNS, IDS)
  Raspberry Pi 5 (Debian-based OS)
  Isolated LAN subnet
  Travel router providing WAN (campus deployment)

Control Families Implemented
  AC – Access Control
  IA – Identification and Authentication
  AU – Audit and Accountability
  CM – Configuration Management
  SI – System Integrity
  SC – System & Communications Protection

Tools Used
  Lynis (security auditing)
  auditd (event logging)
  OPNsense firewall
  SSH hardening
  PAM policy enforcement
