# Dedicated Cybersecurity IDE and Lab Workspace Setup

Author: Kellie Hucker  

---

## Overview

This project documents the setup of a dedicated cybersecurity development environment using Visual Studio Code and a structured CyberLab workspace.

The goal is to create a clean, reproducible, and scalable environment for scripting, detection engineering, and lab management.

---

## Objective

- Configure a dedicated cybersecurity IDE (VS Code)  
- Establish a structured CyberLab workspace  
- Enable scripting across Python, PowerShell, and Bash  
- Set up version control using Git  
- Create a reproducible and organized lab environment  

---

## Workspace Structure
A standardized directory structure was created to organize infrastructure, tooling, scripts, and documentation.

C:\CyberLab\
│
├── Infrastructure\
│   ├── VMs\
│   ├── ISOs\
│   └── NetworkDiagrams\
│
├── BlueTeam\
│   ├── Wazuh\
│   ├── Splunk\
│   ├── Logs\
│   └── Detections\
│
├── RedTeam\
│   ├── Kali\
│   └── AttackScripts\
│
├── AdLab\
│
├── Scripts\
│   ├── Python\
│   ├── PowerShell\
│   └── Bash\
│
├── Tools\
│
├── Wireshark\
│
└── Documentation\
