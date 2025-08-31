# Deploying Active Directory in Azure

## Lab Summary
In this lab, I set up Active Directory using two Azure VMs (DC-1 and Client-1).  

### Part 1: Setting up Active Directory and Domain
- **Step 1:** Installed Active Directory on DC-1 and created a new domain called mydomain.com.
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/48f125b2-3070-445e-bb65-678d878c6e62" />


- **Step 2:** Made two folders in AD: _EMPLOYEES and _ADMINS.
- 
  <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/8609e347-47c3-4339-8980-4c514123a919" />
   
- **Step 3:** Created a new admin user jane_admin, added it to Domain Admins, and logged in as that user.

    <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/1fad708d-1451-40af-9505-177fced8f702" />
- **Step 4:** Connected Client-1 to the domain and placed it inside a new OU called _CLIENTS.

  <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/83241323-ed95-4395-87e1-af8a56bae8c4" />

### Part 2: Adding Users and Remote Access
- **Step 5:** Allowed Domain Users to log in to Client-1 with Remote Desktop.  
- **Step 6:** Used PowerShell to create a bunch of new users in `_EMPLOYEES`, checked them in AD, and logged into Client-1 with one of those accounts.  

---

## Related Labs
- [Configuring On-premises Active Directory within Azure VMs](https://github.com/Ian6190/configure-ad)  
- [Network Security Groups (NSGs) and Inspecting Network Protocols](https://github.com/Ian6190/azure-network-protocols)  
