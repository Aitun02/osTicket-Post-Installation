<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles for Permissions
- Configure Departments for Ticket Visibility
- Configure Teams for Cross-Department Collaboration
- Configure Agents and Users
- Set Up SLA Policies
- Add Help Topics for Ticket Categories

<h2>Configuration Steps</h2>

<h3>1. Admin/Analyst Login Pages</h3>
<p>
- Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php<br />
- End Users osTicket URL: http://localhost/osTicket
</p>
To effectively manage roles, departments, and teams within osTicket, begin by navigating to the **Admin Panel** and accessing the appropriate sections:

 <h3>2. Roles Configuration</h3>
   Assign permissions to agents by creating and customizing roles. For example, you can set up a **Supreme Admin** role to grant full administrative privileges.


<p align="center">
<img src="https://imgur.com/phaaMoF.png" alt="Configure Roles" height="80%" width="80%">
</p>

<h3>3. Configure Departments</h3>

 Departments Configuration</h3> 
   Organize ticket visibility and assignments by defining departments. Common examples include **SysAdmins** for IT management and **Support** for general customer inquiries.

<p align="center"> 
<img src="https://imgur.com/9Kt0A4Z.png" alt="osTicket Example Image" height="80%" width="80%">
</p>

<h3>4. Configure Teams</h3>
<p> 
   Enable cross-department collaboration by forming teams. For instance, you might create an **Online Banking** team to handle issues specific to digital banking operations.
</p>
<p align="center">
<img src="https://imgur.com/Bjw9gid.png" alt="osTicket Configuration Example" height="80%" width="80%">
</p>




<h3>5. Configure Agents</h3>
<p>
This image highlights the addition of new agents in the osTicket system, showcasing examples such as Jane, assigned to the SysAdmins department, and John, assigned to the Support department, ensuring proper role allocation within the help desk team.

</p>
<p align="center">
<img src="https://imgur.com/ie8HREh.png" alt="osTicket Agents Configuration" height="80%" width="80%">
</p>


<h3>7. Configure Users</h3>
<p>
This image highlights the addition of new users in the osTicket system. Examples include Karen and Ken, showcasing how end-users are added to the system for efficient ticket management and support operations.

</p>
<p align="center">
<img src="https://imgur.com/VSkR28Z.png" alt="osTicket User Configuration" height="80%" width="80%">
</p>


<h3>8. Configure SLA (Service Level Agreement)</h3>
<p>
This image highlights the configuration of SLA (Service Level Agreement) policies within the osTicket system. Examples include:
- **Sev-A:** Grace Period of 1 hour with a 24/7 schedule.
- **Sev-B:** Grace Period of 4 hours with a 24/7 schedule.
- **Sev-C:** Grace Period of 8 hours with a schedule limited to business hours.
These SLAs ensure timely ticket resolution based on priority and urgency.

</p>
<p align="center">
<img src="https://imgur.com/eaLXk2F.png" alt="osTicket Help Topics Configuration" height="80%" width="80%">
</p>


<h3>9. Configure Help Topics</h3>
<p>
This image highlights the configuration of Help Topics within the osTicket system. Examples include:
- **Business Critical Outage**
- **Personal Computer Issues**
- **Equipment Request**
- **Password Reset**
- **Other**

These Help Topics allow users to categorize their issues, ensuring tickets are directed to the appropriate departments for efficient resolution.

</p>
<p align="center">
<img src="https://imgur.com/YTo60KZ.png" alt="osTicket Image" height="80%" width="80%">
</p>



