<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a Domain Controller virtual machine and a Windows 10 virtual machine. 
- Insall Active Directory on the Domain Controller VM, and create a new forest.
- Create New Organizational Units called "Employees" and "Admins", set up remote desktop use or non-adminstrative user.
- In Powershell as an administrator run a script that generates multiple new users and login to remote desktop with one of the newly created users. 

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/GsIvVgR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Client-1 VM control panel showing connection to Domain Controller VM after enabling ICMPv4 on the local firewall for the Domain Controller
</p>
<br />

<p>
<img src="https://i.imgur.com/wFoc2MK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/Bryvro4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/tJ5xfDP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Active Directory being installed on Domain Controller, new forest domain being created, and logging back into Domain Controller with new domain. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
