# Networking-Portfolio-Begineers
This contains my homelab project files, screenshots of various projects i created while pursuing the beginner's Computer Networking Udemy course by Alton Instructor
# 🌐 Networking for Non-Techies — Hands-on Lab Portfolio
> **Course Instructor:** Alton (Networking for Non-Techies)

Welcome to my networking portfolio! This repository serves as a digital showcase of the hands-on labs, architectural topologies, and core configuration concepts I mastered during Alton's specialized training program. 

Despite starting from a non-technical background, this course provided me with a deep, practical understanding of network engineering infrastructure, routing, switching, and protocol analysis.

---

## 🛠️ Skills & Technologies Mastered
* **Foundational Layer:** OSI Model (Layers 1-7), TCP/IP Suite, Encapsulation.
* **IP Architecture:** IPv4 Addressing, Variable Length Subnet Masking (VLSM), Classless Inter-Domain Routing (CIDR).
* **Core Switching:** VLANs (Virtual LANs), Inter-VLAN Routing, Broadcast Domains, Access vs Trunk Ports.
* **Routing Foundations:** Static Routing, Default Routing, Basics of Dynamic Routing Protocols.
* **Network Services:** DHCP Server Allocation, DNS Mapping, NAT (Network Address Translation).
* **Security & Analysis:** Access Control Lists (ACLs), Wireshark Packet Inspection, Port Security.

---

## 📁 Repository Structure
The files in this repository are structured exactly to mirror my learning journey:
```text
├── Module-1-Fundamentals/      # OSI Model breakdowns & IP addressing labs
├── Module-2-Switching/         # VLAN allocations & Trunking configurations
├── Module-3-Routing/           # Default routes & Inter-VLAN setup screenshots
└── Module-4-Network-Services/  # DHCP, DNS, and NAT validation labs
```

---

## 💻 Highlighted Lab Projects

### 1. Subnetting & IP Allocation Scheme
* **The Challenge:** Designing an efficient IP addressing scheme for a corporate network to minimize IP wastage.
* **The Solution:** Applied VLSM to divide a single `/24` network into distinct subnets tailored to departmental host requirements (HR, Sales, IT).
* **Key Visual Verification:**
  *(To display your image here, replace the placeholder path below with your actual screenshot path)*
  ![Subnet Design](./Module-1-Fundamentals/your-screenshot-name.png)

### 2. VLAN Segmentation & Trunking
* **The Challenge:** Segmenting network traffic to prevent massive broadcast domains and secure departmental communication.
* **The Solution:** Configured internal VLANs on Layer 2 switches and established an 802.1Q trunk link to allow controlled inter-VLAN routing via a router interface.
* **Key Visual Verification:**
  ![VLAN Config](./Module-2-Switching/your-screenshot-name.png)

### 3. Traffic Filtering with Access Control Lists (ACLs)
* **The Challenge:** Restricting the Guest Network from accessing the sensitive corporate Server Room environment.
* **The Solution:** Deployed standard/extended Access Control Lists (ACLs) closest to the traffic source to filter packets based on destination IP protocols.
* **Key Visual Verification:**
  ![ACL Testing](./Module-4-Network-Services/your-screenshot-name.png)

---

## 🚀 Next Steps on My Career Track
Building upon this core networking blueprint, I am currently expanding my system administration infrastructure skills before pursuing official certifications:
1. 🔲 **In Progress:** Linux System Administration & Windows Server Active Directory Labs
2. 🔲 **Next Milestone:** Cisco CCNA (200-301) Certification
3. 🔲 **Security Baseline:** CompTIA Security+ (Sy0-701)

---
*Feel free to browse through the folders above to review my complete collection of configuration screenshots, packet captures, and network topology maps.*
