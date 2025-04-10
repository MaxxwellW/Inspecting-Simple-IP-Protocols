 <p align="center"> 
<img src="https://i.imgur.com/Z6IAMbi.png" />
</p>
<p>
<h1>Inspecting Network Traffic</h1>
 <p align="center"> 

 <img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
 <p align="center">  
This tutorial outlines how to install WireShark and use Internet Control Message Protocol through the Application
  https://www.wireshark.org/download.html .<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- WireShark
- Powershell

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
<p>
<img src="https://i.imgur.com/LVMtM1B.png" />
</p>
<p>

- Ubuntu 22
<p>
<img src="https://i.imgur.com/GLIn4hX.png" />
</p>
<p>

<h2>Noticable Changes</h2>

  - Replies and Request via ping
  - Running Data


To start, go to the local browser and search for the WireShark website for download and install.
<p>
<img src="https://i.imgur.com/DOpxg8P.png" />
</p>
<p>

Continue to  the 64Bit Variation
<p>
<img src="https://i.imgur.com/lMA8SS5.png" />
</p>
<p>
Open the files after completed download
</p>
<br />

<p>
<img src="https://i.imgur.com/N4guATF.png" />
</p>
<p>
Continue through cofiguration without altering any defaults.
<p>
<img src="https://i.imgur.com/fQWGqMo.png" />
</p>
Once fully completed, open PowerShell in order to communicate with Linux computer.
<p>
<img src="https://i.imgur.com/c2gJ9fJ.png" />
</p>
View incoming traffic in WireShark without a known filter to see a representation of data.

<p>
<img src="https://i.imgur.com/U9isra2.png" />
</p>

Inside of WireShark, input "icmp" to filter ping traffic
<p>
<img src="https://i.imgur.com/QsBK4PW.png" />
</p>

Now inside of PowerShell, type the expression, "ping 10.0.0.4" in order to communicate to the Linux.
(10.0.0.4 is the Private IP of the Linux Virtual Machine)
<p>
<img src="https://i.imgur.com/7pwwQ86.png" />
</p>
After doing this protocol, there should be specified network traffic that shows Windows Private IP (Computer) communicating with Linux
<p>
<img src="https://i.imgur.com/mEQvTqH.png" />
</p>
