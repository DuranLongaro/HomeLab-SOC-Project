# Starting the Indexer Cluster

## Action Performed

On wazuh-collector:

sudo bash wazuh-install.sh --start-cluster -i

---

## Purpose

This initialized:

- Wazuh indexer service  
- Security configuration  
- Cluster communication  

---

## Validation

Service status checked with:

sudo systemctl status wazuh-indexer
sudo ss -lntp | grep 9200

Port 9200 confirmed open and listening.
