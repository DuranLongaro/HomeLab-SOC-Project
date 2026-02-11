# Transferring Certificates to Node 2

## Purpose

The generated install package must be copied from the collector node to the dashboard node.

---

## Command Used

From wazuh-collector:

sudo scp /home/meatball/wazuh-install-files.tar vboxuser@192.168.1.222:/home/vboxuser/

---

## Verification on Node 2

After transfer, on wazuh-siem:

ls -l /home/vboxuser/wazuh-install-files.tar

File presence confirmed before continuing.
