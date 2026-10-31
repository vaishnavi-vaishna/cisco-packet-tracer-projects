# 🌐 Network Design Portfolio

This repository showcases my hands-on Cisco Packet Tracer projects built during my journey to become a network engineer.  
Each project demonstrates core networking concepts such as VLAN segmentation, inter-VLAN routing, OSPF, NAT, DHCP, and secure remote management (SSH and ACLs).

---

## 🧱 Projects Overview

### 🏢 [Company Network Design & Implementation](./company-network-design/README.md)
**Level:** Advanced  
**Focus:** Hierarchical Network Design, Enterprise Redundancy, VLAN Segmentation, OSPF Routing, Security Implementation. 
**Highlights:**
- Implementation of core, distribution, and access layers to provide network redundancy.
- VLANs configured for Sales & Marketing, HR & Logistics, Finance & Accounts, Admin & PR, ICT, and a dedicated Server Room.
- OSPF utilized as the primary routing protocol alongside dedicated DHCP server configuration for dynamic IP assignment.
- Integration of Port-Security (sticky MACs) for the finance department, SSH for secure remote device management, and NAT Overload/PAT for multi-ISP connectivity.
- WLAN setup featuring Access Points deployed across all office departments.

### 🏫 [Campus Network Design & Implementation](./college-campus-network/README.md)
**Level:** Intermediate  
**Focus:** Hierarchical Network Design, Multi-site Campus Topology, VLANs, Router-on-a-stick, DHCP, and RIP Routing
**Highlights:**
- Implemented Core, Distribution, and Access layers using Multi-layer switches.
- Created specific VLANs for departments including Admin, HR, Finance, Business, Engineering, Arts & Design, IT.
- Configured Inter-VLAN Routing using sub-interfaces for efficient departmental communication.
- Deployed router-based DHCP server pools for dynamic IP allocation across all faculty and student labs.
- Implemented RIP version 2 to manage internal routing between the Main Campus and Branch Campus.
- Integrated a cloud-based email server with static routing and validated end-to-end connectivity

### ☕ [Coffee Shop Network](./coffee-shop-network/README.md)
**Level:** Beginner / Intermediate  
**Focus:** Small Business Network Infrastructure, VLAN Segmentation, Router-on-a-Stick, DHCP, SSH, and Access Control Lists (ACLs).
**Highlights:**
- Designed a secure, logical network topology tailored for retail operations.
- Implemented VLANs to isolate traffic for Management, Point of Sale (POS), Guest Wi-Fi, and Network Management.
- Configured Router-on-a-Stick for Inter-VLAN routing across the four logical segments.
- Deployed router-based DHCP services with static address reservations for critical infrastructure like printers.
- Secured the network infrastructure using SSH for remote management and console port protection.
- Applied standard ACLs to enforce traffic policies, ensuring guest Wi-Fi isolation from internal business resources.
- Verified end-to-end network connectivity and security policy enforcement through comprehensive testing.

## ⚙️ Technologies Used
- VLANs & Trunking  
- Inter-VLAN Routing  
- DHCP & DHCP Relay  
- OSPF Dynamic Routing  
- NAT / PAT  
- ACLs & SSH Management  
- ASA Firewall  
- GRE Tunnel & IPsec  

---

## 🧠 About This Portfolio
This repository demonstrates both design and configuration skills across small to medium-sized networks.  
All projects were built and tested using **Cisco Packet Tracer**, with documentation created in **VS Code**.

---

## 📫 Connect with Me
**LinkedIn:** [Vaishnavi SA](https://www.linkedin.com/in/vaishnavivaishna/)  
**GitHub:** [vaishnavi-vaishna](https://github.com/vaishnavi-vaishna)  
**Tagline:** *Aspiring Network Engineer | Cisco Packet Tracer Projects*
