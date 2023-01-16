<h1>Network Examination with Wireshark</h1>

<h2>Description</h2>
Project consists of using Wireshark within a Windows 10 environment to monitor network traffic.
<br />


<h2>Utilities Used</h2>

- <b>VirtualBox</b> 
- <b>Wireshark</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Using Wireshark to Examine Live Network Traffic:</h2>
Wireshark is opened and run. After navigating to http://juice-shop.herokuapp.com/#/ it can be noted that Wireshark picked up its traffic. Using nslookup I determined one of the addresses for juice-shop.herokuapp.com and matched it with the address logged in Wireshark: <br/>
<img src="https://imagizer.imageshack.com/img922/170/tfNUGe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wireshark is used to capture the ping to Google's DNS (8.8.8.8): <br/>
<img src="https://imagizer.imageshack.com/img922/9550/8AWOBS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
