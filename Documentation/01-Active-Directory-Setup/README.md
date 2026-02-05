# Active Directory Lab – lab.local

## Overview

This section of the project documents the complete setup and configuration of an Active Directory environment built using **Windows Server 2022** in **VMware**.

The goal of this lab was to:

- Deploy a Windows Server domain controller  
- Configure Active Directory Domain Services  
- Organize users using Organizational Units  
- Implement least-privilege access control  
- Join client machines to the domain  

---

## Environment Details

- Hypervisor: VMware  
- Operating System: Windows Server 2022  
- Domain Name: lab.local  
- Server Role: Domain Controller + DNS  
- Network: Static IP addressing  

---

## Organizational Structure

The following Organizational Units (OUs) were created:

- IT  
- Finance  
- Sales  
- HR  

Each OU contains users and security groups specific to that department.

---

## Documentation Sections

This Active Directory setup is broken into the following steps:

1. VMware and Server Installation  
2. AD DS Role Installation  
3. OU Structure Creation  
4. User and Group Configuration  
5. Domain Joining Clients  
6. File Shares and Permissions  

---

## Purpose

This lab serves as the foundation for the rest of the SOC project, including:

- SIEM deployment  
- Log collection  
- Alert creation  
- Incident response testing  
