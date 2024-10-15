<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>

This document outlines the configuration settings and functionalities within the osTicket help desk system. It covers the essential aspects of user management, ticket visibility, service level agreements (SLA), and help topics to optimize the support process.



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/kN6zBR8.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Admin Panel vs. Agent Panel:

-Admin Panel: The control center for administrators to configure settings, manage agents, and oversee ticketing workflows.

-Agent Panel: The interface where support agents manage tickets, communicate with users, and handle inquiries.
</p>
<br />

<p>
<img src="https://imgur.com/WakE7kY.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Configure User Roles

 1.Navigate to Admin Panel.

 2.Go to Agents > Roles.

 3.Define roles according to permission grouping
 

</p>
<br />

<p>
<img src="https://imgur.com/sKcZKrH.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3.Configure Departments

 1.In the Admin Panel, select Agents > Departments.

 2.Set up departments for better ticket categorization:
 
 -SysAdmins: Handles technical issues.

 -Help Desk: General support queries.

 -Networking: Manages network-related requests.

</p>
<br />


<p>
<img src="https://imgur.com/EpU16Wd.jpg" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Configure Teams

1.Access the Admin Panel.

2.Navigate to Agents > Teams.

3.Pull agents from different departments to create specialized teams:

  -Online Banking: Focused support for online banking issues.
</p>
<br />


<p>
<img src="https://imgur.com/v8HFiYP.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Ticket Creation Permissions

 1.Go to Admin Panel > Settings > User Settings.

 2.Registration Required: Ensure users must register and log in to create tickets.
</p>
<br />


<p>
<img src="https://imgur.com/Hnyj0wG.jpg" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 6. Configure Agents

1.In the Admin Panel, select Agents > Add New.

2.Add agents with specific department assignments: 

-Jane (Dept: SysAdmins)
</p>
<br />


<p>
<img src="https://imgur.com/3Q9nwu2.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Configure Users (Customers)

1.Switch to the Agent Panel.

2.Navigate to Users > Add New.

3.Add user profiles:

-Karen Love


</p>
<br />


<p>
<img src="https://imgur.com/HTZdSjX.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8. Configure Service Level Agreements (SLA)

1.In the Admin Panel, go to Manage > SLA.

2.Create SLA definitions:

-Sev-A: Grace Period: 1 hour, Schedule: 24/7.

-Sev-B: Grace Period: 4 hours, Schedule: 24/7.

</p>
<br />


