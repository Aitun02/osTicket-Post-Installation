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
- Allow or Restrict Ticket Creation
- Configure Agents and Users
- Set Up SLA Policies
- Add Help Topics for Ticket Categories

<h2>Configuration Steps</h2>

<h3>1. Admin/Analyst Login Pages</h3>
<p>
- Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php<br />
- End Users osTicket URL: http://localhost/osTicket
</p>

<h3>2. Configure Roles</h3>
<p>
- Navigate to Admin Panel -> Agents -> Roles<br />
- Example Role: Supreme Admin
</p>

<h3>3. Configure Departments</h3>
<p>
- Navigate to Admin Panel -> Agents -> Departments<br />
- Example Departments: SysAdmins, Support
</p>

<h3>4. Configure Teams</h3>
<p>
- Navigate to Admin Panel -> Agents -> Teams<br />
- Example Team: Online Banking
</p>

<h3>5. Allow or Restrict Ticket Creation</h3>
<p>
- Navigate to Admin Panel -> Settings -> User Settings<br />
- To restrict: Uncheck "Allow unregistered users to create tickets"<br />
- Require registration: Enable "Require registration and login to create tickets"
</p>

<h3>6. Configure Agents</h3>
<p>
- Navigate to Admin Panel -> Agents -> Add New<br />
- Example Agents:<br />
  - Jane (Department: SysAdmins)<br />
  - John (Department: Support)
</p>

<h3>7. Configure Users</h3>
<p>
- Navigate to Agent Panel -> Users -> Add New<br />
- Example Users:<br />
  - Karen<br />
  - Ken
</p>

<h3>8. Configure SLA (Service Level Agreement)</h3>
<p>
- Navigate to Admin Panel -> Manage -> SLA<br />
- Example SLAs:<br />
  - Sev-A: Grace Period: 1 hour, Schedule: 24/7<br />
  - Sev-B: Grace Period: 4 hours, Schedule: 24/7<br />
  - Sev-C: Grace Period: 8 hours, Schedule: Business Hours
</p>

<h3>9. Configure Help Topics</h3>
<p>
- Navigate to Admin Panel -> Manage -> Help Topics<br />
- Example Help Topics:<br />
  - Business Critical Outage<br />
  - Personal Computer Issues<br />
  - Equipment Request<br />
  - Password Reset<br />
  - Other
</p>

<h2>Visual Demonstrations</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Configuration Example"/>
</p>
<p>
The above image demonstrates the Admin Panel where various configurations such as roles, departments, and agents are set up.
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="SLA Configuration"/>
</p>
<p>
The SLA configuration ensures tickets are categorized and handled according to their urgency and priority.
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Help Topics"/>
</p>
<p>
Help Topics streamline ticket creation by categorizing issues, helping agents address user concerns more efficiently.
</p>
<br />


   
