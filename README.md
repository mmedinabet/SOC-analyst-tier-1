<h1>SIEM Detection and Response: Junior Analyst Edition</h1>

Start your day as a Junior Security Analyst by reviewing alerts and diving into security monitoring. Analyze network traffic, detect threats, and experience the thrill of incident response. Gain essential knowledge to become a proficient Network Defender.

Review the alerts on your SIEM dashboard. Identify the malicious IP address mentioned in the alerts, take note of it, and proceed by clicking on the alert for further action:
<h1></h1>

![Screenshot 2024-04-14 2 11 55 PM](https://github.com/mmedinabet/SOC-analyst-tier-1/assets/142737434/bd16100d-6610-4f70-99ad-2a73aa40ebd8)

Upon reviewing the SIEM alert, I observed a malicious IP address highlighted within the alerts: 221.181.185.159.

![Screenshot 2024-04-14 2 19 27 PM](https://github.com/mmedinabet/SOC-analyst-tier-1/assets/142737434/f3aaf984-2872-4b00-9d25-5f6c7f5079a9)

Websites provide the capability to verify the reputation of an IP address, aiding in identifying potential malicious or suspicious activity.

![Screenshot 2024-04-14 2 22 19 PM](https://github.com/mmedinabet/SOC-analyst-tier-1/assets/142737434/9585e5d9-768f-4eff-80c7-cfe7d4f5bba1)

As a secuirity analyst, the utilization of various open-source databases such as AbuseIPDB and Cisco Talos Intelligence to conduct reputation and location checks for IP addresses. These tools are invaluable for security analysts during alert investigations. Additionally, reporting malicious IPs to platforms like AbuseIPDB contributes to making the internet safer. After identifing the IP address as malicious, the next step is to escalate it to a staff member for further action. 

![Screenshot 2024-04-14 2 25 25 PM](https://github.com/mmedinabet/SOC-analyst-tier-1/assets/142737434/78d16dd4-355c-45c2-b72b-bf8418eff1fa)

I have escalated the event associated with the malicious IP address to Will Griffin who is SOC Team Lead and the most appropiate member of the team to help disolve the alert. 

![Screenshot 2024-04-14 2 28 11 PM](https://github.com/mmedinabet/SOC-analyst-tier-1/assets/142737434/3472f9f4-a2a3-4373-b8ad-96ce7aacab5e)

Will Griffin, SOC Team Lead, granted permission to block the malicious IP address. Now, I proceed to implement the block rule on the firewall. After blocking the malicious IP address, discover the message left for you by the perpetrators.

![Screenshot 2024-04-14 2 30 52 PM](https://github.com/mmedinabet/SOC-analyst-tier-1/assets/142737434/92b1a0ee-8b11-4833-9c70-e85c7a76f630)

<h2> Summary</h2>
In summary, this lab as a Junior Security Analyst provided hands-on experience in monitoring, analyzing, and responding to security alerts. Using appropriate tools, I identified and escalated a malicious IP address to senior staff for action. With permission granted, I promptly blocked the IP address on the firewall, contributing to network protection. This experience underscores the importance of swift action and collaboration in maintaining cybersecurity defenses
