<p align="center">

</p>

<h1>Deploying Active Directory and Creating Users</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<p>
Ensure Connectivity between the client and Domain Controller
</p>
<img src="https://i.imgur.com/vkTuj9O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<p>
Install Active Directory
</p>
<img src="https://i.imgur.com/ONdLQ46.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/0LO1L1m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Ly5zwkQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
<p>
In Active Directory Users and Computers (ADUC), create an Organizational Unit 
</p>
<img src="https://i.imgur.com/8FHGlI1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<p>
Create a new employee named “John Doe” with the username of “john_admin”
</p>
<img src="https://i.imgur.com/rOYg2ZU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


<p>
<p>
Add john_admin to the “Domain Admins” Security Group
</p>
<img src="https://i.imgur.com/9t7t2iG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


<p>
<p>
Log out/close the Remote Desktop connection to DC-1 and log back in as “mydomain.com\john_admin”
</p>
<img src="https://i.imgur.com/Mxlj5SK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


