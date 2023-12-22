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

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src=https://i.imgur.com/N4bV9WO.png/>
  <img src=https://i.imgur.com/iwa4KVp.png/>
</p>
<p>
I will be making a help topic as a User (Customer) based off the help topics configured in the previous tutorial. <b> i. Business Critical Outage ii.Personal Equipment Issues iii. Equipment Request iv. Password Reset.</b>
  <br />
</p>
<br />

<p>
<img src=https://i.imgur.com/8stP1ri.png/>
</p>
<p>
I will now be logging into osTicket as a Help Desk Professional which you may recall as the Agents we configured in the previous tutorial as well.
</p>
<br />

<p>
<img src=https://i.imgur.com/nprwCLi.png>
</p>
<p>
Now that we are logged in as our Agent Jane we can observe and troubleshoot the ongoing ticket reagarding the mobile banking being offline, I created two other tickets for reference but we will focusing on this ticket for the simulation.
</p>
<br />

<p>
  <img src=https://i.imgur.com/1wrqZWb.png>
</p>
<p>
We will observe <b>Ticket#458091</b> or as the customer stated "Mobile banking is down." In this simulation and in the real world this ticket would most likely be a severity A SLA plan because it could potentially lose income for the business.

For Jane in this simulation we will pretend she is the Queue Manager and make sure the settings are configured properly. <b>The red arrows in the above image show where I have changed the severity and priority of this ticket.</b>
</p>
<p>
<img src=https://i.imgur.com/CcUd6Z4.png>
<img src=https://i.imgur.com/oYoMUKq.png>
</p>
<p>
If the support team is unable to troubleshoot the issue at hand there is an option to transfer the ticket to another department like the image examples above.
</p>

<p>
  <img src=https://i.imgur.com/aaxYBoL.png>
</p>
<p>
If you scroll to the bottom of the page you will see a "post reply" section as you can see we replied by saying that we are coordinating with the sys admins 
  <b>Note: The arrow indicates that the ticket status is still opened we will leave the ticket open for now but the two other options are resolved and closed.</b>
</p>
<p>
  <img src=https://i.imgur.com/FyL8LZE.png>
</p>

<p>
Now we will say that a fault has been found and the issue has been resolved.
</p>
<p>
<img src=https://i.imgur.com/smfz7c7.png>
<img src=https://i.imgur.com/HSM0nTY.png>
</p>

<p>
If we go back to the dashboard we can see that <b>Ticket#458091</b> is no longer in open, If we go to the closed tab we can see that the ticket has been closed and resolved.
</p>
