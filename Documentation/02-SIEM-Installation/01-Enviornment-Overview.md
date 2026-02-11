# SIEM Installation – Environment Overview

## Purpose

This document describes the environment used to deploy the Wazuh SIEM platform.

The SIEM was implemented as a distributed, two-node architecture inside a home lab virtual network.

---

## Nodes Used

| Role | Hostname | IP Address |
|------|---------|------------|
| Wazuh Indexer | wazuh-collector | 192.168.1.221 |
| Wazuh Dashboard | wazuh-siem | 192.168.1.222 |

---

## Operating System

Both nodes were deployed using:

- Ubuntu Server 22.04 LTS  
- Static internal IP addresses  
- SSH enabled for remote administration  

---

## Deployment Goals

- Install a functional multi-node Wazuh SIEM  
- Separate indexer and dashboard roles  
- Secure communication using certificates  
- Verify full connectivity between components  

