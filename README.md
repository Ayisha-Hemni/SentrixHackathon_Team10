           
# Sentrix Hackathon - Day 1 Implementation

## Overview
This project implements a basic Security Operations Center (SOC) simulation using virtualized i>

## Components
- Kali Linux (Attack VM)
- Ubuntu Target VM
- Suricata IDS (Network Intrusion Detection System)
- Wazuh (SIEM)
- Docker-based security stack (Wazuh indexer, dashboard, manager)

## Suricata Rules
Custom IDS rules were implemented to detect:
- ICMP reconnaissance activity
- SSH connection attempts
- HTTP traffic monitoring
- SYN scan detection (Nmap simulation)
- SSH brute force patterns

## Network Setup
- Host-only network for VM communication
- Bridged adapter for external connectivity testing

## Current Status (Day 1)
- Virtual environment setup completed
- IDS rules configured
- Initial attack simulation tested (Nmap)
- SIEM setup is done (Wazuh Docker)

## Notes
This is an evolving SOC pipeline designed for multi-stage attack detection and correlation acro>



