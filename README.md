<p align="center">
![image](https://github.com/DannyGrullon/osticket-prereqs/assets/139714290/85c66584-622f-4654-8475-0cd07d729664)


<h1>VPN Setup and Usage (Proton VPN)</h1>
This tutorial outlines the prerequisites and installation of setting and using ProtonVPN.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- WhatismyIPaddress.com
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a resource group.
- Create a Windows 10 Virtual Machine with 2-4 Virtual CPUs
- Change desired region in Virtual Machine settings.
- Open Remote Desktop Connection with public IP address from Virtual Machine.
- Download Proton VPN.


<h2>Installation Steps</h2>

![Screenshot 2023-07-19 172732](https://github.com/DannyGrullon/osticket-prereqs/assets/139714290/ad295341-e367-45e3-b887-95ce3679f60e)
</p>
Start off by creating a new virtual machine and resource group. Select a region where you would like your new VPN. Select Windows 10 Pro as the image and two Virtual CPUs as the size. Open Remote Desktop Connection with the Virtual Machine public IP address and login creditials. Once you connect to the virtual machine, search https://whatismyipaddress.com/ to make sure your VPN is in your desired location.  

<br />
</p>

![image](https://github.com/DannyGrullon/osticket-prereqs/assets/139714290/6e17c159-02e0-449c-a023-4f705fb34d9d)

</p>

Create a free account with Proton VPN. Once you log in, you'll have access to some free locations to set up your new VPN. Once you select your lcoation, Proton VPN will conect you to that locations server and create a tunnel to that server within the virtual machine. 
</p>
<br />

