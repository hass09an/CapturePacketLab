Capture Packet Lab 
<h2>Description</h2>
Successfully completed a hands-on project using Wireshark to capture and analyze network traffic. Gained practical experience in configuring Wireshark on Linux, capturing live packets, and applying display and conditional filters to isolate specific protocols (TCP, UDP, HTTP) and IP traffic. Developed a foundational understanding of network communication, troubleshooting, and security analysis. This project enhanced my ability to monitor network performance, identify anomalies, and apply best practices in network security and traffic management.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

The wired interface includes ethernet packet capture which begin with "en" in the wireshark <br/>
![Image Alt](https://github.com/hass09an/CapturePacketLab/blob/main/Screenshot%202025-01-08%20150932.png?raw=true)

Wireshark app include controls to start packet capture; stop capture; save packet to a file and load capture file
![Image Alt](https://github.com/hass09an/CapturePacketLab/blob/main/Screenshot%202025-01-08%20150932.png?raw=true)

A capture can only be saved once the cpature has stopped
![Image Alt](https://github.com/hass09an/CapturePacketLab/blob/da2d60a7e7f42822e72f3a830e7826d06bd68d23/Screenshot%202025-01-08%20155028.png)

To display only HTTPS traffic, used filter on TCP port (tcp.port == 443)
![Image Alt](https://github.com/hass09an/CapturePacketLab/blob/72f74e021282c08b813eb3081393b332d02b2c7e/task%203.png)




<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
