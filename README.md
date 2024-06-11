<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuring osTicket Objectives</h2>

- Roles
- Departments
- Teams
- Agents(workers)
- Users(customers
- SLA
- Help Topics

<h2>Ticket Lifecycle Stages Objectives</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Configuring osTicket Steps</h2>

<p>
<img src="https://i.imgur.com/6PB0dYP.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I configured the roles by going to the Admin Panel, then Agents, and selecting Roles. Here, I set up a role called "Supreme Admin."
</p>
<br />

<p>
<img src="https://i.imgur.com/u1f60Y9.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Next, I configured the departments by navigating to Admin Panel -> Agents -> Departments, where I created a department called "System Administrators."
</p>
<br />

<p>
<img src="https://i.imgur.com/Cb0DrMu.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After that, I configured the teams by going to Admin Panel -> Agents -> Teams and creating two teams: "Level I Support" and "Level II Support."
</p>
<br />

<p>
<img src="https://i.imgur.com/8MFsbBL.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To allow anyone to create tickets, I went to Admin Panel -> Settings -> User Settings and selected "Registration Required," requiring registration and login to create tickets. I then configured agents (workers) by going to Admin Panel -> Agents -> Add New and adding agents named Jane and John. 
</p>
<br />

<p>
<img src="https://i.imgur.com/qugE4Qw.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For users (customers), I went to Agent Panel -> Users -> Add New and added users named Karen and Ken.
</p>
<br />

<p>
<img src="https://i.imgur.com/jh0joYK.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In addition, I configured SLAs by navigating to Admin Panel -> Manage -> SLA and setting up three SLAs: Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), and Sev-C (8 hours, business hours). Finally, I configured help topics by going to Admin Panel -> Manage -> Help Topics and creating topics for "Business Critical Outage," "Personal Computer Issues," "Equipment Request," and "Password Reset."</p>
<br />


<h2>Lifecycle Stages Steps</h2>

<p>
<img src="https://i.imgur.com/WouxqKO.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   <figcaption><strong>The application is crashing!.</strong></figcaption>
</figure>
</p>
<br>

<p>
<img src="https://i.imgur.com/qU4b8bD.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   <figcaption><strong>Lets escalate this issue and assign it to Craig.</strong></figcaption>
</figure>
</p>

<p>
To practice the ticket lifecycle using osTicket, I first created a few test tickets to simulate user requests or issues. I included various details such as ticket title, description, priority, and requester information. Once the tickets were created, I triaged them by assigning them to different departments or teams based on their nature and urgency. This step helped me understand how tickets are categorized and routed in a real-world scenario. Finally, I worked on solving the tickets by following the established processes and workflows within osTicket. This involved communicating with the requester, troubleshooting the reported issues, and providing timely resolutions. Through this practice, I gained hands-on experience with managing tickets from creation to resolution, improving my skills in customer support and issue resolution using osTicket.
</p>
<br />
