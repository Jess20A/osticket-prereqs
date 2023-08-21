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

- Azure Virtual Machine
- Internet Information Services
- PHP Manager
- Rewrite Module
- PHP 7.3.8
- VC Redist x86.exe
- MySQL 5.5.62
- OsTicket v1.15.8
- HeidiSQL

<h2>Installation Steps</h2>


![image](https://github.com/Jess20A/osticket-prereqs/assets/142112890/d8f5706f-27fb-4679-b0b1-52ec32f6bae5)


<p>
Create a Windows 10 Virtual Machine using Azure and afterwards connect to it by using Remote Desktop. Copy your public IP Address and type your password to connect. 
</p>

![image](https://github.com/Jess20A/osticket-prereqs/assets/142112890/0edfa8d7-c3ee-44c5-b91a-4b497255a9b7)


Install and enable IIS in Windows with CGI. Once in the windows features, start by checking the box for Internet Information Services. Expand World Wide Web Services followed by Application Development Features and checking the CGI and Common HTTP Features boxes. To test IIS go to a web browser and type 127.0.0.1, it should load the IIS webpage if all worked well.
</p>
<br />

![image](https://github.com/Jess20A/osticket-prereqs/assets/142112890/53ccb7f8-cb81-4334-b23e-1e606d8f61e4)

All of these files will have to be dowloaded in order to have OsTicket up and running correctly.
</p>
<br />

![image](https://github.com/Jess20A/osticket-prereqs/assets/142112890/fc8a3d7f-d249-459b-ab8e-892958b52e77)
