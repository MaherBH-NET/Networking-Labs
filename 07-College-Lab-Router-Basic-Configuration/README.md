# College Lab: Router Basic Configuration + DHCP + SSH + ARP

## 🧭 Overview
This lab focuses on configuring and securing a Cisco router using essential management and networking services.  
It combines multiple key tasks including router setup, SSH security, DHCP configuration, and ARP verification to demonstrate both administrative and operational network concepts.

---

## ⚙️ Tools Used
- Cisco Packet Tracer  
- Cisco IOS CLI  

---

## 🧩 Key Topics
- Router basic configuration (hostname, console, privilege passwords)
- Enabling and testing SSH secure remote access
- DHCP configuration and IP allocation
- ARP table inspection and simulation

---

## 🧠 Skills Practiced
- Changing router hostname and securing access via console and enable passwords  
- Configuring SSH for encrypted remote management (`ip domain-name`, `crypto key generate rsa`, `username/secret`)  
- Setting up a DHCP pool with excluded addresses and verifying IP allocation to clients  
- Observing ARP table population and message flow in simulation mode  

---

## 🧪 Key Verification Commands
- `show ip dhcp binding`  
- `show ip ssh`  
- `show arp`  
- `arp -a` (on PCs)  

---

## 🚀 Outcome
Successfully configured a router with secure SSH access, dynamic IP assignment using DHCP, and verified ARP operations across connected hosts.  
This lab strengthens understanding of router security, address management, and Layer 2–3 network communication.

---

## 📂 Files Included
- `Router-Basic-Configuration.pkt`
