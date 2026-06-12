# Enterprise Infrastructure Design

## Overview

Designed and implemented a small enterprise infrastructure environment for a medium-sized company with 100 employees.

The project focuses on infrastructure architecture, Linux server administration, file sharing services, monitoring, and security hardening. The environment was deployed using Ubuntu Server on UTM virtualization and documented using industry-standard infrastructure documentation practices.

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

## Architecture

### Infrastructure Components

| Server | Purpose                         |
| ------ | ------------------------------- |
| FILE01 | File Storage and File Sharing   |
| MON01  | Infrastructure Monitoring       |
| SIEM01 | Security Monitoring and Logging |
| DC01   | Authentication and DNS Services |

### Network Design

* VLAN 10 – HR
* VLAN 20 – Finance
* VLAN 30 – IT
* VLAN 40 – Marketing
* VLAN 50 – Server Network

### Architecture Diagram

![Network Topology](diagrams/network-topology.png)

## Security Controls 
* Password Policy 
* Account Lockout Policy 
* Multi-Factor Authentication (MFA) 
* Daily Backup Strategy 
* Security Logging 
* Access Control Management

## Implementation

### File Services

* Ubuntu Server 24.04 LTS deployment
* Samba file sharing configuration
* SMB access from macOS clients
* Shared folder management

### Monitoring

* htop
* btop
* CPU monitoring
* Memory monitoring
* Disk utilization monitoring

### Security Hardening

* UFW Firewall
* SSH protection
* SMB access control
* Fail2Ban intrusion prevention

## Technologies Used

* Ubuntu Server
* Samba
* Linux Administration
* UTM
* htop
* btop
* UFW
* Fail2Ban
* Git
* GitHub

## Repository Structure

docs/
diagrams/
implementation/
screenshots/

## Key Outcomes

* Successfully deployed a Linux-based file server environment.
* Implemented monitoring and operational visibility for system resources.
* Applied security controls to protect infrastructure services.
* Produced technical documentation and infrastructure diagrams.

## Lessons Learned

* Linux Server Administration
* Infrastructure Design
* Security Hardening
* Monitoring and Operations
* Technical Documentation
* Git and GitHub Workflow


