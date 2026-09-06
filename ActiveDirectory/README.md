# Active Directory Lab

## Overview
This lab demonstrates the installation and configuration of Active Directory Domain Services (AD DS) on Windows Server. I created a domain, configured DNS, built an OU structure, added users and groups, and joined a Windows 10 client to the domain.

## Skills Demonstrated
- Installing the AD DS role
- Promoting a server to Domain Controller
- Configuring DNS for the domain
- Creating Organizational Units (OUs)
- Creating users and security groups
- Managing password policies
- Joining Windows 10 to the domain
- Basic Active Directory troubleshooting

## Lab Steps Completed
1. Installed Active Directory Domain Services  
2. Promoted server to Domain Controller  
3. Configured DNS zones  
4. Created OUs (IT, HR, Finance, Students, Admins)  
5. Created user accounts and security groups  
6. Joined Windows 10 VM to the domain  
7. Verified domain connectivity and login  

## Screenshots

### 1. Windows Server 2022 Installation
<img width="920" height="568" alt="Screenshot 2026-08-31 215612" src="https://github.com/user-attachments/assets/a326a176-7558-4421-878c-18c37c31154e" />

### 2. DC01 Server Configuration
<img width="723" height="483" alt="Screenshot 2026-08-31 214149" src="https://github.com/user-attachments/assets/0f7ef4f2-a0ab-4a2c-bf2a-fb9a109b4a75" />

### 3. Static IPv4 Configuration
<img width="473" height="506" alt="Screenshot 2026-08-31 215130" src="https://github.com/user-attachments/assets/624e60ca-0b5e-4afe-8601-f9c64fc44979" />

### 4. Active Directory Domain Services 
Installed the Active Directory Domain Services (AD DS) role on DC01, along with the required management tools and Group Policy Management. This prepares the Windows Server 2022 machine to be promoted to a domain controller.

<img width="1206" height="772" alt="Screenshot 2026-09-06 073915" src="https://github.com/user-attachments/assets/307f4d7e-8fd5-4b69-9292-9c17c59532de" />


### 5. Domain Controller Promotion 
Promoted DC01 to the first domain controller in the new `Abdirahman.local` Active Directory forest. The server now provides centralized domain authentication and Active Directory services for the lab environment.
<img width="1396" height="760" alt="Screenshot 2026-09-06 080100" src="https://github.com/user-attachments/assets/86e31f6e-7bff-4561-9103-b4e9212e8e60" />

### 6. DNS Configuration 
Configured and verified DNS for the Abdirahman.local Active Directory domain. The DNS zone contains the required Active Directory records and a Host (A) record for DC01 pointing to 192.168.245.129.
<img width="1381" height="765" alt="Screenshot 2026-09-06 080916" src="https://github.com/user-attachments/assets/4d02023b-411d-4c29-8bf8-bfd3afcece0b" />

### 7. Organizational Units and Users
Created Organizational Units (OUs) to organize users by department, including IT, HR, Finance, Students, and Admins.
Created an Active Directory user named Ahmed Ali in the IT OU and assigned the role of IT Support Technician.
Created an IT-Users security group to demonstrate group-based user and access management
<img width="1315" height="772" alt="Screenshot 2026-09-06 084102" src="https://github.com/user-attachments/assets/887d1516-341c-425f-807b-7e72af02d751" />

### 8. Windows Client Domain Join

## Tools Used
- Windows Server 2022  
- Windows 10 Enterprise  
- VMware Workstation 

## Why This Lab Matters
Active Directory is the core identity service used in almost every enterprise. This lab demonstrates my ability to deploy, configure, and manage domain services in a real environment.
