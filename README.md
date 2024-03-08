<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (22H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Connect a host computer to the Domain Controller 
- Add a bunch of users to the system 
- Login as and admin with one of the users 
- And practice disabling a users account then unlocking that same account
- This is going to be a walkthrough presentation 

<h2>Deployment and Configuration Steps</h2>

- Ok here I join a host computer to the Domain Controller using the private IP Address
<p>
<img src=https://i.imgur.com/PHlvcFU.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
- Ok here I setup a script to add 10,000 users 


<p>
<img src=https://i.imgur.com/lBOHvUa.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> 

</p>
<br />
- These are the results after I run the script 

<p>
<img src=https://i.imgur.com/ddnhexY.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
- Here is a list of the users added to the employee section 

<p>
<img src=https://i.imgur.com/pQzPnM2.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
- Here is where i locate the user name I will use to get admin access

<p>
<img src=https://i.imgur.com/t1Ohojx.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 

</p>
<br />
- Ok here I disable the users account 

<p>
<img src=https://i.imgur.com/FONXMFp.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
- Here I try to login to the system and my account is disabled 

<p>
<img src=https://i.imgur.com/AmjZy3c.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
- Here I unlock the users account so that they could login to the system
- Ok this concludes the presentation. Thanks for viewing 

<p>
<img src=https://i.imgur.com/9XuwJ28.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
