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

- osTicket Installation Guide
- Installation Files
- Windows 10 Virtual Machine

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/8krNqwH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I want to preface this by saying that I have utilized a tutorial from the Course Careers Introduction to Information Technology course I recently took. I have gone through this tutorial several times until I was comfortable utilizing a "Simple List" that explained each installation file and how to start the setup. I believe in full transparency and do not want to take credit for this project as my own idea, but I have dived deeper than the tutorial to get a better understanding. This screenshot shows the various downloadable content provided for this project to work. </p>
<br />

<p>
<img src="https://i.imgur.com/feA3kI9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The steps that I took in order to get this webspace up and running within this Windows 10 Server include various web hosting actions. We started off by configuring Internet Information Services (IIS) as an internal web server within the Virtual Machine itself. We then downloaded the configuration files needed such as PHP 7.3.8, MySQL 12.3.0, PHP Manager for IIS, and a few other files needed for the proper function of the osTicket Application. Basically, we did all of the preliminary steps needed to create this live application to function internally within this Virtual Machine itself without actually giving it a specific domain name and setting up the Domain Name System to actually allow external connections from outside of the network. There were settings and permissions that needed to be implemented within the IIS Web Server itself in addition to what I explained, but I thought that may be too much information for this relatively simple project.  </p>
<br />

<p>
<img src="https://i.imgur.com/5l0MWRQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After the initial installation and making sure that the osTicket is available within the Local Host at 127.0.0.1, we then have to finish the actual installation. We set up HeidiSQL as a Database client in order to actually utilize the MySQL services connected to osTicket. We had to set up a "Help Desk Name", an Admin User and set up the actual Database connection that will be used for keeping track of the various data within osTicket itself. </p>
<br />
