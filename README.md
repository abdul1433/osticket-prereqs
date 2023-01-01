<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)


<h2>Required Prerequisites</h2>

- Heidi SQL
- MySQL 5.5
- Web Platform Installer 5.1
- Information Internet Systems (IIS)

<h2>Installation</h2>

<p>
</p>
<p>

Create a Virtual Machine (Windows 10 Pro) using Microsoft Azure 

Connect to the VM with Remote Desktop 


  
<img src="https://i.imgur.com/XUQUdqX.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<p>

Once you are in the Virtual Machine you will need to enable IIS


Go to "turn windows features on or off" in the control panel and then enable Internet Information Services



</p>  
<img src="https://i.imgur.com/vrutbBO.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
</p>
<p>
We will be using the following link to install the Web Platform Installer and all the required files or applications
https://drive.google.com/drive/u/1/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6

 
Download the Web Platform Installer and open it
Now add and install MySQL 5.5 and add all the version of x86 PHP up until 7.3

(Note: MySQL 5.5 will ask credintials to be created later)


<img src="https://i.imgur.com/sBsGpoU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>
<p>


Once the installation is complete then you will notice that some of the files are failed to install

so we will need to install them manually




<img src="https://i.imgur.com/bn6uo1V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>




Go to the google drive installation files link and download the following files: 

Microsoft C++

PHP Manager for IIS



<img src="https://i.imgur.com/MW4JcdH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 






Next download the osTicket from the installation files: https://drive.google.com/drive/u/1/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6

Within osTicket extract the "uplaod" folder into c:\inetpub\wwwroot

Rename "upload" folder to "osTicket"



  
  

  
</P>
<img src="https://i.imgur.com/6P2UW6q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>







Now open IIS and restart the server 

On the top right under the Connections menu  go to Vm2/Sites/Default Web Site/osTicket

Click on "Browse *:80 (http)" on the right hand side of the screen







</p>
<img src="https://i.imgur.com/PefUR7L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p>
</p>
<p>



The osTicket installer will pop up in the default browser of your virtual machine once you click on "Browse *:80 (http)





</p>
<img src="https://i.imgur.com/streyho.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p>
</p>
<p>



Before we continue to install osTicket we will have to enable some extensions in the PHP manager and assign some permissions

Go back to IIS and go to VM2/sites/Default Web Site/osTicket

Open PHP Manager and under PHP Extensions, click on "enable or disable an extension"

Enable the following extensions:








<img src="https://i.imgur.com/86WXI3r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p>
</p>
<p>




<img src="https://i.imgur.com/YdFg6NP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p>



<img src="https://i.imgur.com/CBnZecV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>                                                                                                 














<img src="https://i.imgur.com/mRV7b39.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>                                                                                                  








<img src="https://i.imgur.com/DuGnMMJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  



  
  

