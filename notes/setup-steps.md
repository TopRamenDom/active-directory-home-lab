# Active Directory Home Lab Setup

## Lab Overview

Built a Windows Server 2022 Active Directory lab environment using VirtualBox.

---

## Virtual Machines

### Domain Controller
- Name: DC01
- OS: Windows Server 2022
- RAM: 4 GB
- CPU: 2 cores

### Client Machine
- Name: CLIENT01
- OS: Windows 11

---

## Network Configuration

Configured both virtual machines on:
- NAT Network

Assigned static IP to domain controller:
- IP Address: 192.168.10.10
- Subnet Mask: 255.255.255.0
- DNS Server: 192.168.10.10

---

## Active Directory

Installed:
- Active Directory Domain Services (AD DS)

Created:
- homelab.local domain

Promoted DC01 to a Domain Controller.
