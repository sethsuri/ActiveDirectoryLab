# Active Directory HomeLab with VMware  

## Overview  
This repository showcases a fully functional Active Directory (AD) HomeLab environment built using VMware. It demonstrates expertise in deploying, configuring, and managing an AD infrastructure in a virtualized environment.  

## Features  
- **Virtualized Environment**  
  - Fully set up using VMware Workstation/ESXi for maximum flexibility.  
- **Active Directory Setup**  
  - Configured a Windows Server with AD Domain Services for centralized user and resource management.  
- **DNS and DHCP Integration**  
  - Implemented DNS and DHCP to ensure network communication and dynamic IP assignment.  
- **Group Policy Management**  
  - Created and enforced Group Policies for user and device configuration.  
- **User and Group Management**  
  - Simulated real-world organizational structures with users, groups, and permissions.  
- **Security Practices**  
  - Configured domain-level security policies such as account policies, audit settings, and access controls.  

## Skills Demonstrated  
- **Virtualization**  
  - Expertise in deploying and managing virtual machines using VMware.  
- **Active Directory Administration**  
  - Proficient in AD setup, configuration, and troubleshooting.  
- **Networking Fundamentals**  
  - Practical knowledge of DNS, DHCP, and IP address management.  
- **Group Policy Management**  
  - Ability to create and manage Group Policies for system-wide configurations.  
- **Enterprise Security Practices**  
  - Implementation of security configurations to protect domain environments.  

## Environment Details  
- **Virtualization Tool**: VMware Workstation/ESXi  
- **Operating System**: Windows Server (Domain Controller)  
- **Client Machines**: Windows 10/11 clients for AD user testing  
- **Network Setup**: Internal virtual network for communication between VMs  

## Purpose  
This project serves as a practical demonstration of my ability to design, deploy, and maintain a virtualized Active Directory environment, an essential skill for managing enterprise IT infrastructures.  

## Walkthrough 

Downloaded VMware and Began the proccess of mounting the Windows Server ISO: 

![Screenshot 2025-01-16 141519](https://github.com/user-attachments/assets/601b7014-15fe-4797-8d4b-72ddfb5e2cf6)

Began to edit what functions I wanted my Lab to have:

![Screenshot 2025-01-16 154833](https://github.com/user-attachments/assets/ea815dde-713d-44bc-a015-282a39d25273)

Setup up account:

![Screenshot 2025-01-16 160449](https://github.com/user-attachments/assets/e673c836-5555-4a34-aed2-d7bc8672587e)

Got the server installed successfully:

![Screenshot 2025-01-16 160738](https://github.com/user-attachments/assets/8cd3d01a-f204-4c5d-800e-114bcbe7b7d8)

Began to configure server and Active Directory:

![Screenshot 2025-01-16 161630](https://github.com/user-attachments/assets/c9f244a0-7369-468c-b8f2-7384c62cbe8c)

Started the process of Adding Admins and Users:

![Screenshot 2025-01-16 162943](https://github.com/user-attachments/assets/a6c2ceca-4827-415f-90b9-73c443c1aee3)
![Screenshot 2025-01-16 175936](https://github.com/user-attachments/assets/5d147573-3479-4241-8fae-306cc2b6d3b9)
![Screenshot 2025-01-16 211933](https://github.com/user-attachments/assets/426dcf4e-443b-4003-9bb3-fd95c4875325)
![Screenshot 2025-01-16 212606](https://github.com/user-attachments/assets/f9f2806d-f02e-4ab8-a9b3-9fcc354e40cb)

Set up DHCP and made sure Client 1 ran off of DC's Internet: 

![Screenshot 2025-01-16 215827](https://github.com/user-attachments/assets/d76d08dc-c2d6-46ef-b1de-34ac91672007)
![Screenshot 2025-01-16 220115](https://github.com/user-attachments/assets/af0ddb27-ed03-499d-84c8-39731348fd7b)
