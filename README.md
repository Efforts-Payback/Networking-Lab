# Mini Network Lab

A beginner-friendly network simulation project built in Cisco Packet Tracer to understand basic LAN setup, IP configuration, and connectivity testing.

## Overview
This project creates a small virtual network using 2–3 PCs and a switch (optionally a router). It demonstrates how devices communicate within a local area network and lays the foundation for learning routing and access control.

## Features
- Basic LAN topology with PCs and a switch
- Manual IP addressing
- Ping tests to verify connectivity
- Optional router integration for multi-network communication

## Tools Used
- **Cisco Packet Tracer** (by Cisco Networking Academy)

## Steps to Build
1. **Install Cisco Packet Tracer**  
   - Download from [Cisco Networking Academy](https://www.netacad.com/).
   - Create a free account if required.

2. **Create Network Topology**
   - Add 2 PCs and 1 switch.
   - Connect them using copper straight-through cables.

3. **Assign IP Addresses**
   - Example:
     - PC1 → `192.168.1.2` (Subnet mask: `255.255.255.0`)
     - PC2 → `192.168.1.3` (Subnet mask: `255.255.255.0`)

4. **Test Connectivity**
   - From PC1 terminal, run:
     ```
     ping 192.168.1.3
     ```
   - If replies are received, the network is working.

5. **(Optional) Add Router**
   - Add a router to connect multiple networks.
   - Configure basic routing to enable communication between different subnets.

## Deliverables
- `.pkt` (Packet Tracer) project file
- Screenshots of topology and successful ping results

## Learning Objectives
- Understand the basics of LAN configuration
- Practice IP addressing and subnetting
- Familiarize with network testing using ping
- Introduction to router setup and routing principles

---

⚠️ **Note**: This project is a simulation for educational purposes only and does not represent a live production environment.
