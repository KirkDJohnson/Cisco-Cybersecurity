<h1>Various hands-on short cybersecurity and networking labs</h1>



<h2>Description</h2>
Throughout the Cisco Cybersecurity analyst pathway on Skillsforall[.]com I took note of some of labs and coding exercises that I completed. Due to this being so long ago much of the work I did was lost. But these exercises highlight some of the activities I completed. However, it did vastly boost my Cisco command line knowledge.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Cisco IOS</b> 
- <b>Cisco Router</b>

<h2>Environment</h2>

- <b>Cisco Packet Tracer</b> 

<h2>Coding/Lab Overview</h2>

<p align="center">
 <h3>Zone-Policy Based Firewall Lab Description</h3>
Due to the amount of explanation needed for the first exercise, I decided to make a brief discussion here. <br/>
Zone-Based Policy firewalls was a concept that was heavily covered in one of the courses. It involved creating two or more security zones that identify different parts of network through ports on a cisco router or switch. In the lab I created a security zone for traffic flowing within the same local network and traffic flowing from and to the internet (public). After creating the security zones, I created a basic access-list allowing traffic from the 192.168.3.0/24 network to pass and there an implicit deny any traffic in the access-list for traffic not matching the permit addresses. I then created a policy-map and class type to inspect any traffic travelling from the private security zone to the public security zone and traffic travelling only in the private zone. Any incoming public traffic that did not originate first from the private network will be dropped. Lastly, I configured the zone-member with the policy map to the ports on the router.<br/>
<img src="https://github.com/KirkDJohnson/Cisco-Cybersecurity/assets/164972007/7f7d94dd-4ee4-44d8-9956-b1cfcefe9e8c" 
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
