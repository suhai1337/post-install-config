<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Configuration</h1>
This project outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Objectives</h2>

- Add roles,departments and teams for agents to exist in.
- Add agents(workers) and users(clients) to the database.
- Allow registered users to create tickets.
- Add additional Help Topics for tickets.
- Configure SLA.

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/H51gyht.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Signing into osTicket as an admin, we are able to configure multiple settings on osTicket to match the needs of a company. For this project I added a Super Admin role, a System Administrators department and also multiple level of support teams. When adding agents(workers) to the database, there is an option to send them an email to reset their password or have them reset their password on the next login, this is a common tool for new employees signing in for the first time or for individuals who have forgotten their password.
</p>
<br />

<p>
<img src="https://i.imgur.com/5FWjKUP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help Topics are important in ticketing because it can quickly give an idea of what the issue is going to involve such as a password change, feedback or even something like a large business outage. I created four additional help topics for the company.
</p>
<br />

<p>
<img src="https://i.imgur.com/7EeqMPm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Service Level Agreements(SLA) are vital to ticketing. It lets workers know the severity of the ticket. Often time, the user sending in a ticket might put their SLA as severe but after being reviewed by someone assigned to the ticket, it could be revised into a lower SLA level. An example is a production worker sending in a Severe SLA involving their only company computer being slow but aftering being reviewed by someone who understands and knows the companys SLAs, they would put the SLA at the appropriate level. Understanding a company's SLAs is vital for help desk workers.
</p>
<br />
