# ticket-life-cycle-examples
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolve tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/Hnp6Cri.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Above is a step-by-step setup for installing osTicket: launch IIS as an admin, enable extensions, rename and post configuration,
assign permissions, and download Heidi SQL.
</p>
<br />

<p>
<img src="https://i.imgur.com/xDK2uID.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Above is an image of an Admin panel in osTicket. That is configuring Agent Roles by creating new ones and adding Permissions.
agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an agent to the help desk 
they will need to be assigned to a primary department and given a primary role for the tickets\task routed to that department.  
</p>
<br />

<p>
<img src="https://i.imgur.com/BYC2smE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Above is an example of an SLA (SLAs are unlimited in osTicket). The purpose of the SLA Plan is to provide a length of 
time in which the help desk Administrator expects tickets to be closed. SLA Plans can be created by going to the Admin Panel > Manage > SLA Plans.
Each SLA plan is different this SLA has 3 severity levels 
sev-A (has the highest level of severity and must be resolved and closed within 1 hour of ticket intake).
SEV-B (has a moderate level of severity and must be resolved and closed within 4 hours of ticket intake).
SEV-C (has the lowest level of severity and must be resolved and closed within 8 hours of ticket intake).  
</p>
<br />

<p>
<img src="https://i.imgur.com/at5ivqO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> 
Above is an example of help topics and how tickets are assigned. Help topics will determine what department the ticket is routed to
which will determine which agents have access to the ticket. Help topics can also determine other configurations of the ticket such as SLAs
and the priority of the ticket emergency to low, ranging from business critical outage to general inquiry.  
</p>
<br />

<p>
<img src="https://i.imgur.com/YFGtzmq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> 
Above is an example of an open ticket with a normal priority level SEV-b, ken from coming from the support dept stated that ever since last night nobody in accounting has been able to use Adobe Reader. 
the details of the ticket state that the entire account dept Adobe reader is not functioning correctly. 
an administrator named Jane has updated the priority of the ticket to a high-priority SEV-a and has assigned the ticket to John Doe, 
and allowed him 4 hours to resolve the problem.


  
<p/>
<br />

<p>
<img src="https://i.imgur.com/rXTwoZx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>  
<p> 
Above is an example of the correspondence between John Doe and Josh from the support department. John found a rolled-back version of Adobe Reader which will allow accounting to utilize Adobe Reader 
  until he does further research as to why the updated version is malfunctioning. A response from Josh(support) indicates that the problem is resolved and the Adobe Reader software has been updated and ready for use, and has marked this ticket resolved and closed.
</p>
<br />

