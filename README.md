<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

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
- Configure Agents
- Configure Users

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/1J8eGyI.png" height="80%" width="80%" alt="roles"/>
<p>  
</p>
Once logged into the azure portal and remotely connected to virtual machine, we would open the ticket sytem. Once opened you would select the admin panal> agents> then roles. Roles are the permissions granted to the agents of the different department. Here you would create variety of roles such as Admin, Admin Secuirty, or Supreme Admin and then assign the permissions of that role. 
</p>
<br />

<p>
<img src="https://i.imgur.com/G8Kks74.png" height="80%" width="80%" alt="agents"/>
</p>
<p>
After assigning the permission for the different roles, you would then complete the same steps and create the Departments in the ticket system. We would select admin panal> Agents> and then Departments. We would also do this same process for configuring Teams and Agents. However, when configuiring Agents it would be slightly different. we would go to Agent Panel>Agents> and then Add New.
</p>
<br />

<p>
<img src="https://i.imgur.com/KTNg9Bm.png" height="80%" width="80%" alt="help"/>
</p>
<p>
Lastly, after assigning configuration, we would then configure the settings for the users. Here we are determining who will be allowed to create tickets within the organization. We would do this under the admin panal. Once user settings have been configured, we would then configure service level agrrements (SLA) and also the help topics: i.e Password Reset or Equipment request.
</p>
<br />
