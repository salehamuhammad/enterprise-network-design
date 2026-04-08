# Enterprise Network Design & Simulation

A large-scale enterprise network designed and simulated from scratch using **Cisco Packet Tracer**, implementing industry-standard routing protocols, subnetting, and security configurations.

## Features

- **VLSM Subnetting** — Variable Length Subnet Masking for efficient IP allocation across all network segments
- **Multi-Protocol Routing** — OSPF (Area 1 & 2), EIGRP (AS 11), and RIP deployed across separate network blocks
- **Route Redistribution** — Border routers (R1–R4) redistribute routes between OSPF, EIGRP, and RIP domains
- **DHCP** — Centralized dynamic IP assignment for hosts across multiple routing domains
- **NAT** — Network Address Translation on the border router for private-to-public IP mapping
- **Access Control Lists (ACLs)** — Security policies restricting host access to designated servers (Web, Data, TFTP)

## Tools Used
- Cisco Packet Tracer 
- Protocols: OSPF, EIGRP, RIP
- Concepts: VLSM, NAT, DHCP, ACLs, Route Redistribution

