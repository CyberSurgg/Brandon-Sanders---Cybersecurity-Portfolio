Cybersecurity Incident Report: 
Network Traffic Analysis

Part 1: Provide a summary of the problem found in the DNS and ICMP 
traffic log.


The UDP protocol reveals that: The UDP protocol reveals that the system attempted to send DNS requests to port 53 but received an ICMP error saying that port was unreachable.

This is based on the results of the network analysis, which show that the ICMP echo reply returned the error message: The network analysis showed an ICMP message saying that UDP port 53 is unreachable.

The port noted in the error message is used for: DNS used to convert domain names into IP addresses such as IPv4.

The most likely issue is: The most likely issue is port 53 is blocked or unavailable, possibly due to a firewall.





Part 2: Explain your analysis of the data and provide at least one cause of the incident.
Time incident occurred: The incident happened between 13:24 and 13:28 based on the timestamps in the logs.

Explain how the IT team became aware of the incident: The IT team became aware of the incident after user reported not being able to access the website.

Explain the actions taken by the IT department to investigate the incident: To investigate the incident, the IT team first attempted to reach the website but were unsuccessful. They then used a network analyzer, tcpdump, to capture and analyze the network traffic while attempting to load the page again.

Note key findings of the IT department's investigation (i.e., details related to the port affected, DNS server, etc.): The investigation revealed that DNS requests were failing because the system received ICMP messages saying that UDP port 53 was unreachable.

Note a likely cause of the incident: A likely cause of this incident is a firewall blocking traffic on port 53.

The tcpdump logs show DNS requests sent using UDP to port 53. However, the DNS server responds with ICMP error messages saying that UDP port 53 is unreachable.
This shows that the DNS service cannot be reached.

Time incident occured:
Between 13:24 and 13:28 based on the timestamps in the logs.

Explain how the IT team became aware of the incident:
Users reported they could not access the website and received a “destination port unreachable” error.

Current status:
The website cannot be reached because the DNS requests to the server are failing.

Information discovered during investigation:
UDP packets were sent to port 53 for DNS resolution, but ICMP messages returned stating “UDP port 53 unreachable”.

Next troubleshooting steps:
The next step would be to check the firewall configuration to see if that's what the problem is.

Suspected root cause:
DNS service unavailable. 


