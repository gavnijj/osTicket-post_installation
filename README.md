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

- Configuring roles
- Configure department and teams
- Allow anyone to create tickets
- Configure agents and users
- Configure SLA and Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/9XTqpZt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the admins panel go to the Agents tab then click the departments tab to configure the department settings. Added a new department called SysAdmins with access to all the tickets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/hrJF2JV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to admin panel, then Agents tab, then Teams tab to create a new team or configure seetings of other teams. Created a new team called Online Banking where members of this team will deal with tickets from the online banking section of the company.
</p>
<br />

<p>
<img src="https://i.imgur.com/X2YmT8m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Creating an account for the workers of the help desk. Account allows the workers to view and deal with tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/GoJ9RRO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The user creating an account to submit a helpdesk ticket to report a problem she is facing. The ticket would then be able to be viewed on the agents panel of the help desk. 
</p>
<br />

<p>
<img src="https://i.imgur.com/bRN7tgt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created three different SLA plans that scale with the severity of the ticket. Sev-A is the highest priority and a tikcet marked with this plan should be handled with the utmost urgency. Sev-B is next and is not quite as important as a Sev-A ticket but should still be resolved quickly. Sev-C is of the least priority and should be proritzed last if there other tickets to handle.
</p>
<br />

<p>
<img src="https://i.imgur.com/8GszncY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Help topics are something the end user uses when creating a ticket to select a category in where their ticket may belong. There are topics such as personal computer issues, equipment resets, business outages, etc. 
</p>
<br />
