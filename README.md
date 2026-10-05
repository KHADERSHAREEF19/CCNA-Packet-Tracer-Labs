# 🌐 CCNA Packet Tracer Labs

<table>
  <tr>
    <td width="60%">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ2MJfpLy0b-DGvT31YkAb84zeizi5Io37olnVZhlZIYQ&s=10" alt="CCNA Banner" width="100%">
    </td>
    <td width="40%">
       <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3UyY3JyeXlmeG1ib2FvNnJmZ3hna2p1b3BxdzNmMXpqcG1veTQ3OCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/1msHsbhybB80DJZRoL/giphy.gif" alt="CCNA Packet Tracer Lab Demo" width="380">
    </td>
  </tr>
</table>


<p align="center">
  A hands-on collection of networking labs built using Cisco Packet Tracer while learning CCNA networking fundamentals.
</p>

---

## 🎬 Lab Overview

This repository documents my practical learning journey through CCNA networking concepts using Cisco Packet Tracer.

Rather than only studying networking theory, I use these labs to build, configure, test, and troubleshoot network topologies.

Each lab contains the original Cisco Packet Tracer file along with documentation explaining what was configured and how the network was verified.

The repository will gradually progress from basic network communication to switching, VLANs, routing, subnetting, and more advanced networking concepts.

---

## 🎯 Objectives

The main goals of this repository are to:

- Build a strong foundation in networking fundamentals.
- Practice CCNA concepts through hands-on labs.
- Understand how packets move through a network.
- Develop structured configuration and troubleshooting habits.
- Document my learning in a clear and reproducible format.
- Build networking knowledge that can later be applied to firewalls and cybersecurity.

---

## 🧪 Lab Repository

| Lab | Topic | Key Concepts | Status |
|-----|------|--------------|--------|
| [LAB1](./LAB1/) | Basic LAN Connectivity | IP addressing, ICMP, ARP | ✅ |
| [LAB2](./LAB2/) | MAC Address Learning | Switching, MAC table | ✅ |
| [LAB3](./LAB3/) | ARP Investigation | ARP request/reply, MAC resolution | ✅ |
| [LAB4](./LAB4/) | VLAN Fundamentals | VLANs, access ports | 🚧 |
| [LAB5](./LAB5/) | VLAN Trunking | 802.1Q, trunk links | ⏳ |

> This table will be updated as new labs are added.

---

## 📁 Lab Structure

Every lab is maintained in its own folder.

Example:

    LAB1/
    ├── README.md
    ├── LAB1.pkt
    └── images/
        └── topology.png

Each lab contains:

- 📘 `README.md` — Explanation and configuration steps
- 🖥️ `.pkt` — Working Cisco Packet Tracer topology
- 🖼️ `images/` — Topology diagrams or verification screenshots

---

## 🛠️ Tools Used

### 🛠️ Cisco Packet Tracer

[Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer) is the primary network simulation tool used to build, configure, and test the labs in this repository.

It allows me to practice:

- Router configuration
- Switch configuration
- IPv4 addressing and subnetting
- ARP and MAC address learning
- VLANs and trunking
- Static and dynamic routing
- Network troubleshooting

🔗 Download from here: [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer)
---

## 🧠 Skills & Concepts Covered

The labs in this repository progressively cover networking fundamentals through switching, routing, and basic network security.

### 🌐 Networking Fundamentals

- What a computer network is and how devices communicate
- LAN and WAN concepts
- Network topologies
- Network devices and their roles
- Routers, switches, end devices, and network interfaces
- Bandwidth, latency, and basic network performance concepts

### 🧩 OSI & TCP/IP Models

- OSI 7-layer model
- TCP/IP model
- Role of each network layer
- Encapsulation and de-encapsulation
- PDUs: data, segments, packets, frames, and bits
- How data moves through a network

### 📦 Ethernet & Packet Flow

- Ethernet frames
- Source and destination MAC addresses
- Source and destination IP addresses
- How a packet travels from source to destination
- Same-network vs remote-network communication
- Default gateway behavior
- Packet Tracer Simulation Mode for packet analysis

