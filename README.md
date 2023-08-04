# osTicket-Prerequisites
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- VM in Azure creation (Resource group, Windows10 with 2-4 VMs)
- Access IIS Management Console
- Register PHP within IIS and install osTicket(extract files and copy within c:\inetpub\wwwroot
- Continue setting up osTicket in browser configure HeidiSQL create user and password.

<h2>Installation Steps</h2>
Creating the VM using windows 10, 4 vCPUs in Microsoft Azure to connect to RDP which will enable us to proceed with the process of creating the osTicketing system.

<img> ![image](https://github.com/AEY982312/osticket-prereqs/assets/116044851/15151880-49eb-46b8-a8c1-53fc2f0495dc) <img>

</p>

Next would be to install IIS in Windows with CGI and common HTTP features. Enabling IIS (Internet Information Services) in Windows and using GCI (Generic CGI) in the osTicket process is crucial for hosting the osTicket application on a Windows server. IIS serves as the web server platform that allows osTicket to be accessed by users over the internet. GCI, on the other hand, enables the execution of CGI scripts required for osTicket's functionality. By enabling IIS and utilizing GCI, organizations can provide a reliable and secure environment for osTicket, ensuring seamless access and efficient ticket management for users.

![image](https://github.com/AEY982312/osticket-prereqs/assets/116044851/6433d5df-28db-43ac-aa51-d22f4a97dc93)
</p>

IIS 

  ![image](https://github.com/AEY982312/osticket-prereqs/assets/116044851/6dedbb06-61b8-4198-a02d-9cee5a329ac4)

Download all installation files PHP Manager for IIS, Rewrite Module, VC_redist.x86.exe., as well as MySQL. I also registered PHP from within IIS in order for osTicket to function properly.

![image](https://github.com/AEY982312/osticket-prereqs/assets/116044851/1a8b114b-3d2f-4058-afa2-c9430e26d1e1)
SQL
![image](https://github.com/AEY982312/osticket-prereqs/assets/116044851/639e67d5-f616-43d9-b947-8d26ab25b2fb)
HEIDISQL
![image](https://github.com/AEY982312/osticket-prereqs/assets/116044851/1f4d88cd-7bdb-4468-88f6-e99f606521de)
REWRITE MODULE
![image](https://github.com/AEY982312/osticket-prereqs/assets/116044851/f0894cda-0612-4ab0-ace5-bd70b7c07502)

After ALL necessary files has been downloaded and files that are needed to be extracted were extracted I continued to proceed with fixing osTicket on the browser to ensure the admin and user acounts were made!

![image](https://github.com/AEY982312/osticket-prereqs/assets/116044851/7894fea4-aa90-491e-9292-3a7e2e33b19e)

![image](https://github.com/AEY982312/osticket-prereqs/assets/116044851/563a88a1-c605-45a9-914f-9f0362ce81bf)




</p>
<br />
