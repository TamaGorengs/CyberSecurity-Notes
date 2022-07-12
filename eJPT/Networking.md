# Protocol
---
1. Devices talk to each other by *Protocol*
2. protocol ensure  different devices & hardware can communicate

## Packet
---
1. Primary goal of networking is to exchange information between networked computers which carried by *packet*
2. Packet is a stream of bits running as electric signals on physical media used for data transmission. can be through wire in LAN or the air in WiFi
3. These electrical signals are then interpreted as bits (0 & 1) that make up the information
4. Every Packet has the structure
![[Pasted image 20220712094749.png]]
- *Header* ensures that the receiving host can correctly interpret the payload and handle the overall communication
- *Payload* is the actual inforamation. Could be part of email message or content file during a download
![[Pasted image 20220712095005.png]]

## Protocol Layers

---

# Internet Protocols (IP)
1. IP is rotocol that runs on the Internet Layer of the internet Protocol suitem also known as TCP/IP
2. IP is in charge of delivering the datagrams (IP packets are called datagrams) to the hosts involved in a communication, and it uses IP addresses to identify a host

## IPv4 Addresses
1. Internet uses it's addressing scheme to deliver packets to the right destination
2. Any host on a computer network, be it a private netowrk or the internet, is identified by a *unique IP address.*
3.  Majority run on IP version 4 (IPv4)
4.  IPv4 consist of four bytes, or ctets; a byte consists of 8 bits
- eg : 73.5.12.132