# Enterprise Infrastructure Design

## Overview
This project demonstrates the design and implementation of a small enterprise infrastructure environment for a medium-sized company with 100 employees. The project focuses on infrastructure planning, Linux server administration, file sharing services, system monitoring, and security best practices.

## Objectives

* Design enterprise network architecture
* Implement network segmentation
* Deploy and configure Linux servers
* Implement file sharing services
* Monitor system resources and performance
* Apply infrastructure security controls
* Create professional technical documentation

## Company Structure

* HR
* Finance
* IT
* Marketing

## Infrastructure Components

| Server | Purpose                         |
| ------ | ------------------------------- |
| DC01   | Authentication and DNS Services |
| FILE01 | File Storage and File Sharing   |
| MON01  | Infrastructure Monitoring       |
| SIEM01 | Security Monitoring and Logging |

## Network Design

* VLAN 10 – HR
* VLAN 20 – Finance
* VLAN 30 – IT
* VLAN 40 – Marketing
* VLAN 50 – Server Network

## Architecture Diagram

![Network Topology](diagrams/network-topology.png)

## Security Controls

* Password Policy
* Account Lockout Policy
* Multi-Factor Authentication (MFA)
* Daily Backup Strategy
* Security Logging
* Access Control Management

## Project Phases

### Phase 1 – Infrastructure Design

* Company requirements analysis
* Network architecture design
* Server planning
* Security planning
* Infrastructure documentation

### Phase 2 – File Server Implementation

* Ubuntu Server deployment on UTM
* Samba installation and configuration
* Shared folder creation
* SMB access testing from macOS
* Infrastructure documentation

### Phase 3 – Monitoring and Operations

* htop installation and configuration
* btop installation and configuration
* CPU monitoring
* Memory monitoring
* Disk usage monitoring
* System health verification

## Technologies Used

* Ubuntu Server
* Linux Administration
* Samba
* SMB Protocol
* UTM Virtualization
* htop
* btop
* Git
* GitHub

## Repository Structure

```text
docs/
diagrams/
implementation/
screenshots/
```

## Evidence

Deployment and configuration screenshots are available in the `screenshots` directory.

## Future Enhancements

* Infrastructure Security Hardening
* Firewall Configuration
* Fail2Ban Implementation
* Centralized Logging
* DNS Services
* Monitoring Dashboard
