# Troubleshooting Log

## Issues Encountered

### 1. Missing Certificates Error

Error:
"There is no certificate for the Wazuh dashboard node"

Cause:
Install package not properly transferred or extracted.

Fix:
Regenerated install files and recopied to node 2.

---

### 2. Dashboard Not Starting

Error:
"Cannot connect to Wazuh dashboard"

Fix:
Verified indexer was running and reachable on port 9200.

---

### 3. Network Connectivity Drops

Observed intermittent:
Destination Host Unreachable

Fix:
VM network adapter reset - set to bridged instead of NAT and static IP reconfirmed.

---

## Final Outcome

After corrections:

- Indexer online  
- Dashboard installed  
- Web interface accessible  
- Cluster communication confirmed  
