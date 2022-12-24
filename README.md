<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Actions and Observations</h2>

<p>
<img src="https://imgur.com/pOGkZS8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created a windows and a Ubuntu VM machines, pingged the Ubuntu VM from the windows powershell.
</p>
<br />

<p>
<img src="https://imgur.com/RnkmEuz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Disabling inbound ICMP traffic .
</p>
<br />

<p>
<img src="https://imgur.com/fP0lWWS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observed the ping request in windows 10 powershell ICMP traffic request has timed out .
</p>
<br />

<p>
<img src="https://imgur.com/jVoMOde.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Connecting to Ubuntu Virtual Machine via SSH .
</p>
<br />

<p>
<img src="https://imgur.com/he4R6AG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Filtering for SSH traffic using Wireshark .
</p>
<br />

<p>
<img src="https://imgur.com/ShoKnx1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Using ipconfig /renew to retrieve a new IP Address .
</p>
<br />


