# Networking Notes
##Cybersecurity Basics
##CIA Triad
The CIA Triad is the foundation of cybersecurity:
- Confidentiality: Ensures that sensitive data is accessed only by authorized users. (Example: passwords, encryption) 
- Integrity: Ensures that data is accurate and not altered by unauthorized users. 
- Availability: Ensures that systems and data are accessible when needed.

Types of Cyber Threats:
-	Phishing: A social engineering attack where users are tricked into revealing sensitive information through fake emails or websites. 
-	Malware: Malicious software designed to harm systems (e.g., viruses, worms, trojans). 
-	DDoS (Distributed Denial of Service): Overloads a server with traffic to make it unavailable. 
-	SQL Injection: Attacker injects malicious SQL queries to access or manipulate database data. 
-	Brute Force Attack: Trying multiple password combinations until the correct one is found. 
-	Ransomware: Malware that locks or encrypts data and demands payment to restore access.

##Attack Vectors
-	Social Engineering: Manipulating people into revealing confidential information. 
-	Wireless Attacks: Exploiting insecure Wi-Fi networks. 
-	Insider Threats: Threats from employees or trusted individuals misusing access.

----

##Networking Basics
## OSI Model
The OSI Model explains how systems communicate over a network.

Layers:
1. Physical - Transmits raw bits  
2. Data Link - Error-free transfer  
3. Network - Routing using IP  
4. Transport - Reliable delivery (TCP/UDP)  
5. Session - Manages sessions  
6. Presentation - Data formatting & encryption  
7. Application - User-level services  

## TCP/IP Protocol Suite

TCP (Transmission Control Protocol):
Reliable and connection-oriented communication.

UDP (User Datagram Protocol):
Fast and connectionless communication.

## DNS (Domain Name System)
Converts domain names (like google.com) into IP addresses.

## HTTP vs HTTPS

HTTP (HyperText Transfer Protocol):
Transfers data in plain text (not secure)

HTTPS (HyperText Transfer Protocol Secure):
Uses SSL/TLS encryption to secure communication

## IP Addressing

An IP address uniquely identifies a device on a network.

Types:
- IPv4 (e.g., 192.168.1.1)  
- IPv6  

Also:
- Private IP (local network)  
- Public IP (internet)  

## Subnetting

Divides a network into smaller subnets.

Benefits:
- Better performance  
- Improved security  
- Efficient traffic management  

Uses subnet mask (e.g., 255.255.255.0)

## NAT (Network Address Translation)

Maps private IPs to a public IP.

Benefits:
- Saves IP addresses  
- Adds security by hiding internal IPs  

## Networking Commands

ip a - show IP address  

ping <ip> - test connectivity  

netstat -tuln - show open ports  

traceroute <ip> - trace route  
