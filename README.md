Capture Packet Lab 
<h2>Description</h2>
Successfully completed a hands-on project using Wireshark to capture and analyze network traffic. Gained practical experience in configuring Wireshark on Linux, capturing live packets, and applying display and conditional filters to isolate specific protocols (TCP, HTTP, HTTPS) and IP traffic. Developed a foundational understanding of network communication, troubleshooting, and security analysis. This project enhanced my ability to monitor network performance, identify anomalies, and apply best practices in network security and traffic management.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Wireshark</b> 

<h2>Environments Used</h2>

- <b>wireshark</b> 
- <b>Virtual Machine</b> 

<h2>Program walk-through:</h2>

1) The wired interface includes ethernet packet capture which begin with "en" in the wireshark <br/>
![Image Alt](https://github.com/hass09an/CapturePacketLab/blob/main/Screenshot%202025-01-08%20150932.png?raw=true)

2) Wireshark app include controls to start packet capture; stop capture; save packet to a file and load capture file
![Image Alt](https://github.com/hass09an/CapturePacketLab/blob/e5daa41913253cacc25f8c021aef6960441874a6/logs.png)

3) A capture can only be saved once the cpature has stopped
![Image Alt](https://github.com/hass09an/CapturePacketLab/blob/da2d60a7e7f42822e72f3a830e7826d06bd68d23/Screenshot%202025-01-08%20155028.png)

4) To display only HTTPS traffic, used filter on TCP port (tcp.port == 443)
![Image Alt](https://github.com/hass09an/CapturePacketLab/blob/72f74e021282c08b813eb3081393b332d02b2c7e/task%203.png)

5) TLS Handshake display filter used to detect a website visit in a packet list: (tls.handshake.type == 1)
![Image Alt](https://github.com/hass09an/CapturePacketLab/blob/1daed1351a808cc52b6cc25121dd8ec033c5f918/Tls.handshakes.type%20%3D%3D%201.png)

6) IP address is ued to filter to obtain packet information about website ( ip. addr == ip)
![Image Alt](https://github.com/hass09an/CapturePacketLab/blob/24307cb3a344f997080c17335429394e28c4c656/ip.addr%20%3D%3D%20IP.png)

7) Finally, compound conditional should include parenthses to aviod order of excution errors
![Imagine Alt](https://github.com/hass09an/CapturePacketLab/blob/17987bf0da1e28628a98491807f9e0d34671ea00/not%20.png)



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
