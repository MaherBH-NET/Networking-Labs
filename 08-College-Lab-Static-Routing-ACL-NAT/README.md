# College Lab: Static Routing, ACL, and Static NAT

## 🧭 Overview
This lab combines three major Layer 3 concepts: **Static Routing**, **Access Control Lists (ACLs)**, and **Network Address Translation (NAT)**.  
It demonstrates how routers are configured to control traffic flow, enforce access policies, and enable communication between private and public networks.

---

## ⚙️ Tools Used
- Cisco Packet Tracer  
- Cisco IOS CLI  

---

## 🧩 Key Topics
### 🛰️ Part I – Static Routing
- Manual route configuration using the `ip route` command  
- Route verification using `show ip route`  
- Understanding next-hop addressing and packet forwarding between networks  

### 🔒 Part II – Access Control Lists (ACL)
- **Standard ACL:** Denying or permitting hosts based on source IP addresses (applied closest to the destination)  
- **Extended ACL:** Filtering traffic by both source and destination IP addresses (applied closest to the source)  
- Interface-based ACL application (inbound/outbound)  
- Verifying ACLs using `show access-lists`

### 🌐 Part III – Static NAT
- Configuring **Static Network Address Translation** to map internal private IPs to public IPs  
- Verifying NAT translations using `show ip nat translations`

---

## 🧠 Skills Practiced
- Creating static routes between multiple routers for inter-network communication  
- Implementing and testing both Standard and Extended ACLs for traffic filtering  
- Applying Static NAT for controlled external access  
- Using verification commands (`show ip route`, `show access-lists`, `show ip nat translations`)  

---

## 🚀 Outcome
Successfully configured a multi-router topology with manual routing, ACL-based access restrictions, and static NAT mapping.  
This lab demonstrates full control of routing paths, access permissions, and IP translation at the network edge.

---

## 📂 Files Included
- `Static-Routing-ACL-NAT.pkt`