### 🔌 Switching Fundamentals

- How Ethernet switches operate
- MAC address learning
- MAC/CAM address tables
- Frame forwarding and filtering
- Unknown unicast flooding
- Broadcast traffic
- Broadcast domains
- Collision domains

### 🔎 ARP & ICMP

- ARP requests and replies
- IP-to-MAC address resolution
- ARP tables
- ICMP
- Ping and connectivity testing
- Basic packet-level troubleshooting

### 🌍 IPv4 Addressing

- IPv4 address structure
- Network and host portions
- Private and public IPv4 addresses
- Subnet masks
- Network addresses
- Broadcast addresses
- Valid host ranges
- Default gateways

### 🧮 Subnetting

- Binary and decimal conversion
- CIDR notation
- Calculating network addresses
- Calculating broadcast addresses
- Determining valid host ranges
- Dividing networks into smaller subnets
- Variable Length Subnet Masking (VLSM)

### 🏷️ VLANs & Trunking

- VLAN concepts
- Access ports
- VLAN membership
- Broadcast-domain segmentation
- IEEE 802.1Q trunking
- Native VLAN concepts
- Communication between switches
- Inter-VLAN routing

### 🛣️ Routing

- How routers forward packets
- Routing tables
- Connected routes
- Static routes
- Default routes
- Route selection
- Inter-VLAN routing
- Introduction to dynamic routing

### 🚚 TCP & UDP

- Transport-layer communication
- TCP vs UDP
- TCP connection establishment
- TCP three-way handshake
- Port numbers
- Well-known ports and services
- Connection-oriented vs connectionless communication

### 🔐 Network Security Fundamentals

- Basic ACL concepts
- Permitting and denying network traffic
- Traffic filtering
- Network segmentation
- Introduction to firewall policy thinking
- Basic network troubleshooting methodology

## 🗺️ Learning Path

The labs are organized progressively so that each topic builds on concepts learned in previous labs.

    Networking Fundamentals
              ↓
        OSI & TCP/IP
              ↓
    Ethernet & Packet Flow
              ↓
       IPv4 Addressing
              ↓
          Subnetting
              ↓
      Switching Basics
              ↓
    MAC Address Learning
              ↓
          ARP & ICMP
              ↓
         TCP & UDP
              ↓
           VLANs
              ↓
       802.1Q Trunking
              ↓
    Inter-VLAN Routing
              ↓
       Static Routing
              ↓
       Default Routing
              ↓
      Dynamic Routing
              ↓
       ACL Fundamentals
              ↓
    Network Troubleshooting
              ↓
     Firewall Fundamentals
              ↓
    FortiGate & Security
The long-term goal is to connect CCNA networking knowledge with firewall administration and cybersecurity troubleshooting.

---

## ▶️ How to Use These Labs

1. Open the desired `LAB` folder.
2. Read the lab's `README.md`.
3. Review the topology and objectives.
4. Download the `.pkt` file.
5. Open it using Cisco Packet Tracer.
6. Recreate or inspect the configuration.
7. Perform the verification tests described in the README.
8. Try troubleshooting the topology by intentionally changing configurations.

---

## 📈 Progress

🟢 Completed  
🟡 Currently Learning  
⚪ Planned

Progress will be continuously updated as I complete additional labs.

---

## 👨‍💻 About This Repository

This repository is part of my hands-on networking and cybersecurity learning journey.

My goal is not simply to collect Packet Tracer files, but to document what I configured, why it works, how I verified it, and what I learned from each lab.

Future projects will extend these networking fundamentals into firewall configuration, FortiGate, network security, and real-world troubleshooting.

---

## 📌 Repository

🔗 [CCNA Packet Tracer Labs](https://github.com/KHADERSHAREEF19/CCNA-Packet-Tracer-Labs)

---

<p align="center">
  <b>Built while learning, testing, breaking, and troubleshooting networks.</b>
</p>
