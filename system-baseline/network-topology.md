# Network Topology

## Overview
The Raspberry Pi is deployed behind an OPNsense firewall within a segmented home lab environment.

## Network Flow
Internet → Router → OPNsense Firewall → Internal VLAN → Raspberry Pi

## Segmentation
- VLAN 10: Management
- VLAN 20: Lab Systems
- VLAN 30: IoT

## Security Controls in Place
- Stateful firewall rules on OPNsense
- NAT enabled
- No direct WAN exposure

## System Boundary
The authorization boundary includes:
- Raspberry Pi 5
- OPNsense firewall
- Internal switching infrastructure

External systems (ISP modem, internet) are outside the authorization boundary.
