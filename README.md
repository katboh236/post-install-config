<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow Anyone to Create Tickets
- Configure Agents (Workers)
- Configire Users (Customers)
- Configure SLAs
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/IyQpD2G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/vUnro8z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Added a new "Supreme Admin" role for Agents in Admin Panel -> Agents -> Roles that gives permission to assign tickets to agents or teams, to close tickets, to open tickets on behalf of users, to edit and delete tickets, to edit thread items of other agents, to link tickets, to mark a ticket as Answered/Unanswered, to merge tickets, to post a ticket reply, to manage ticket referrals, to release ticket assignment, to transfer tickets between departments; permissions to assign, close, create, delete, edit, post reply and transfer tasks; ability to add/update/disable/delete canned responses. 
</p>
<br />

<p>
<img src="https://imgur.com/vQUAkVh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Added a new " System Administrators" department in Admin Panel -> Agents -> Departments.
</p>
<br />

<p>
<img src="https://imgur.com/OWR0Khx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created a new "Level II Support" team in Admin Panel -> Agents -> Teams.
</p>
<br />
<p>
<img src="https://imgur.com/CVyr0cc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Added new Agents (Jane Green and John Smith) in Admin Panel -> Agents -> Add New. Added Jane Green to "System Administrators" department, Supreme Admin panel and assigned to "Level II Support" team. Added John Smith to "Support" department with "View only" access. 
</p>
<br />
<p>
<img src="https://imgur.com/fGxwoWS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Added two new users: Karen Johnson and Ken Miller in Agent Panel -> Users -> Add New.
</p>
<br />
<p>
<img src="https://imgur.com/xHyPP25.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Added a new SLA plans: Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours) in order to provide a length of time in which the help desk Administrator expects tickets to be closed.

</p>
<br />
<p>
<img src="https://imgur.com/xHyPP25.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Added a new

</p>
<br />
