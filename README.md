<h1>Various hands-on short cybersecurity and networking labs</h1>



<h2>Description</h2>
Used SSH to remote into a router to create a Zone-Based Policy firewall. Created zones that would pass, drop, or filter traffic from within the local network and when interacting with the public web. Within the Zone-Based Policy firewall, I allow created an access list which would allow ip ranges from a given subnet with an implicit deny all for other traffic. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Cisco IOS</b> 
- <b>Cisco Router</b>

<h2>Environment</h2>

- <b>Cisco Packet Tracer</b> 

<h2>Coding/Lab Overview</h2>

<p align="center">
Once connected to the terminal and logging into the admin account, created two security zones: PUBLIC and PRIVATE<br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created a specfic access list (101) allowing traffic from the 192.163.3.0/24 subnet and assigned it to a class-map <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created a policy-map and class type to define the security zones <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Added the inspect polciy map to all outgoing traffic to the outgoing router's port and the other securoty zonef or traffic that stay in the LAN <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  <br/>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
