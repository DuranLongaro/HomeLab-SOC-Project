# Least_Privilege

## Project Overview

This repository section documents the implementation of the **Principle of Least Privilege** within a Windows Active Directory and file server environment.

The screenshots included demonstrate how access to shared resources was restricted so that users and groups are granted only the minimum permissions required to perform their tasks.

---

## Objective

The purpose of this configuration is to show:

* Proper use of Share Permissions
* Proper use of NTFS Permissions
* Separation of duties using security groups
* Real-world least privilege access control practices

---

## Files Included

This folder contains the following documentation screenshots:

* `share_permissions_settings.png` – Configuration of network share permissions
* `ntfs_permissions_settings.png` – Configuration of NTFS security permissions

Each image provides visual proof of correct permission structure and access control.

---

## Implementation Details

### Share Permissions

* Share permissions were configured on the file server
* Access was limited to authorized security groups
* No unnecessary Full Control permissions were granted
* Permissions follow the principle of least privilege

### NTFS Permissions

* NTFS permissions were used as the primary security control
* Users were given only the access required for their role
* Modify and Write permissions were restricted
* Read-only access was used whenever possible

### Security Approach

* Permissions were assigned to groups instead of individual users
* Access control was layered using both Share and NTFS permissions
* Administrative privileges were limited to authorized accounts only

---

## Security Principles Demonstrated

This configuration demonstrates understanding of:

* Least Privilege
* Role-Based Access Control (RBAC)
* Defense in Depth
* Windows file system security
* Proper enterprise permission management
