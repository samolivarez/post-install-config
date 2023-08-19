<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This guide outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Create osTicket roles from the admin panel
- Set permissions for roles created
- Create Departments
- Create Teams
- Set the "User" settings
- Addition of new Agent
- Create "Users"
- Create SLA Plans
- Create "Help Topics"

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/WQs0LyZ.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Working from Virtual Machine remote access thru Microsoft Azure, the Admin will work from their osTickt admin panel to begin creating roles. In the image above a new "Supreme Admin" role is created.
</p>
<br />

<p>
<img src="https://i.imgur.com/c6PeVB4.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, the Admin will set "permissions" for the newly created role.
</p>
<br />

<p>
<img src="https://i.imgur.com/vI7FupI.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, the Admin will begin creating "Departments" such as "System Administration" as the image above shows.
</p>
<br /># post-install-config

<p>
<img src="https://i.imgur.com/0ONt0tE.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, the Admin can create "Teams" as the above image shows where a "Team" called "Level II Support" is created.
</p>
<br /># post-install-config

<p>
<img src="https://i.imgur.com/HCl80Mi.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next and still in the admin panel, the "User" settings are established. In the above image, we have chosen to not require a "user" to register in order to create tickets.
</p>
<br /># post-install-config

<p>
<img src="https://i.imgur.com/rI3QcFO.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, is the addition of new "Agents". The above image shows the addition of an "Agent" named "Jane Doe" and the creation of their respective access credentials. Please note: "Agents" and "User" credentials are fictitious and created for the sole purpose of this project demonstration. Access credentials have all since been disabled. 
</p>
<br /># post-install-config


<p>
<img src="https://i.imgur.com/HcaclSj.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, the image above depicts the addition of a second new "Agent" named "John Doe" and their respective access credentials. 
</p>
<br /># post-install-config

<p>
<img src="https://i.imgur.com/ali3lI9.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, is the creation of "Users". The above image shows the creation of a fictitious user named "Karen Karen". 
</p>
<br /># post-install-config

<p>
<img src="https://i.imgur.com/Ssfgm5L.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, is the creation of SLA plans or Service Level Agreements which set the outline for ticket severity and timeframe for ticket resolution. The above image shows the addition of a SEV-A Plan which is the highest level of ticket priority status that sets a ticket resolution timeframe of 1 hour 24/7hrs a day.
</p>
<br /># post-install-config

<p>
<img src="https://i.imgur.com/EqOuGxn.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, is the creation of a SEV-B ticket priority status plan which sets the timeframe for ticket resolution of 4hrs 24/7. 
</p>
<br /># post-install-config

<p>
<img src="https://i.imgur.com/Fy4rQL7.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, is the creation of a SEV-C ticket priority status plan which sets the ticket priority timeframe for resolution at 8hrs AND only takes into account a business's standard business hours of operation which are typically Monday-Friday 8-5 pm Eastern Standard time(US).
</p>
<br /># post-install-config

<p>
<img src="https://i.imgur.com/eDzpVjT.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The above image shows the successful creation of SEV-A, SEV-B and SEV-C Plans!
</p>
<br /># post-install-config

<p>
<img src="https://i.imgur.com/jvrjK29.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, the aove image shows the creation of "Help Topics" and their respective levels of priority. "Help Topics" help streamline end-user's help desk experience and to ensure each ticket's proper assignment and prompt response time. 
</p>
<br /># post-install-config


