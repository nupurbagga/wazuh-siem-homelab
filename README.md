# Wazuh SIEM Homelab

![Platform](https://img.shields.io/badge/Platform-VirtualBox-blue)
![OS](https://img.shields.io/badge/OS-Parrot%20%7C%20Windows-orange)
![Security](https://img.shields.io/badge/Security-SIEM-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

<img width="391" height="210" alt="wazuh-siem drawio (1)" src="https://github.com/user-attachments/assets/28dc5d44-3d01-4d37-98db-6ecc1c00ef2f" />


## Overview
Cybersecurity homelab using Wazuh SIEM running on Parrot OS to monitor file integrity and security events on Windows endpoint

## Tools
| Tool | Purpose |
| ---- | ------- |
| VirtualBox | Virtualization Platform |
| Parrot OS | Wazuh Manager |
| Windows 11 | Monitored Endpoint |
| Wazuh Manager | Security Information and Event Management (SIEM) |
| Wazuh Agent | Endpoint Monitoring |
| Syscheck | File Integrity Monitoring |
| Linux | Server Administration |

## Objectives
- Deploy a Wazuh SIEM platform
- Register Windows endpoint with Wazuh Manager
- Configure File Integrity Monitoring in real-time
- Generate security alerts
- Monitor activity through Wazuh dashboard

## Skills demonstrated
- Security Information and Event Management (SIEM)
- File Integrity Monitoring (FIM)
- Log Analysis
- Linux Administration
- Windows Administration
- Security Event Monitoring
- Network Troubleshooting


## Setup

### Wazuh Manager
- Installed and configured Wazuh Manager on Parrot OS
- Accessed Wazuh Dashboard

### Endpoint Configuration
- Installed Wazuh agent on Windows endpoint
- Registered Wazuh Agent with the Wazuh Manager
- Established secure communication between the Manager and Agent

### File Integrity Monitoring
- Enabled Syscheck for real-time monitoring
- Configured Windows desktop repository for File Integrity Monitoring 

## Testing
- Created, modified and deleted files within the repository
- Verified that events were detected by the Wazuh Agent
- Confirmed alerts were generated and displayed in the Dashboard
- Validated communication was successful between Windows Agent and Wazuh Manager

## Results
Successfully deployed and configured Wazuh SIEM environment to monitor Windows endpoint in real-time

Wazuh SIEM successfully:
- Detected file creation, modification and deletion
- Generated real-time security alerts
- Established secure communication between Wazuh Manager and Agent

## What I Learned
- Deploying and configuring SIEM platform
- Configuring File Integrity Monitoring using Syscheck
- Analysing security events using Wazuh Dashboard
- Troubleshooting Linux, Windows, networking and agent connectivity issues
