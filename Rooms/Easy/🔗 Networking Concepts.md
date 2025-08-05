# 🔗 Networking Concepts 
**📅 August 5, 2025 — Day 9**

> *Learn about the ISO OSI model and the TCP/IP protocol suite.*

[🔗 Access the room on TryHackMe](https://tryhackme.com/room/networkingconcepts)

![Networking Concepts](https://raw.githubusercontent.com/TomazMPP/TryHackMe/refs/heads/main/Images/networking-concepts.png)


## Introduction</h2>
Have you ever wondered why you need an IP address to access the Internet? Is it true that an IP address can uniquely identify the user? Are you curious to learn what the life of a packet looks like? If the answer is yes, let’s dive in!

This room is the first room in a series of four rooms dedicated to introducing the user to vital networking concepts and the most common networking protocols:

Networking Concepts (this room)
Networking Essentials
Networking Core Protocols
Networking Secure Protocols

### Learning Objectives</h3>
By the time you finish this room, you will have learned about the following:

ISO OSI network model
IP addresses, subnets, and routing
TCP, UDP, and port numbers
How to connect to an open TCP port from the command line

| Layer Number | Layer Name         | Main Function                                         | Example Protocols and Standards           |
| ------------ | ------------------ | ----------------------------------------------------- | ----------------------------------------- |
| Layer 7      | Application layer  | Providing services and interfaces to applications     | HTTP, FTP, DNS, POP3, SMTP, IMAP          |
| Layer 6      | Presentation layer | Data encoding, encryption, and compression            | Unicode, MIME, JPEG, PNG, MPEG            |
| Layer 5      | Session layer      | Establishing, maintaining, and synchronising sessions | NFS, RPC                                  |
| Layer 4      | Transport layer    | End-to-end communication and data segmentation        | UDP, TCP                                  |
| Layer 3      | Network layer      | Logical addressing and routing between networks       | IP, ICMP, IPSec                           |
| Layer 2      | Data link layer    | Reliable data transfer between adjacent nodes         | Ethernet (802.3), WiFi (802.11)           |
| Layer 1      | Physical layer     | Physical data transmission media                      | Electrical, optical, and wireless signals |

RFC 1918 defines the following three ranges of private IP addresses:

- `10.0.0.0` - `10.255.255.255` (`10/8`)
- `172.16.0.0` - `172.31.255.255` (`172.16/12`)
- `192.168.0.0` - `192.168.255.255` (`192.168/16`)

---

## Questions

**1. Which layer is responsible for end-to-end communication between running applications?**  
Answer: `4 (Transport Layer)`

**2. Which layer is responsible for routing packets to the proper network?**  
Answer: `3 (Network Layer)`

**3. In the OSI model, which layer is responsible for encoding the application data?**  
Answer: `6 (Presentation Layer)`

**4. Which layer is responsible for transferring data between hosts on the same network segment?**  
Answer: `2 (Data Link Layer)`

**5. To which layer does HTTP belong in the TCP/IP model?**  
Answer: `4 (Application Layer)`

**6. How many layers of the OSI model does the application layer in the TCP/IP model cover?**  
Answer: `3 (Session, Presentation, Application)`

**7. Which of the following IP addresses is not a private IP address?**  
Options: 192.168.250.125 | 10.20.141.132 | 49.69.147.197 | 172.23.182.251  
Answer: `49.69.147.197`

**8. Which of the following IP addresses is not a valid IP address?**  
Options: 192.168.250.15 | 192.168.254.17 | 192.168.305.19 | 192.168.199.13  
Answer: `192.168.305.19` 

**9. Which protocol requires a three-way handshake?**  
Answer: `TCP`

**10. What is the approximate number of port numbers (in thousands)?**  
Answer: `65` 

**11. On a WiFi, within what will an IP packet be encapsulated?**  
Answer: `Frame`

**12. What do you call the UDP data unit that encapsulates the application data?**  
Answer: `Datagram` 

**13. What do you call the data unit that encapsulates the application data sent over TCP?**  
Answer: `Segment`

**14. use telnet to connect to the web server on MACHINE_IP. What is the name and version of the HTTP server?**  
Answer: `lighttpd/1.4.63` 

**14. What flag did you get when you viewed the page?**  
Answer: `THM{TELNET_MASTER}` 

# Completed
![Networking Concepts](https://raw.githubusercontent.com/TomazMPP/TryHackMe/refs/heads/main/Images/completed-networking-concepts.png)





|Date                       |      All Time|      All Time|       Monthly|       Monthly|Points    | Rooms     |
|:--------------------------|-------------:|-------------:|-------------:|-------------:|---------:| --------: |
|                           |        Global|        Brazil|        Global|        Brazil|          |           | 
| Aug &nbsp; 5, 2025        |         #359130 |           #6645 |         #12274|          #224 | ?  |       23 |

