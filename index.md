---
layout: default
---

# Installing and Configuring a Virtual Network

<a href="https://docs.google.com/document/d/1HnYFiNJ5eso6yP-6tgihzOVBIvID8p6SlmEawQNcixk/edit?usp=sharing">Installing and Configuring a Virtual Network PDF</a>

Project Overview: SAVN.local Virtual Network Implementation

"SAVN.local" is a virtual private network (VPN) designed for a fictitious company called System Administration Virtual Network Company (SAVN). As the company’s system administrator, I am responsible for designing and implementing this network. SAVN’s network infrastructure will be built using Microsoft technologies, specifically Windows Server 2022 for servers and Windows 10 for desktop environments.

The project involves the following key components:

Virtualization: The entire network setup is virtualized. We have two virtual servers and one virtual desktop. These machines communicate over a local virtual network switch, with my physical computer acting as the network switch.

Domain Controller (CMB-SP24-S22-1): This server manages the SAVN.local domain using Active Directory Domain Services (AD DS) and DNS. It is responsible for locating network resources and controlling access to them.

Application and File Server (CMB-SP24-S22-2): This server stores and manages applications and data files centrally, allowing other networked computers to access these resources.

Virtual Desktop (CMB-SP24-W10-1): This client machine runs Windows 10 and accesses system resources such as folders and files on the network file server.

Through this project, I will configure IP settings, implement centralized and secure management of the network, and ensure all components work seamlessly together to support SAVN’s operations.




# Managing the SAVN.local Domain

Project Overview: In this project, I managed the SAVN.local domain by performing essential system administration tasks. The focus was on configuring and securing the network by creating and managing Organizational Units (OUs), as well as setting up and manipulating user accounts across multiple servers within the domain. This project emphasized the importance of domain security and efficient resource management within an Active Directory (AD) environment.

Key Objectives:
Organizational Unit (OU) Creation:
I established OUs for the Administration, Research, and Sales departments within the SAVN.local domain. This structure allowed for more granular control and application of security policies tailored to each department’s needs, ensuring that resources are managed efficiently and securely.

User Account Management:
Local User Account Creation: On the standalone server MJL-SP24-S22-2, I created a local user account using the Local Users and Groups MMC snap-in. This process highlighted the distinction between local and domain-oriented accounts, crucial for understanding access control within a hybrid environment.
Domain User Account Creation: On MJL-SP24-S22-1, the domain controller for SAVN.local, I set up a domain user account using the Active Directory Users and Computers tool. This task was integral to managing access to network resources and applying group policies effectively.

Moving User Accounts to OUs:
I demonstrated how to organize and secure user accounts by moving the newly created domain user account into the appropriate OU (Administration). This step is vital for maintaining a structured and secure environment, allowing for the streamlined application of security policies.
Testing Domain User Logon Without a Domain Controller:
To assess the domain’s resilience, I attempted to log into MJL-SP24-S22-2 as the domain user after shutting down the domain controller (MJL-SP24-S22-1). As expected, the logon attempt failed, reinforcing the critical role of the domain controller in user authentication and access control. This test underscores the importance of ensuring domain controller availability for maintaining network security and accessibility.

Cybersecurity Implications: This project highlighted several cybersecurity best practices, including the importance of proper organizational structuring within Active Directory, the need for clear distinctions between local and domain user accounts, and the significance of maintaining the availability of key network infrastructure components like domain controllers. By successfully completing this project, I enhanced the security posture of the SAVN.local domain and gained valuable hands-on experience in managing and securing a Windows-based network environment.


<a href="https://docs.google.com/document/d/1Igvi7cHpFZX13rb6o1Mq7J-Net3DuPimOiDF7TDZKS0/edit?usp=sharing">Managing the SAVN.local Domain PDF</a>








> UNDER CONSTRUCTION!
> UNDER CONSTRUCTION!
> UNDER CONSTRUCTION!

### Header 3



![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)



```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
