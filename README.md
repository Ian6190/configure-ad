# Setting up Active Directory and Domain Lab

## Summary
I configured Active Directory on a domain controller, created a domain admin user, and joined a client computer to the domain.  

### Steps

- **Step 1: Create Domain Admin User**
  - Used Active Directory Users and Computers (ADUC) to create a new domain admin account, assigning it to the **Domain Admins** group for full administrative access.
 
    <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/61ffda64-43c0-4851-97e5-89f635fba136" />

- **Step 2: Join Client to Domain**
  - Configured Client-1 to connect to the domain by setting its DNS to the domain controller’s IP.  
  - Joined Client-1 to the domain and verified that it appeared in Active Directory.  

<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/0f797ab1-45bc-4f26-aaa9-eb9d7073f85a" />
