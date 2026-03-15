Incident report analysis
------------------------

Instructions:
As you continue through this course, you may use this template to record your findings after completing an activity or to take notes on what you've learned about a specific tool or concept.
You can also use this chart as a way to practice applying the NIST framework to different situations you encounter.

Summary:
The organization experienced a denial of service (DoS) attack caused by an ICMP flood attack.
This was made possible because the firewall on the network was not properly configured to block or filter excessive ICMP traffic.
The attack disrupted services for approximately 2 hours. The security responded by blocking incoming ICMP packets, taking non-critical services offline,
and restoring critical network services once the attack was contained.

Identify:
The network firewall was not properly configured to filter or limit incoming ICMP traffic. 
This vulnerability allowed a malicious actor to send a flood of ICMP packets and overwhelm the network, resulting in a denial of service (DoS) attack.

Protect:
To protect the network from similar attacks in the future, the organization should implement firewall rules that limit the amount of ICMP traffic allowed to pass in a certain amount of time.
Rate limiting helps prevent attackers from performing Denial of Service (DoS) attacks.

Detect:
Network monitoring software can be used to detect abnormal traffic patterns on the network.
By monitoring network activity in real time, the system can alert security analysts when unusual spikes in traffic occur, 
such as an ICMP flood, allowing the team to investigate and respond more quickly.

Respond:
The incident response team first implemented firewall rules to block incoming ICMP packets and stop the attack traffic.
They then took non-critical network services offline to reduce network load and prevent further disruption.
After the attack was contained, the team restored critical services and began investigating the incident.

Recover:
After the threat was eliminated, the security team restored network services and verified that systems were functioning normally. 
The team also continued monitoring the network to detect any abnormal traffic and help prevent future attacks.




Reflections/Notes:
After the threat was eliminated, the security team restored network services and verified that systems were functioning normally. 
The team also continued monitoring the network to detect any abnormal traffic and help prevent future attacks.


