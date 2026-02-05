# Active Directory Configuration

## Overview

This folder contains documentation and screenshots related to the configuration of **Active Directory (AD)** in the lab environment.

The purpose of this section is to demonstrate proper domain management, organizational structure, and security configuration within a Windows Server Active Directory domain.

---

## Contents

This directory includes:

* Screenshots of Organizational Units (OUs)
* Group policy and delegation configurations
* User and group structure
* Evidence of least privilege delegation
* AD administrative settings

All files serve as proof of correct Active Directory configuration and management practices.

---

## Active Directory Structure

The following core components were implemented:

### Organizational Units (OUs)

* Logical separation of users, groups, and computers
* Department-based OU design
* Proper inheritance of policies
* Delegation of control where appropriate

### Users and Groups

* Role-based security groups
* Users assigned to appropriate groups
* Separation between administrative and standard accounts
* Principle of least privilege applied

### Delegation and Permissions

* Limited administrative delegation to specific OUs
* Restricted permissions based on job function
* No excessive or unnecessary privileges granted

---

## Security Practices Demonstrated

This configuration demonstrates:

* Proper Active Directory design
* Secure user and group management
* Delegated administration
* Least privilege access control
* Enterprise-style domain organization

---

## Purpose

The goal of this configuration is to simulate a real-world domain environment and show understanding of:

* AD management
* Security group design
* Permission delegation
* Organizational best practices

---

## Notes

All configurations shown were performed using standard Windows Server tools such as:

* Active Directory Users and Computers
* Group Policy Management
* Delegation of Control Wizard
