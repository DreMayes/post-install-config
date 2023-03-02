<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation]https://youtu.be/vRf7WiRMHAk(https://www.youtube.com)

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
- Configure Agents/Workers
- Configure Users/Customers
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src=https://user-images.githubusercontent.com/126605824/222589066-b3ee4d42-b43b-4653-abbb-cf32ee7b5ac0.png

</p>
<p>
If granted access to the Admin Panel, that Agent will have the ability to make changes in the configurations of the help desk. From the Agent tab of the Admin Panel, the configurations of each Agent of the help desk can be modified, including the ability to Limit an Agent’s access to only tickets that are specifically assigned to them. The Permissions tab of the Agent profile allows the Agent functionality within the help desk which are not Department specific access items. Areas such as the User Directory, Organization, and Knowledge Base can be limited per Agent. This includes the ability to search for and see the ticket metadata for tickets the Agent does not have access to, the email ban list, and other staff statistics on the dashboard.
</p>
<br />

<p>
<img src=https://user-images.githubusercontent.com/126605824/222589800-e223774d-352f-4762-bf02-07cfea8bbdc1.png

</p>
<p>
There are many departments that handle tickets for different situations and some may be designated for higher role such as managers and supervisors.
</p>
<br />

<p>
<img src=https://user-images.githubusercontent.com/126605824/222590380-19ef81df-0628-4ef6-9692-b64d68c922a5.png
</p>
<p>
Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter. Having Agents from different Departments assigned to a Team will supersede the parameters of the Agents’ Department rules. For example, you can create a Help Topic associated with a particular product you produce, and assign it to a Team of specialist Agents from different Departments. To create a Team in your Admin Panel, locate the Agents tab, and click on Teams. Then click Add New Team on the right, and fill out the appropriate information. Then you will be able to add Agents to the team by clicking on their name from your list of Agents and checking the corresponding box next to the Team name you wish to add them at the bottom of the page. A Team can have an appointed leader who can receive Alerts & Notices separate from other team members. In order to set a Team Leader you can choose an Agent from the Team Lead dropdown when creating a Team or Editing an existing Team.
  </p>
<br />
<img src=https://user-images.githubusercontent.com/126605824/222592426-b7d61704-23c7-4de5-a912-4a458b76d870.png
     </p>
Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile.

