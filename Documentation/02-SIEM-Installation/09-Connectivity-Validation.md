# Validating SIEM Connectivity

## Internal Tests

From wazuh-siem:

ping 192.168.1.221

curl -k https://192.168.1.221:9200

Confirmed response from indexer.

---

## Web Interface Test

Opened from host machine:

https://192.168.1.222

Dashboard successfully reachable.

---

## Result

- Dashboard service running  
- Indexer responding  
- Nodes communicating correctly  
- Basic SIEM platform operational  
