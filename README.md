<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
<p>This tutorial demonstrates the post-configuration setup of the osTicket system.</p>

<h2>Introduction</h2>
<p>
Great job! We have successfully configured osTicket from scratch. Now, we will proceed with system administration tasks and post-installation setup.
</p>

<h2>Step 1: Configure New Roles</h2>
<p>
To configure new roles, navigate to <strong>Admin Panel → Agents → Roles</strong>. We will create a new role called "Supreme Admin."
Click on "Add new role," enter the role name, and modify permissions as needed. Since this is a Supreme Admin, all permissions will be granted. Roles define an agent's access level, so not all agents will have full permissions.
</p>
<img src="https://i.imgur.com/XHteqdt.png" height="80%" width="80%" alt="Creating Supreme Admin Role"/>

<h2>Step 2: Create a New Department</h2>
<p>
Select <strong>Departments</strong> in the Agents tab. Departments organize agents based on their roles within the help desk. Here, we will create a department named "System Administrators" where Supreme Admins will be assigned. Additional settings such as SLAs, managers, and email settings can also be configured.
</p>
<img src="https://i.imgur.com/dGK0RVM.png" height="80%" width="80%" alt="Creating System Administrators Department"/>

<h2>Step 3: Set Up a New Team</h2>
<p>
Teams allow agents from different departments to collaborate. For example, you can create a specialized support team for handling specific product-related tickets. Navigate to <strong>Agents → Teams</strong>. By default, there is a Level I Support Team. In this case, we will create a Level II Support Team.
</p>
<img src="https://i.imgur.com/cYzWBD2.png" height="80%" width="80%" alt="Creating Level II Support Team"/>

<h2>Step 4: Enable Public Ticket Creation</h2>
<p>
To allow users to create tickets, go to <strong>Admin Panel → Settings → User Settings</strong> and modify the necessary options.
</p>
<img src="https://i.imgur.com/H1q2Fdh.png" height="80%" width="80%" alt="User Settings for Public Ticket Creation"/>

<h2>Step 5: Create Agents</h2>
<p>
Agents are responsible for resolving tickets. Each agent is assigned a primary department and role. Agents can also have access to multiple departments and different roles per department. Navigate to the <strong>Agents</strong> tab to configure permissions, access, and team assignments.
</p>
<img src="https://i.imgur.com/8WTOSre.png" height="80%" width="80%" alt="Creating Agents"/>

<h2>Step 6: Create Users</h2>
<p>
Users are customers who submit tickets. Each user is identified by their email address. To create a new user, navigate to <strong>Agent Panel → Users → User Directory → Add New</strong>.
</p>
<img src="https://i.imgur.com/xOprA9f.png" height="80%" width="80%" alt="Creating Users"/>

<h2>Step 7: Configure SLA Plans</h2>
<p>
SLA Plans define the response time expectations for resolving tickets. Navigate to <strong>Admin Panel → Manage → SLA Plans</strong> to configure schedules and grace periods. In the example below, SEV-A has a 24/7 schedule with a one-hour grace period.
</p>
<img src="https://i.imgur.com/LpjCaLd.png" height="80%" width="80%" alt="Configuring SLA Plans"/>

<h2>Step 8: Set Up Help Topics</h2>
<p>
Help topics allow users to categorize their tickets. For instance, a help topic like "Business Critical Outage" can be used for urgent issues such as mobile banking downtime.
</p>
<img src="https://i.imgur.com/kB7rts2.png" height="80%" width="80%" alt="Creating Help Topics"/>

<h2>Conclusion</h2>
<p>
By completing these post installation configurations, your osTicket system is now fully set up and optimized for efficient ticket management. 🎉
</p>


