# Setup a Basic Home Lab Running Active Directory Oracle VirtualBox | Add Users with PowerShell
- [Virtualization of Windows Server 2019 with Oracle VirtualBox](https://github.com/rosario7832/Virtualization-of-Windows-Server-2019-with-Oracle-VirtualBox)

In this section, **Windows Server 2019** will be virtualized using **Oracle VirtualBox**, which will allow the installation of **Active Directory** and the creation of a **domain** to which other devices in the lab environment can be connected.
  
- [Active Directory Installation and Configuration](https://github.com/rosario7832/Active-Directory-Installation-and-Configuration)

Install and configure **Active Directory**, setting up **administrative roles** and **network services** to ensure proper domain management.

- [Installing a Remote Access Server](https://github.com/rosario7832/Installing-a-Remote-Access-Server-in-Windows-Server)

The purpose of installing this server is to allow other devices within the network to access the internet through the **Windows Server**, which will act as a gateway and manage network connectivity.

- [Configuring a DHCP Server in Windows Server](https://github.com/rosario7832/-Configuring-a-DHCP-Server-in-Windows-Server)

A **DHCP (Dynamic Host Configuration Protocol)** server is configured so that client machines can automatically obtain an **IP address** and access the Internet, even when they are connected to a private internal network.

- [Adding Users Using PowerShell](https://github.com/rosario7832/Adding-Users-Using-PowerShell/tree/main)

This guide explains how to use a PowerShell script to add 1,000 new users to Active Directory.  
All users will be organized within a dedicated `_USERS` organizational unit for easier management.

- [Adding a Computer to an Active Directory Domain](https://github.com/rosario7832/Adding-a-Computer-to-an-Active-Directory-Domain)

In a Windows Server environment, **Active Directory (AD)** allows centralized management of users, computers, and network resources.  
Joining a computer to an Active Directory domain enables administrators to apply security policies, manage user accounts, and provide authentication services consistently and securely.  
This guide explains how to add a client computer to an AD domain using a virtual environment in **VirtualBox**, ensuring proper network configuration and successful domain integration.



