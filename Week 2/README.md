# DevCore Innovations — Enterprise Infrastructure Plan

- **Name:** JamiHyari D. Andaya
- **Course:** Bachelor of Science in Information Technology (BSIT)
- **Section:** BSIT-4A
**Project:** Week 02 – Enterprise Infrastructure Planning

---

## Project Overview

This project presents an initial IT Infrastructure Plan for DevCore Innovations, a fictional software development company with 20 employees.

The project covers:

- Company profile
- Hardware inventory
- Software inventory
- Network inventory
- Enterprise network topology
- System administration roles
- Infrastructure recommendations
- Personal reflection

The purpose of this project is to demonstrate the planning and documentation activities required before deploying an organization's IT infrastructure.

---

## Learning Objectives

This project demonstrates:

- System Administration concepts
- Hardware planning
- Software planning
- Network design
- IT inventory management
- Network security concepts
- Backup planning
- Technical documentation
- GitHub portfolio management

---

## Company Scenario

DevCore Innovations is a fictional software development startup with 20 employees.

| Department | Employees |
|---|---:|
| Information Technology | 5 |
| Human Resources | 4 |
| Finance | 5 |
| Sales | 6 |
| **Total** | **20** |

The company starts with no computers, servers, network infrastructure, internet infrastructure, or security policies.

---

## Hardware Inventory Summary

The proposed infrastructure includes:

- 20 desktop computers
- 3 laptops
- 1 server
- 1 router
- 1 managed switch
- 1 network printer
- 2 UPS units
- 2 wireless access points
- 1 NAS
- 2 external backup drives
- 20 monitors

---

## Software Inventory Summary

The proposed software environment includes:

- Windows 11 Pro
- Ubuntu Server 24.04 LTS
- Microsoft 365 Apps
- Visual Studio Code
- Git
- GitHub Desktop
- VirtualBox
- Google Chrome
- Microsoft Defender
- AnyDesk
- 7-Zip

---

## Network Diagram

The network diagram is stored in the `diagrams/` directory.

![DevCore Innovations Network Diagram](diagrams/network-topology.png)

---

## Network Segmentation

| VLAN | Department/Function |
|---:|---|
| 10 | IT |
| 20 | HR |
| 30 | Finance |
| 40 | Sales |
| 50 | Servers |
| 60 | Guest |
| 99 | Management |

---

## Technologies Used

- Windows 11 Pro
- Ubuntu Server
- Microsoft 365
- Visual Studio Code
- Git
- GitHub
- VirtualBox
- CAT6 Ethernet
- VLANs
- TCP/IP
- Wi-Fi
- Network security
- Backup systems
- Draw.io / diagrams.net
- Markdown

---

## Challenges Encountered

The most challenging part of this project was designing the network topology while considering connectivity, security, department separation, and future expansion.

Another challenge was selecting realistic quantities of hardware for a 20-person startup.

---

## Reflection

This project helped me understand that successful system administration begins with proper planning. I learned that hardware, software, networking, security, backups, and documentation must be considered together before deployment.

The project also helped me understand the importance of network segmentation, centralized services, asset inventories, and disaster recovery planning.

---

## Repository Structure

```text
BSIT-SystemAdministration-Portfolio/
│
└── Week02/
    ├── EnterpriseInfrastructurePlan.pdf
    ├── README.md
    │
    ├── diagrams/
    │   ├── network-topology.drawio
    │   ├── network-topology.png
    │   └── network-topology.pdf
    │
    ├── images/
    │   └── network-diagram-screenshot.png
    │
    └── references/
        └── references.md
