# Active Directory Home Lab

## Overview

This project documents the creation of a virtualized Active Directory environment designed to simulate common tasks performed by IT Support and Help Desk professionals in an enterprise environment. The purpose of this lab was to gain hands-on experience with user management, domain administration, authentication, and endpoint management using Windows Server and Active Directory Domain Services.

Through this project, I developed a better understanding of how organizations centrally manage users, computers, security policies, and access permissions across a networked environment.

---

## Lab Environment

The lab environment consisted of:

- Windows Server 2022 acting as the Domain Controller
- Windows 11 acting as a domain-joined workstation
- Active Directory Domain Services (AD DS)
- DNS services
- Oracle VirtualBox virtual machines

This environment was built to closely resemble the infrastructure commonly found in small and medium-sized business environments.

---

## Project Objectives

The primary objectives of this project were:

- Deploy and configure Active Directory Domain Services.
- Promote a Windows Server instance to a Domain Controller.
- Create and manage user accounts within Active Directory.
- Configure organizational units and security groups.
- Join a Windows 11 workstation to the domain.
- Verify successful authentication using domain credentials.
- Gain familiarity with enterprise identity and access management concepts.

---

## Tasks Completed

During the lab, I completed the following tasks:

### Active Directory Deployment
- Installed the Active Directory Domain Services role on Windows Server.
- Configured the server as a Domain Controller.
- Verified successful deployment of Active Directory services.

### User and Computer Management
- Created user accounts within Active Directory Users and Computers.
- Configured user account properties and login settings.
- Verified that newly created users could authenticate successfully.
- Confirmed that domain-joined computers appeared correctly within Active Directory.

### Domain Join and Authentication
- Joined a Windows 11 workstation to the newly created domain.
- Logged into the workstation using domain credentials.
- Verified communication between the endpoint and the Domain Controller.

### Administrative Verification
- Tested authentication functionality.
- Confirmed that the workstation could locate and communicate with the Domain Controller.
- Verified that Active Directory objects were being properly created and managed.

---

## Screenshots and Evidence

### Windows Server Environment
This screenshot shows the Windows Server environment used as the foundation of the lab infrastructure.

![Windows Server Environment](images/windows-server-setup.png)
<img width="1031" height="773" alt="Screenshot 2026-04-30 015540" src="https://github.com/user-attachments/assets/c978e9cf-ebe2-4917-b8f9-0920644f23dc" />


---

### Active Directory Users and Computers
This screenshot shows the Active Directory Users and Computers console where user accounts, organizational units, and computer objects were managed.

![Active Directory Users and Computers](images/ad-users-and-computers.png)
<img width="2048" height="1151" alt="Screenshot 2026-04-30 020401" src="https://github.com/user-attachments/assets/749b7838-2c53-48e0-96ea-09fc7148acad" />


---

### User Account Creation
This screenshot demonstrates the successful creation and configuration of a domain user account.

![User Account Creation](images/user-created.png)
<img width="2048" height="1152" alt="Screenshot 2026-04-30 020118" src="https://github.com/user-attachments/assets/ad5ae04c-6a6f-4ce9-b59c-4d1b95ea5d24" />

---

### Domain Join Verification
This screenshot confirms that the Windows 11 workstation was successfully joined to the Active Directory domain.

![Domain Join](images/domain-join.png)

---<img width="2048" height="1152" alt="Screenshot 2026-06-29 170213" src="https://github.com/user-attachments/assets/09615f6c-79c5-4a90-bb7d-294e2216da76" />



### Domain Authentication
This screenshot demonstrates successful authentication using domain credentials.

![Domain Login](images/domain-user-login.png)

---<img width="2048" height="1152" alt="Screenshot 2026-06-29 170555" src="https://github.com/user-attachments/assets/4caf0313-5963-4721-8fa2-7983121934c8" />


### Computer Object Verification
This screenshot confirms that the workstation was properly registered within Active Directory after joining the domain.

![Computer Object Verification](images/computer-in-domain.png)

---

## Skills Demonstrated

Throughout this project I gained hands-on experience with:

- Active Directory Administration
- Windows Server Administration
- User Provisioning
- Endpoint Management
- Identity and Access Management (IAM)
- Domain Authentication
- Windows Troubleshooting
- Enterprise User Lifecycle Management

---

## Lessons Learned

One of the biggest takeaways from this project was understanding how heavily organizations rely on Active Directory for centralized identity and access management. Prior to building this environment, concepts such as domain controllers, domain authentication, and user provisioning were primarily theoretical.

By creating and managing my own Active Directory environment, I gained practical experience with the processes that IT Support and Help Desk professionals perform on a daily basis, including creating users, managing access, joining systems to a domain, and troubleshooting authentication issues.

This project significantly improved my understanding of enterprise Windows environments and provided hands-on experience with one of the most widely used technologies in modern IT infrastructure.
