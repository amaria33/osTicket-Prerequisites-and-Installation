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

- Create a Resource Group in Azure
- Create a Windows 10 VM with 2-4 CPU's in Azure
- Allow it to Create a Virutal Network 
- Remote Desktop In
- Have Installation Files Ready

<h2>Installation Steps</h2>

<p>
   <a href="https://drive.google.com/uc?export=view&id=1kC4pD03Gz82dx62_UzXonAeZbYZqntoF">
    <img src="https://drive.google.com/uc?export=view&id=1kC4pD03Gz82dx62_UzXonAeZbYZqntoF"
    style="width: 900px; max-width: 100%; height: auto"
    title="Click for the larger version." /></a>
</p>
<p>
There are many steps to the installation files. The files consist of PHP Manager for IIS, Rewrite Module, PHP.7.3.8, VC, MySQL, and osTicket. As an entry level help desk technician you won't have to install osTicket but learning how to install software makes for good practices, plus osTicket is Open Source which means it's free to download. 
</p>
<br />

<p>
<a href="https://drive.google.com/uc?export=view&id=14KnYc_O5_1YK37pUmaZFXbVyGN9WYrXP">
    <img src="https://drive.google.com/uc?export=view&id=14KnYc_O5_1YK37pUmaZFXbVyGN9WYrXP"
    style="width: 900px; max-width: 100%; height: auto"
    title="Click for the larger version." /></a>
</p>
<p>
While installing software, there needs to be reinstalls, configurations, and in this case reloads. This is the PHP ISS Manager a graphical tool that allows webserver applications. For us that's osTickets. 
</p>
<br />

<p>
<a href="https://drive.google.com/uc?export=view&id=16SmWInRt5OrnYGLyJxc2HRIy6QEaZVJV">
    <img src="https://drive.google.com/uc?export=view&id=16SmWInRt5OrnYGLyJxc2HRIy6QEaZVJV"
    style="width: 900px; max-width: 100%; height: auto"
    title="Click for the larger version." /></a>
</p>
<p>
This is a long process, osTicket is not installed. As you can see there are some items we need to configure and some features that will need to be enabled in PHP ISS Manager. Once that is complete, along with a couple more tasks, we'll be ready to start taking osTickets. osTickets provides really great documentation and steps on how to complete each step. 
</p>

<a href="https://drive.google.com/uc?export=view&id=19uEf3rUdg2m9PNd_UEkiUFGqNmQGeuOj">
    <img src="https://drive.google.com/uc?export=view&id=19uEf3rUdg2m9PNd_UEkiUFGqNmQGeuOj"
    style="width: 900px; max-width: 100%; height: auto"
    title="Click for the larger version." /></a>
</p>
<p>
The last and biggest step is installing and connecting SQL Server. Every business runs on data, data is KING! You'll need to create a new database and name it osTicket, create a secure document with encryption with logins of the root name, username and password. You'll need this to login to the software. *Please note you can not login with the creditnals on the screenshot, the system has now been deleted. 
</p>

<a href="https://drive.google.com/uc?export=view&id=1e6_wiBKHVJFCoQeVTJsx8irSWOnhK5o6">
    <img src="https://drive.google.com/uc?export=view&id=1e6_wiBKHVJFCoQeVTJsx8irSWOnhK5o6"
    style="width: 900px; max-width: 100%; height: auto"
    title="Click for the larger version." /></a>
</p>
<p>
Rejoice! We have successfully installed osTicket. 
</p>
<br />
