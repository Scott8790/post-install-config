<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket (Admin and Agent panel)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="721" alt="Post Install Config1" src="https://github.com/Scott8790/post-install-config/assets/172638339/af2de995-0217-4140-95c9-450bd8bddaed">

</p>
<p>
Admin Panel -> Agents -> Roles  
  
  Supreme Admin

</p>
<br />

<p>
<img width="718" alt="Post Install Config2" src="https://github.com/Scott8790/post-install-config/assets/172638339/81a9be5b-05a1-4204-aced-ce57542c6eb3">

</p>
<p>
Admin Panel -> Agents -> Departments

  System Administrators
  
</p>
<br />

<p>
<img width="731" alt="Post Install Config3" src="https://github.com/Scott8790/post-install-config/assets/172638339/bf612441-cf26-44ff-ad98-425baad182d7">

</p>
<p>
Admin Panel -> Agents -> Teams

  Level I & II Support
  
</p>

</p>
<br />

<p>
<img width="716" alt="Post Install Config4" src="https://github.com/Scott8790/post-install-config/assets/172638339/772315f2-7c52-404f-93ab-c686c4033528">

</p>
<p>
Admin Panel -> Settings -> Users Settings

  Registration Required: Require registration and login to create tickets -> leave it unchecked to allow anyone to create a ticket
  
</p>

</p>
<br />

<p>
<img width="719" alt="Post Install Config5" src="https://github.com/Scott8790/post-install-config/assets/172638339/5eafb67c-b26d-42d1-b148-67a4e93b4672">

</p>
<p>
Admin Panel -> Agents -> Add New

  Jane and John Doe (assign to department and teams as necessary)
  
</p>

</p>
<br />

<p>
<img width="724" alt="Post Install Config6" src="https://github.com/Scott8790/post-install-config/assets/172638339/72f1b105-9b08-4345-ae85-1edebf159e07">

</p>
<p>
Agent Panel -> Users -> Add New

  Karen & Ken (customers/users create tickets and cannot close them)
</p>

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Manage -> SLA

  Sev-A (1 hour, 24/7) highest priority needs to be solved and closed ASAP

  Sev-B (4 hours, 24/7) high priority needs to be solved and closed within 4 hrs of ticket creation

  Sev-C (8 hours, business hours) low to mid priority needs to be solved and closed by the 8th business hour not on weekends
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Manage -> Help Topics

  Business Critical Outage

  Personal Computer Issues

  Equipment Request

  Password Reset

  
</p>
<br /># post-install-config

</p>
<br />
