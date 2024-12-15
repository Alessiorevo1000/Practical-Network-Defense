# Assignments for Network Security Course

This repository includes two assignments demonstrating practical applications of network security principles:

## Contents

### 1. **Network Hardening** (`Network_Hardening.pdf`)  
This assignment focuses on improving the security of a network through:

1. **Firewall Configuration**:  
   1. Changing firewall management passwords to stronger ones.  
   2. Forwarding logs to a centralized analysis server (Graylog).  
   3. Limiting ICMP traffic to prevent misuse and attacks.  

2. **TLS and Certificates**:  
   1. Replacing default Linux certificates with custom Certificate Authority-issued ones.  
   2. Forcing HTTPS communication across the network.  

3. **Network Monitoring**:  
   1. Scheduling daily vulnerability scans using Greenbone.  

4. **Traffic Rules**:  
   1. Blocking dangerous packets such as ICMP redirects.  
   2. Mitigating attacks using spoofed IPs.  

5. **Additional Enhancements**:  
   1. Configuring a reverse proxy for secure external access to services.  
   2. Addressing vulnerabilities in software like OpenSSL.  

### 2. **VPN Configuration** (`VPN_Configuration.pdf`)  
This assignment involves creating a secure Virtual Private Network (VPN) using two different protocols:

1. **OpenVPN**:  
   1. Configured with AES-256-GCM for encryption and SHA512 for authentication.  
   2. Implemented on port 1194 using SSL/TLS and user authentication.  
   3. Allocated secure IP ranges and DNS services to connected clients.  

2. **IPSec**:  
   1. Configured mutual Pre-Shared Key (PSK) authentication.  
   2. Used AES-256 and Diffie-Hellman Group 14 for secure key exchanges.  
   3. Enabled ISAKMP, NAT-T, and ESP protocols for secure communication.  

3. **Account Management**:  
   1. Created accounts with certificates for user authentication.  
   2. Organized users into groups (e.g., employees, operators) for access control.  

## Usage  
Each PDF outlines the detailed steps and configurations used to achieve robust security measures. The assignments highlight practical strategies to mitigate risks, monitor networks, and implement secure communications. These resources serve as a reference for anyone interested in applying real-world network security techniques.  

Feel free to explore the repository and adapt the configurations as needed!  
