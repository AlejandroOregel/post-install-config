# post-install-config
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

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/w1eC9R0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once signed into osTicket configuring roles is essential, go to the admin panel--> agents--> departments, after this click on add a new role. Feel free to name it whatever you'd like, I'll be naming mine SysAdmins and granting it all the permissions there is.
</p>
<br />

<p>
<img src="https://i.imgur.com/BPRdR5q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next go to departments and click add new department, as an example I'll be naming my department "Online Banking"
</p>
<br />

<p>
<img src="https://i.imgur.com/2zv3DgG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now make sure that anyone in your system can create tickets go to settings --> users and make sure the box that says "Require registration and login to create tickets" is unchecked.
</p>
<br />

<p>
<img src="https://i.imgur.com/sEylURA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now notice that you have no "agents" helping you maintain and use your system, go over to Agents--> add new. From here set up accounts for your agents feel free to name them whatever you'd like and assign them to different departments within osTIcket.
</p>
<br />

<p>
<img src="https://i.imgur.com/vIpN9qd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Notice that we have no categories for which problem is more urent, slightly urgent, and less urgent, lets change that. Go to Manage--> SLA, from her click where it says "Add New SLA Plan"
</p>
<br />

<p>
<img src="https://i.imgur.com/WPu5Qdz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you've clicked add new SLA plan make sure to add the following SLA's
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)
These each properly categorzie the urgency of each problem and how often agents are notified of these problems.
</p>
<br />

<p>
<img src="https://i.imgur.com/1M0grSK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now every osTicket system needs system specific help topics for when users create a ticket that needs to be fixed, head over to help topics and create help topics, these are a few examples of what they could be
Business Critical Outage, 
Personal Computer Issues,  
Equipment Request, 
Password Reset, 
Other
</p>
<br />

<p>
<img src="https://i.imgur.com/3otH8Zu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Congratulations you have now configured your osTicket!
</p>
<br />
