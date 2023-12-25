<h1>Active Directory Home Lab</h1>


<h2>Description</h2>
The project consists of creating two virtual box machines with one using Server 2019 and the other using Windows 10. Server 2019 was created as the domain controller that holds active directory that comes with two network interface cards. First one which is connected to the outside internet and the second one that's connected to the virtual box private network. Using a script in KQL to create multiple users in PowerShell.
<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle VirtualBox</b>
- <b>Kusto Query Language (KQL)</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Server 2019</b>

<h2>Program walk-through:</h2>

<p align="center">
Diagram I'll be following: <br/>
<img src="https://i.imgur.com/87dbHzm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creation of Server 2019 in Virtual Box: <br/>
<img src="https://i.imgur.com/nWWWOb1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The two NIC's: <br/>
<img src="https://i.imgur.com/O4fAD3v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creation of the admin user in AD:  <br/>
<img src="https://i.imgur.com/K0dxgkj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
KQL script to create multiple users in PowerShell:  <br/>
<img src="https://i.imgur.com/8IpwsSu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Multiple users created in AD:  <br/>
<img src="https://i.imgur.com/ymc9Eti.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Server 2019 and Windows 10 joined together:  <br/>
<img src="https://i.imgur.com/RCK5wvR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />  
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
