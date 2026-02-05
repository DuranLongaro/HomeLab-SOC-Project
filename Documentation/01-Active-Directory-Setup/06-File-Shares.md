# Step 6 – File Shares and Permissions

## Objective

Implement shared folders with least-privilege access control.

---

## Shared Folders Created

C:\Shares\IT
C:\Shares\Finance
C:\Shares\Sales
C:\Shares\HR

---

## Permission Configuration

### Share Permissions

- Access granted based on department groups  
- Default “Everyone – Full Control” removed  

### NTFS Permissions

- IT_Group → Access to IT folder  
- Finance_Group → Access to Finance folder  
- Sales_Group → Access to Sales folder  
- HR_Group → Access to HR folder  

No group was given unnecessary permissions.

---

## Security Principle

This configuration follows:

**Least Privilege Access Control**

Users can only access resources required for their role.

---

## Testing

- Confirmed each user could access only their department folder  
- Verified unauthorized access was denied  

---

## Result

Secure file sharing environment integrated with Active Directory.
