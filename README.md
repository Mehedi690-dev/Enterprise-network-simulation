A multi-router enterprise network designed in Cisco Packet Tracer featuring RIP v2 dynamic routing, DHCP-based IP allocation, and NAT-enabled internet connectivity.
# Enterprise Network Design using Cisco Packet Tracer

This project demonstrates a **multi-router enterprise network** designed and simulated using **Cisco Packet Tracer**.  
The network includes multiple LANs, dynamic routing, DHCP, and NAT to provide internal communication and internet access.

---

# Project Overview

The objective of this project is to design a scalable and functional enterprise network where:
- Multiple internal networks can communicate with each other
- End devices can automatically obtain IP addresses
- Private networks can access the internet using NAT
- Routing is handled dynamically using RIP v2

---

# Tools & Technologies

- **Cisco Packet Tracer**
- **Routing Protocol:** RIP Version 2
- **IP Addressing:** Static & Dynamic (DHCP)
- **NAT:** Dynamic NAT using NAT Pool
- **Topology Type:** Enterprise / Multi-Router Network

---

# Network Topology

- **ISP Router**
- R1: LAN + DHCP Server
- R2: Distribution Router
- R3: Server Network Router
- R4: Edge Router with NAT
- End Devices: PCs and Server

---

# Features Implemented

# 1. IP Addressing & Subnetting
- LAN networks use `/24`
- Serial WAN links use `/30`
- Public IP block used for NAT

# 2. Dynamic Routing (RIP v2)
- Automatic route advertisement between routers
- End-to-end connectivity ensured

# 3. DHCP Configuration
- Centralized DHCP server on R1
- Automatic IP allocation to end devices

# 4. NAT Configuration
- Private IP addresses translated to public IPs
- Enables internet access for internal networks

# 5. Server Network
- Dedicated server LAN
- Accessible from all internal networks

---

# Verification & Testing

The following tests were performed to verify network functionality:
- `ping` between LANs
- `ping` to public IP addresses
- `show ip route`
- `show ip nat translations`

All tests were successful.

------

# How to Run the Project

1. Open **Cisco Packet Tracer**
2. Load the ptk file
3. Wait for devices to boot
4. Use Command Prompt on PCs or **CLI** on routers to test connectivity

---


# License

This project is created for **academic and learning purposes**.
