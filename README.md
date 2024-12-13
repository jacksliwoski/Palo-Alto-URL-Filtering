<h1>Palo Alto Firewall URL Filtering</h1>


<h2>TLDR Description</h2>
Configuring URL filtering on Palo Alto 220 Firewall
<br />

<h2>Purpose</h2>
The purpose of this lab is to filter out unwanted or potentially harmful content and traffic for both the users and the network itself through the Palo Alto Firewall. It imitates organization policy such as schools, and professional organizations to make sure the network is not exposed to malicious or inappropriate websites.
<br />

<h2>Background Info</h2>
URL filtering is essentially a type of internet traffic filtering which blocks and allows certain websites and resources based on known or suspected malicious activity. Some websites that administrators might want to block could be phishing websites which could potentially put some of their companies employees credentials at risk, not safe for work sites/non work appropriate sites, and websites that attempt to download malicious software.
<br />

<h2>Lab Summary</h2>
In this lab we configured URL filtering policies by using the GUI, first we went through the URL filtering profiles and allowed for override on the site access tab and continue for after user credentials are submitted on categories we do not want common users on our network to be able to access. Then we set our security profile group to pull from our url filtering profile and allow for admin override after entering admin credentials.
<br />

<h2>Network Diagram</h2>
<p align="center">
  <img src="https://i.imgur.com/z6KSqzd.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Walk-Through:</h2>

<p align="center">
Configuring the shopping category to allow for admin override and continue to the site after valid admin credentials are submitted.<br/>
<img src="https://i.imgur.com/UlYxP15.png" height="80%" width="80%" alt="Palo Alto Firewall Factory Reset Steps"/>
<br />
<br />
Configure security profile<br/>
<img src="https://i.imgur.com/9TuBZqF.png" height="60%" width="60%" alt="Palo Alto Firewall Factory Reset Steps"/>
<br />
<br />
Configure admin override<br/>
<img src="https://i.imgur.com/P529DEH.png" height="80%" width="80%" alt="Palo Alto Firewall Factory Reset Steps"/>
<br />
<br />
<img src="https://i.imgur.com/TPGEmWc.png" height="60%" width="60%" alt="Palo Alto Firewall Factory Reset Steps"/>
<br />
<br />
The prompted admin override page that we were looking for, proves filtering and possible admin override is working.<br/>
<img src="https://i.imgur.com/2otyiO4.png" height="80%" width="80%" alt="Palo Alto Firewall Factory Reset Steps"/>
<br />
<br />
</p>

<h2>Conclusion</h2>
In this lab I factory reset a Palo Alto 220 Firewall after conducting research to find information on how to do so seeing as I had no prior knowledge on how to perform the objective. I had very little issues completing this lab as it’s main purpose was to simply set up for future labs. It also got me comfortable with using the Palo Alto’s console which I used to initiate the factory reset process. After this lab was completed the firewall was wiped of prior configuration and ready for me to start my own configuration.
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
