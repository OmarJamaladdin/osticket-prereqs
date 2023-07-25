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

- Enabling IIS in Windows with CGI and common HTTP features.
- Install PHP Manager for IIS
- Install MySQL Server



<h2>Installation Steps</h2>

![image](https://github.com/OmarJamaladdin/osticket-prereqs/assets/140512686/13caa205-61d3-49e7-bdd3-3537b3e80620)


IIS is a webserver that is required for OsTicket to run on. To enable IIS, I had to visit the programs section of my Windows 10 VM and then click on (Turn Windows programs on or off) which allowed me to adjust the settings of the Internet Information Services.

![image](https://github.com/OmarJamaladdin/osticket-prereqs/assets/140512686/ef2bff0b-bccd-4b78-ab36-0f1ff224adad)

Here I had to create a directory for PHP on the local hard drive (c drive) and after downloading the PHP files I extracted the zip files into the new PHP folder. I also downloaded/installed C++ Redistr to work with PHP pertaining to URL rewrites when using OsTicket.

![image](https://github.com/OmarJamaladdin/osticket-prereqs/assets/140512686/73ffb33c-d9b3-40b4-9398-0befae9bb197)

Here I installed MySQL server which installs a datatbase on to the computer to store things like the actual tickets in OsTicket as well as users information.

![image](https://github.com/OmarJamaladdin/osticket-prereqs/assets/140512686/1e29c9eb-d6bc-4610-94d7-0a7561cab42e)

Finally I installed OsTicket and HeidiSQL. First I had to run IIS as an admin in order to register PHP from within IIS using the PHP folder I created earlier in the project. After installing OsTicket, I revisited IIS > php manager to enable more PHP extensions required by OsTicket. Lastly, I had to set up my Help Desk and Admin user settings for the OsTicket system as well as install HeidiSQL. HeidiSQL allows me to connect to the SQL server I created earlier in the project and set up a database for OsTicket to use.

![image](https://github.com/OmarJamaladdin/osticket-prereqs/assets/140512686/a833678e-d33d-4a8c-9a9e-8fb68f70e01b)

<br />
