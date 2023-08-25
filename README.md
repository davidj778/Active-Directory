<p align="center">

</p>

<h1>Deploying Active Directory and Creating Users</h1>
This is a brief tutorial outlines the beginning stages of Active directory by confirming the connectivity between the client and Domain Controller and the installation of Active Directory. Towards the end, we take a look at how to create a username and log in with the new account.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Stages</h2>

- Ensure Connectivity between the client and Domain Controller
- Install Active Directory
- In Active Directory Users and Computers (ADUC), create an Organizational Unit
- Create a new employee named “John Doe” with the username of “john_admin”
- Add john_admin to the “Domain Admins” Security Group
- Log out/close the Remote Desktop connection to DC-1 and log back in as “mydomain.com\john_admin”


<h2>Stages</h2>

<p>
<p>
Ensure Connectivity between the client and Domain Controller by using the ping -t command and the private ip address of the Domain Controller
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
Log out/close the Remote Desktop connection to DC-1 and log back in as “mydomain.com\john_admin”. Confirm that you are logged in as the new user by using command prompt.
</p>
<img src="https://i.imgur.com/Mxlj5SK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


