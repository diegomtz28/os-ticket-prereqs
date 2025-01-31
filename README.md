<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable IIS in Windows with CGI
- Install PHP manager and configure PHP 
- Install Rewrite Module
- Set up my SQL Database
- Download and install OS-ticket

<h2>Installation Steps</h2>

__Step 1: Enable IIS and Windows CGI__ 
- Enable IIS and CGI in __Windows Features__.
  -  Enable IIS and CGI in __Windows Features__.
  -  Open __Control Panel__ > __Programs and Features__ > __Turn Windows features on or off.__
  -  Enable __IIS__ and check box for __CGI__ under __World Wide Web Services__.
  
<img src="https://github.com/diegomtz28/os-ticket-prereqs/blob/main/enabling%20iis.png"/>

__Step 2:__ Install PHP Manager and Configure PHP
- Install __PHP manager__ and Configure for __IIS__ and ensure PHP is installed. 
- Enable required PHP extensions
- Download and install PHP Manager for IIS.
- Set PHP to a recommended version and enable required extensions using PHP Manager.

<img src="https://github.com/diegomtz28/os-ticket-prereqs/blob/main/Installing%20PHP.png"/>

__Step 3: Install Rewrite Module__
- Install the __URL Rewrite Module__ for IIS
- Download and install the __URL Rewrite Module__ from the IIS website to enable URL rewriting in OS-Ticket

<img src="https://github.com/diegomtz28/os-ticket-prereqs/blob/main/Rewrite%20Module.png"/>

__Step 4:__ Set UP MySQL workbench or phpMyAdmin to create a new database. 
- Create a new __MySQL Workbench__ or --phpMyAdmin to create a new database
- Use my __SQL Workbench __phpMyAdmin__ to create a new database 
- Create a user with permissions for the OS-Ticket database

<img src= "https://github.com/diegomtz28/os-ticket-prereqs/blob/main/Sql%20Database.png"/>

__Step 5: Download and Install OS-Ticket__
- Download the latest OS-Ticket version, extract it, and run the installer. 
- Download the OS-Ticket from the official site, and extract the files to your IIS Directory.
- Open your browser and access the OS-Ticket installer, follow the steps to connect the database, and complete the setup.
- After installation, remove the setup folder for security.

<img src= "[https://github.com/diegomtz28/os-ticket-prereqs/blob/main/Sql%20Database.png]"/>

