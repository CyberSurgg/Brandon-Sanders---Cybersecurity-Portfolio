Security incident report

Section 1: Identify the network protocol involved in the incident
The first protocol used was DNS, which resolved the domain name to an IP address. After the IP address was returned, the browser used HTTP to request and load the webpage from the web server.





Section 2: Document the incident
The attacker gained unauthorized access to the website’s administrative account through a brute force attack. After getting into the account they modified the website's source code to redirect users to a malicious website “greatrecipesforme.com”. When users visited the website they were prompted to download an executable file. After running the file, users were redirected to a malicious website that contained malware.




Section 3: Recommend one remediation for brute force attacks
I strongly recommend adding Multi-factor authentication to mitigate potential future brute force attacks. This would prevent attackers from repeatedly guessing passwords to gain access to administrative accounts.





