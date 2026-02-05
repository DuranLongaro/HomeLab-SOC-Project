# Step 1 – VMware and Windows Server Installation

## Objective

Install Windows Server 2022 as a virtual machine to serve as the domain controller.

---

## Process

1. Open VMware and create a new virtual machine  
2. Mount Windows Server 2022 ISO  
3. Configure virtual hardware:
   - 2–4 CPU cores  
   - 4–8 GB RAM  
   - 60–80 GB disk  

4. Install Windows Server 2022 with **Desktop Experience**

---

## Post-Installation Configuration

- Assigned a static IP address  
- Configured subnet mask and gateway  
- Set DNS server to point to itself  
- Renamed the server to: DC1

---

- Rebooted to apply changes  

---

## Result

A properly configured Windows Server 2022 VM ready for Active Directory installation.

