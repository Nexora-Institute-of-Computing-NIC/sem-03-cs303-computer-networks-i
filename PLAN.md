# CS303 — Computer Networks I — PLAN

**Semester:** 3 · **Credits:** 4 · **Level:** Intermediate
**Theory:** 45 hrs · **Lab:** 30 hrs · **Tools:** Wireshark, tcpdump, mininet, Python sockets

## Syllabus

### Unit 1 — Introduction and Layered Models (9 lectures)
1. What a network is — goals and challenges
2. Network topologies — LAN, WAN, MAN
3. Circuit switching vs packet switching
4. The OSI seven-layer model
5. The TCP/IP four-layer model
6. Encapsulation and decapsulation
7. Protocol data units at each layer
8. Bandwidth, latency, throughput, jitter
9. Standards bodies — IETF, IEEE, RFCs

### Unit 2 — Physical and Data Link Layers (9 lectures)
1. Physical media — copper, fibre, wireless
2. Signal encoding — NRZ, Manchester
3. Nyquist and Shannon limits
4. Error detection — parity, checksum, CRC
5. Error correction — Hamming codes
6. Framing — byte stuffing, bit stuffing
7. MAC addresses and addressing
8. Multiple access — ALOHA, CSMA/CD, CSMA/CA
9. Ethernet and switched LANs

### Unit 3 — Network Layer (9 lectures)
1. IPv4 addressing and classes
2. Subnetting and CIDR
3. NAT — address translation
4. IPv6 — format and transition
5. ARP and RARP
6. ICMP — ping, traceroute, errors
7. Routing basics — forwarding vs routing
8. Distance-vector routing — RIP
9. Link-state routing — OSPF

### Unit 4 — Transport Layer (9 lectures)
1. Transport services — multiplexing, reliability
2. UDP — header, use cases
3. TCP — three-way handshake, teardown
4. TCP flow control — sliding window
5. TCP congestion control — slow start, AIMD
6. TCP variants — Reno, CUBIC, BBR (overview)
7. Ports and sockets
8. Retransmission and timeouts
9. QUIC — a modern transport protocol

### Unit 5 — Application Layer and Network Programming (9 lectures)
1. Client-server vs peer-to-peer
2. HTTP/1.1, HTTP/2, HTTP/3 — evolution
3. DNS — resolution process and records
4. DHCP — dynamic host configuration
5. Email — SMTP, IMAP, POP3
6. FTP and SFTP
7. WebSockets and long-lived connections
8. Socket programming — TCP and UDP in Python
9. Network tools — curl, dig, netstat, ss

## Practical Labs (18)

1. Wireshark — capture and inspect the first packets
2. Wireshark — analyse a TCP handshake
3. Wireshark — analyse an HTTP request/response
4. `tcpdump` — filter and save captures
5. Packet crafting with Scapy
6. Subnetting calculator — compute network/broadcast ranges
7. Build a small LAN in mininet
8. Ping and traceroute analysis
9. `dig` — query DNS records of multiple types
10. ARP inspection and poisoning demo (isolated lab)
11. TCP socket client and server in Python
12. UDP socket client and server in Python
13. Build a simple HTTP server from sockets
14. Build a chat application using TCP
15. Compare TCP and UDP throughput for the same workload
16. Analyse TCP congestion control with `iperf3`
17. Set up a NAT with iptables
18. DNS resolver from scratch — build a small client

## Assignments

1. Layered model writeup — trace a URL through all layers
2. Subnetting problem set — 10 networks
3. Wireshark analysis report on a real HTTP session
4. TCP vs UDP comparison — coding and analysis
5. Socket programming assignment — a multi-client chat server
