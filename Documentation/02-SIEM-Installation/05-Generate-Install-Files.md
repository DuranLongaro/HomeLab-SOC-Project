# Generating Installation Files

## Purpose

The Wazuh installer requires a certificate package to be created before installation.

---

## Command Used

On wazuh-collector:

sudo bash wazuh-install.sh --generate-config-files -i

---

## Result

This command generated:

wazuh-install-files.tar

Containing:

- SSL certificates  
- Cluster keys  
- Password files  
- config.yml  

---

## Verification

Contents were verified using:

sudo tar -tf wazuh-install-files.tar
