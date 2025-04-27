# Wireshark Network Analysis Project

## Overview
This project demonstrates my ability to capture and analyze network traffic using **Wireshark** on **Kali Linux**. I focused on identifying a **TCP 3-way handshake** and an **HTTP GET request**, both fundamental concepts in networking and cybersecurity.



## Tools Used
- **Wireshark** (Packet Capture and Analysis)
- **Kali Linux** (Virtual Machine Environment)
- **Firefox** (For HTTP Traffic Generation)



## Objectives
- Capture and inspect a TCP 3-way handshake (SYN, SYN-ACK, ACK).
- Capture and analyze an HTTP GET request.
- Understand how protocols interact at different layers of the OSI model.
- Strengthen foundational skills in packet analysis and network security.



## Steps Taken
1. Launched Wireshark and selected the correct network interface (e.g., `wlan0`).
2. Started packet capture with no filters applied.
3. Generated traffic by visiting an HTTP-only website: `http://neverssl.com`.
4. Applied display filters (`tcp` and `http`) to isolate relevant packets.
5. Identified the TCP 3-way handshake between client and server.
6. Located and inspected the HTTP GET request packet.
7. Analyzed packet details, including IP addresses, ports, and HTTP headers.



## Key Findings
- Successful identification of the TCP handshake establishing a reliable connection.
- Clear observation of the HTTP GET request method and its associated headers.
- Increased understanding of how web communications work at the packet level.



## Future Improvements
- Capture and analyze HTTPS traffic, focusing on SSL/TLS handshakes.
- Perform deeper packet dissection and export packet data for reporting.
- Expand analysis to include DNS lookups, ARP requests, and ICMP traffic.


## License
This project is for educational purposes only.  
Feel free to use or modify with attribution.
