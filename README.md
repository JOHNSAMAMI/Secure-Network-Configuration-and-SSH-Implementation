# Secure-Network-Configuration-and-SSH-Implementation

Project Overview
This project involved configuring secure passwords and implementing SSH for a router and switch in a simulated network environment using Packet Tracer. The goal was to enhance security measures before deployment, ensuring that unauthorized access is mitigated, and sensitive data is protected.
Business Understanding
In today’s digital landscape, cybersecurity is paramount for protecting organizational assets and sensitive information. Ensuring that network devices are configured with strong security measures prevents unauthorized access and reduces the risk of data breaches. By implementing secure configurations, businesses can maintain compliance with industry standards and build trust with their clients.
Tools and Frameworks Used
•	Packet Tracer: A network simulation tool for configuring and testing networking devices.
•	Router and Switch Devices: Configured using Cisco IOS commands.
Project Description
The project began with the configuration of a router (RTA) and a switch (SW1) to meet security requirements specified by a network administrator.
Part 1: Router Configuration
1.	IP Addressing: Configured the router's IP address and enabled the interface.
2.	Basic Security Measures:
o	Encrypted plaintext passwords using the service password-encryption command.
o	Set a minimum password length to 10 characters, ensuring stronger passwords are used.
o	Created a strong secret password for device access.
o	Disabled DNS lookup to prevent unnecessary delays when entering incorrect commands.
o	Set the domain name to netsec.com, ensuring proper identification.
o	Created a local user with a strong encrypted password for enhanced security.
o	Generated 1024-bit RSA keys for secure SSH communication.
o	Configured security measures to block login attempts after multiple failures, adding a layer of protection against brute-force attacks.
o	Set up the VTY lines for SSH access, ensuring that local user profiles were used for authentication.
o	Configured an inactivity timeout for sessions on VTY lines to automatically log off idle users.
o	Saved the configurations to NVRAM to ensure persistence after reboots.
Part 2: Switch Configuration
1.	Switch Setup: Configured the switch with a hostname and IP addressing.
2.	Security Enhancements:
o	Disabled all unused switch ports to reduce the attack surface and prevent unauthorized access.
o	Repeated similar security configurations as done on the router, including encryption of passwords, SSH setup, and user management.
The project successfully demonstrated the critical steps needed to secure network devices before deployment, including implementing SSH for secure remote management.
Conclusion: By configuring secure passwords and SSH, the network devices are better protected against unauthorized access and cyber threats. This project highlights the importance of establishing robust security protocols in network management, laying the groundwork for secure and reliable network operations. Implementing these best practices not only enhances security but also contributes to overall organizational resilience against cyber threats.


