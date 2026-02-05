# Step 2 – Installing Active Directory Domain Services

## Objective

Install and configure Active Directory Domain Services on Windows Server 2022.

---

## Steps Performed

1. Opened **Server Manager**  
2. Selected **Add Roles and Features**  
3. Installed the following roles:
   - Active Directory Domain Services  
   - DNS Server  

4. After installation completed, selected:

**“Promote this server to a domain controller”**

---

## Domain Configuration

- Selected: **Add a new forest**  
- Created domain: lab.local

---

- Set DSRM password  
- Completed wizard  
- Rebooted the server  

---

## Verification

After reboot:

- Logged in as: LAB\Administrator

- Confirmed access to:
  - Active Directory Users and Computers  
  - DNS Manager  
  - Group Policy Management  

---

## Result

A fully functional domain controller running the lab.local domain.




