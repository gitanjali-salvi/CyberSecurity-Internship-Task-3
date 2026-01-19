# Cyber Security Internship – Task 3  
## Network Traffic Analysis Using Wireshark

---

## Objective
The objective of this task was to capture and analyze live network traffic using Wireshark in order to understand how different network protocols function during real-time communication.

---

## Tools and Environment
- Operating System: Windows  
- Packet Analysis Tool: Wireshark 4.6.3  
- Packet Capture Driver: Npcap  
- Network Interface: Wi-Fi  

---

## Activities Performed

- Installed Wireshark along with the required Npcap driver  
- Started live packet capture on the Wi-Fi interface  
- Generated traffic by accessing multiple websites  
- Observed real-time packet flow during browsing activity  
- Applied protocol-based display filters for analysis  
- Identified encrypted and non-encrypted traffic  
- Captured DNS, TCP, UDP, QUIC, and TLS packets  
- Saved the captured traffic in `.pcapng` format  

---

## Display Filters Used
dns
tcp
udp
tls

---

## Key Observations

- Continuous packets were captured in real time while the system was connected to the internet.  
- DNS queries and responses showed how domain names were resolved into IP addresses.  
- TCP packets displayed sequence numbers, acknowledgments, and reliable communication behavior.  
- Most TCP communication occurred over port 443, indicating secure HTTPS connections.  
- UDP traffic primarily consisted of QUIC packets used by modern web services.  
- TLSv1.2 and TLSv1.3 traffic confirmed that application data was encrypted and not readable.  
- The TCP three-way handshake (SYN, SYN-ACK, ACK) was observed before secure data transmission.  

---

## Files Included in the Repository

- `task3_network_capture.pcapng` – Captured network traffic file  
- `Screenshots/` – Packet analysis and filter results  
- `README.md` – Task documentation  

---

## Learning Outcome

This task provided hands-on experience with live network traffic analysis and helped in understanding how data flows across a network, how protocols communicate, and how encryption protects transmitted information.

---

## Conclusion

By performing this task, I gained practical exposure to packet capturing and analysis techniques and developed a better understanding of real-world network behavior from a cyber security perspective.

---
