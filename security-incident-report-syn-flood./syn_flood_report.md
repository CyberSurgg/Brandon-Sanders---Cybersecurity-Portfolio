Cybersecurity Incident Report

Section 1: Identify the type of attack that may have caused this 
network interruption
One potential explanation for the website's connection timeout error message is: The connection timeout was likely caused by a SYN flood attack that overwhelmed the web server with a large number of connection requests.

The logs show that: The logs show repeated SYN packets sent from the same IP address 203.0.113.0 sent to 192.0.2.1.

This event could be: The event could be a SYN flood attack.





Section 2: Explain how the attack is causing the website to malfunction
When website visitors try to establish a connection with the web server, a three-way handshake occurs using the TCP protocol. Explain the three steps of the handshake:
The client sends a SYN packet to the server to request a connection.

The server sends a SYN/ACK packet back to the client to synchronize and acknowledge.

The client sends an ACK packet back to the server to confirm the connection.

Explain what happens when a malicious actor sends a large number of SYN packets all at once: When a malicious actor sends a large number of SYN packets all at once, the server tries to respond. However the connections stay half-open and the server's resources get overwhelmed.

Explain what the logs indicate and how that affects the server: The logs indicate repeated SYN attempts from the same IP address,  blocking legitimate users from accessing the server. As a result, users experience connection timeouts.

