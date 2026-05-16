# DNS and DHCP Implementation for Business Networks

A comprehensive network infrastructure simulation built to provide centralized IP address management, domain name resolution, and verified network communication for business environments. 

Developed as an academic project for **CET161 – Network Basics (Fall 2025)** at **El Sewedy University of Technology (SUT)**.

---

## 🚀 Project Overview

This project demonstrates a functional Wide Area Network (WAN) spanning multiple sites. It is designed to target small and medium-sized offices that require stable connectivity and efficient device communication without complex administration. 

### 🛠️ Key Features & Services
* **Network Topology:** Three interconnected routers forming a WAN, with each router connected to an access switch and multiple client workstations.
* **DHCP Service:** Automated dynamic IP address allocation, providing clients with valid IPs, subnet masks, default gateways, and DNS server addresses.
* **DNS Service:** Internal DNS records configured to resolve domain names, allowing devices to communicate using names instead of IP addresses.
* **Email Service:** Email servers configured to allow successful message exchange between internal users across different network sites.
* **Departmental Subnetting:** Structured IP allocation for distinct departments including Administration, Finance, HR, and the main Company network.

---

## 🗂️ Repository Contents

* **`project.pkt`**: The main Cisco Packet Tracer simulation file containing the complete configured network.
* **`Project Documentation Network Basics.docx`**: Technical documentation detailing the configuration, administrative actions, security checks, and connectivity verification logs.
* **`Business Plan.docx`**: A commercial strategy document outlining the revenue model, target market (SMEs), and future growth strategies like cloud-based DNS/DHCP services.
* **`IP's.xlsx` / `IP's.csv`**: A detailed spreadsheet mapping the static IPs assigned to servers, routers (R1, R2, R3), and specific users across the network.
* **Screenshots**: Visual proof of successful ping tests, email delivery, and server configurations.

---

## ⚙️ Verification & Testing
The network has been fully tested and verified using standard networking protocols:
* No IP address conflicts detected.
* Successful ICMP (ping) communication between all clients, servers, and router-connected sites.
* DNS resolution confirmed operational via `nslookup`.

---

## 👤 Author
* **Omar Ahmed Ramadan**
