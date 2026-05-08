# SOC-Home_lab_Setup
Virtualized SOC home lab built with VMware Ubuntu 24.04 and windows 10 for network analysisi, SEIM deployment and incident response simulation

Project 1 — SOC Home Lab Setup
Overview
A virtualized two machine SOC home lab built using VMware Workstation Player. 
This environment serves as the foundation for network traffic analysis, SIEM 
deployment, and incident response simulation projects.

Environment Specifications
 Host Machine
- OS: Windows 10
- RAM: 16GB
- Storage: 2TB

Virtual Machine 1 — Ubuntu 24.04 LTS
- RAM: 4GB
- Storage: 50GB
- Purpose: Security tools, packet analysis, log management

Virtual Machine 2 — Windows 10 Pro
- RAM: 4GB
- Storage: 60GB
- Purpose: Target machine, Windows event log generation

Tools Installed (Ubuntu VM)
- Wireshark — network packet capture and traffic analysis
- Nmap — network scanning and port enumeration
- Net-tools — network configuration utilities
- Curl — command line data transfer
- Git — version control
- Open VM Tools — VMware guest utilities

Steps Taken
1. Downloaded and installed VMware Workstation Player
2. Downloaded Ubuntu 24.04 LTS ISO and created Ubuntu VM
3. Configured Ubuntu VM with 4GB RAM and 50GB storage
4. Updated Ubuntu and installed security tools via apt
5. Downloaded Windows 10 ISO via Microsoft Media Creation Tool
6. Created Windows 10 VM with 4GB RAM and 60GB storage
7. Installed VMware Tools on both VMs for enhanced performance
8. Took clean baseline snapshots of both VMs

Challenges & Troubleshooting
- Resolved apt syntax errors during tool installation
- Manually mounted VMware Tools ISO on Windows VM
- Configured RAM allocation to balance performance across both VMs

Skills Demonstrated
- Hypervisor configuration and VM deployment
- Linux command line usage
- Resource management and system configuration
- Troubleshooting and problem solving
- Security lab environment design

 Next Project
Project 2 — Network Traffic Analysis with Wireshark

