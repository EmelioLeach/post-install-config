<p align =" Center ">
<img src= "https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo "/>
</p>

<h1>osticket - Post-Install Configuration </h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. <br />


<h2 >Video Demonstration </h2>

- ### [YouTube: How to configure osTicket, post-installation ](https://www.youtube.com)

<h2 >Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute )
- Remote Desktop
- Internet Information Services (IIS)

<h2 >Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2 >Post-Install Configuration Objectives </h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2 >Configuration Steps</h2>
Congratulations on installing osticket, now we will demonstrate post confiuration of osticket.
<p>
  
So now we are going to use the Admin panel to create a supreme admin that would have access to creating a ticketing system, defining roles, and SLA.
We will also create agents and tickets so we can solve them or redirect them to the proper department to resolve any issues a customer would have using help desk. In order to set this up we will have to go to Admin panel> Agents> Roles. Also roles are permissions granted to Agents in each department, you can customize roles for specific departments.
</p>
<p>
<img src = https://i.imgur.com/eR3QK9s.png height="80% "width="80%"alt = "Disk Sanitization Steps" / >
</p>
<p>
We will create a System Administrators department so that tickets can be routed through the departments while using help desk, also there are many diffrenet settings in each department can use or have access to. Also certain departments can have SLA set for certain tickets.
<img src =https://i.imgur.com/s4TIQ8Q.png height= "80%" width = "80%" alt = "Disk Sanitization Steps" />
</p>
<p>
Once we setup System Admin we will create teams for the agents and organize them to handle specific issues to be resolved.    
</p>
<br />
<img src =https://i.imgur.com/9SRBLx9.png height="80% "width="80%"alt = "Disk Sanitization Steps" / >
<p>
Also we will have to set up agents so that they can have access to respond to people/tickets in the help desk. Agents will have Primary roles in whatever Primary department they are assigned to and might extended access to other departments, which can be configured in the access tab of the agent's profile.
</p>  
<img src =https://i.imgur.com/epDTNdF.png height="80% "width="80%"alt = "Disk Sanitization Steps" / >
</p>
<p>
Next we can add users so that they can create/check tickets using there email threw help desk, also this would make it easier to find tickets for specific users in User DIrectory. You will have to leave admin panal ad go to Agent Panel->Users->User Directory->Add new. 
</p>
<br />
<img src =https://i.imgur.com/NChjzJY.png height="80% "width="80%"alt = "Disk Sanitization Steps" / >
<p>
</p>
<p>
Now service level agreements is basically how long a ticket can be open and you can also have an unlimited amount of tickets aswell. You will have to go to Admin panel > Manage > SLA to have access to this.
</p>
<br />
<img src = https://i.imgur.com/5ok50Uk.png height="80% "width="80%"alt = "Disk Sanitization Steps" / >
</p>
<br />
Help topics helps you categorize whatever issue somebody is having threw a ticket with the correct department, for example a password reset or a personal computer issue, these are two different types of help topics. Also to access this you must go to Admin panel > Manage > Help Topics.
</p>
<br />
<img src = https://i.imgur.com/zsKRSG5.png height="80% "width="80%"alt = "Disk Sanitization Steps" / >
