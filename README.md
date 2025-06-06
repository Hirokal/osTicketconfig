<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configurations</h1>
For this lab I’ll be demonstrating different configurations you can do for the ticketing system OsTicket. It is expected that you already have OsTicket installed and just need to set it up to be used as a proper ticketing system.<br />


<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/8jtX7hR.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
We can set up different roles and adjust the permissions that are allowed for each role. For this lab, I will just set up a role called “Supreme Admin” and give it all permissions. To create roles, ensure you are in the Admin Panel. You can switch between Admin and Agent Panels on the top right of the OsTicket screen. Once you are in the Admin Panel, simply click on Agents, then Roles, then and you can add new roles and customize their permissions from there.
</p>
<br />

<p>
<img src="https://imgur.com/HH8NUBe.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
We can set up different departments and similar to roles, there will be various configurations you can make. Departments are primarily for ticket visibility. For example, you can have different departments such as help desk/sysadmins/networking/etc. and different tickets can be assigned to different departments. For this lab, I’ll be just be creating a SysAdmin department by going to Admin Panel > Agents > Departments.
</p>
<br />

<p>
<img src="https://imgur.com/Nyu09v9.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
We can set up and configure teams, which are generally used when you want to create a group or groups of agents from different departments. For example, if you work in a bank, you can set up an Online Banking team that consists of sysadmins and help desk agents. For this lab, I’ll be creating an Online Banking team by going to Admin Panel > Agents > Teams.
</p>
<br />

<p>
<img src="https://imgur.com/XDTNXwW.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
We can create agents that can handle tickets that come to the queue. You’ll be able to assign the agents to departments and teams as well as configure their permissions. I’ll be creating 2 agents, Jane and John Doe, assigning them to the SysAdmins and Support departments respectively, by going to Admin Panel > Agents > Agents.
</p>
<br />

<p>
<img src="https://imgur.com/Tzb5Dj6.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
We can create users who will be able to create tickets that agents will receive and take care of. I’ll just be creating one user by going to User Panel > Users > User Directory.
</p>
<br />

<p>
<img src="https://imgur.com/UIscYn2.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
We can create Service Level Agreements (SLAs) that are used to categorize tickets by their urgency and level of impact. I’ll be creating 3 levels, Sev-A, B, and C by going to Admin Panel > Manage > SLA.
</p>
<br />

<p>
<img src="https://imgur.com/FCw7mUJ.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
Lastly, we can create and configure Help Topics that can be assigned when users create a ticket to help organize them. I’ll be creating a few help topics by going to Admin Panel > Manage > Help Topics.
</p>
<br />

<h2>osTicket Configurations are Complete </h2>

With these basic configurations complete, we can now utilize osTicket as a proper ticketing system.
