<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable IIS in Windows with CGI
- Install PHP manager 
- Install the Rewrite Module
- Set up Database (SQL)
- Download OSticket

<h2>Installation Steps</h2>

<p> Create an Azure virtual machine, Windows 10, with 4 VCPUs. 
</p>
<img src="https://github.com/diegomtz28/os-ticket-prereqs/blob/main/Creating%20Vitrual%20Machine.png"/>

</p> Using the public IP address from your VM, remote into it using Microsoft Remote Desktop.
<p>
<img src="https://github.com/diegomtz28/os-ticket-prereqs/blob/main/Loggin%20in%20to%20vm.png"/>
</p>
<br />

<p> Once you're in we can go ahead and install/enable IIS in Windows with CGI.

  - Internet Information Service -> World Wide Web Services -> Application Development Features -> CGI
<img src="https://github.com/diegomtz28/os-ticket-prereqs/blob/main/enabling%20iis.png"/>
</p>
<p> After enabling IIS, we can now install PHP. 
<img src="https://github.com/diegomtz28/os-ticket-prereqs/blob/main/Installing%20PHP.png"/>

<p>After PHP, we can now install the Rewrite Module</p>
<img src="https://github.com/diegomtz28/os-ticket-prereqs/blob/main/Rewrite%20Module.png"/>
<br />

<p> For the last step before installing our OSticket, we need to install a database. 
<img src= "https://github.com/diegomtz28/os-ticket-prereqs/blob/main/Sql%20Database.png"/>
</p> Now we can install Osticket and be able to use it. 
<img src= "<img src= "https://github.com/diegomtz28/os-ticket-prereqs/blob/main/Sql%20Database.png"/>
<p> For the last and final step we restart IIS and we can now access our ticketing system. 
  Within IIS, Go to sites -> Default -> osTicket
On the right, click “Browse *:80”

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
