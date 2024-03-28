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
<img src="https://github.com/KirkDJohnson/Cisco-Cybersecurity/assets/164972007/7f7d94dd-4ee4-44d8-9956-b1cfcefe9e8c" 
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
Configuring a short access-list on a cisco router allowing traffic from two IPs and denying/dropping all other traffic<br/>
<img src="https://github.com/KirkDJohnson/Cisco-Cybersecurity/assets/164972007/8296ccfc-db1f-4179-ae47-a17bcd0c9de6" alt="Cisco Work"/>
<br />
<br />
Configured a cisco termainal to be able to be SSH'd into with a RSA encryption key and admin account<br/>
<img src="https://github.com/KirkDJohnson/Cisco-Cybersecurity/assets/164972007/10ce9dd6-bfb7-45fe-ba71-30d2785a93df" alt="Cisco Work"/>
<br />
<br />
 TEXT<br/>
<img src="" alt="Cisco Work"/>
<br />
<br />
TEXT<br/>
<img src="" alt="Cisco Work"/>
<br />
<br />
<h2>Thoughts</h2>
When I first begun to pivot and learn about cybersecurity I took every single cisco cybersecurity module, while it was largely focused on cisco hardware it still gave me a great foundation of concepts and some hands on labs. It was so early in my time learning about cybersecurity I had no idea that I would should save the work and labs I do to add to a portfolio for later, so a considerable amount of work I did was lost. But looking at the Certifications page and my Credly Profile the amount of Cisco Badges for completeing learning paths is immense. The labs I remember to be actually very difficult and having to use outside sources quite a bit because I was new to network fundamentals and cybersecurity. 


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
