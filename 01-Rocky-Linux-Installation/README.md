# Project 1 - Rocky Linux Installation

# Project Overview

This project documents the deployment of a Rocky Linux 9.8 server in a virtualized home lab environment.

The goal of this project was to build a Linux server foundation for practicing system administration tasks including user management, networking, security configuration, storage management, and service administration.

This server will serve as the foundation for future Linux administration and security projects.

## Objectives

- Deploy Rocky Linux in VMware Workstation
- Configure a Linux server environment
- Perform initial system configuration
- Practice Linux administration skills
- Create enterprise-style documentation

---

## Lab Environment

### Hardware

- Host OS: Windows 11
- CPU: Intel/AMD Processor
- RAM: 32GB
- Storage: 1TB SSD

### Software

- VMware Workstation
- Rocky Linux 9

---

## Virtual Machine Configuration

VM Name:

rocky-linux-server01

Configuration:

- CPU: 2 vCPU
- RAM: 4GB
- Storage: 40GB
- Network: NAT

---

## Rocky Linux Installation

Steps completed:

1. Created virtual machine
2. Mounted Rocky Linux ISO
3. Installed operating system
4. Created administrator account
5. Completed first boot

---

## Initial Configuration

Completed:

- Verified hostname
- Checked IP address
- Verified SELinux status
- Checked firewall status
- updated system

Commands used:

```bash
hostnamectl
ip addr
getenforce
systemctl status firewalld
 dnf update -y

