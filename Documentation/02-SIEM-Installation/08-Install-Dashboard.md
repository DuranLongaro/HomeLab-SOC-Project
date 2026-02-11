# Installing Wazuh Dashboard

## Action

Performed on node:

wazuh-siem

---

## Command Used

sudo bash wazuh-install.sh --wazuh-dashboard wazuh-siem -i

---

## What This Did

- Installed Wazuh dashboard service  
- Configured certificates  
- Set up HTTPS interface on port 443  
- Connected dashboard to indexer  

---

## Service Validation

sudo systemctl status wazuh-dashboard
sudo ss -lntp | grep 443
