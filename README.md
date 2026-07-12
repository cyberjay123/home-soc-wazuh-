# home-soc-wazuh-
Home SOC lab using Wazuh for security monitoring, log analysis, and threat detection.


## Overview

This project demonstrates the deployment of a Home Security Operations Center (SOC) using Wazuh. The lab provides centralized log collection, security monitoring, threat detection, and alert investigation capabilities across Windows and Linux systems.

## Objectives

- Deploy a Wazuh SIEM server
- Monitor endpoint activity
- Collect and analyze security logs
- Generate and investigate security alerts
- Develop hands-on SOC analyst skills
- Document installation and troubleshooting procedures

## Technologies Used

### Hardware
- Personal Computer (32GB RAM)

### Software
- Wazuh
- Ubuntu Server
- Windows 11
- VirtualBox

### Security Concepts
- SIEM
- Log Management
- Threat Detection
- Security Monitoring
- Incident Response
- Endpoint Security

## Lab Architecture

Windows Host
│
├── Ubuntu Server VM
│ └── Wazuh Server
│
└── Windows 11 VM
└── Wazuh Agent

## Results

The Home SOC successfully:

- Collected security logs from monitored systems
- Detected security events and generated alerts
- Provided centralized visibility into endpoint activity
- Supported basic incident investigation workflows

## Proof of Functionality

The following screenshots will demonstrate successful deployment:

- Wazuh Dashboard
- Connected Agent
- Security Alerts
- Windows Event Log Collection
- Alert Investigation
- Threat Detection Example

## Skills Demonstrated

- SIEM Administration
- Security Monitoring
- Threat Detection
- Log Analysis
- Incident Response
- Linux Administration
- Windows Administration
- Virtualization
- Technical Documentation

## Future Improvements

- Additional endpoints
- Active Directory integration
- Sysmon deployment
- Custom detection rules
- Vulnerability scanning integration
- Threat intelligence feeds

## Setup Instructions

See SETUP.md for detailed installation and configuration steps.

## Resume Highlights

- Deployed a Wazuh SIEM environment for centralized security monitoring.
- Configured endpoint log collection and alerting capabilities.
- Investigated security events and analyzed system logs.
- Documented deployment procedures and security monitoring workflows.
