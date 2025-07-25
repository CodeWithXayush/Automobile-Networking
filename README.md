# Automobile Industry Network System – Case Study 🚗🌐

This project is a detailed case study on designing a secure, scalable, and efficient network for an automobile industry setup using Cisco Packet Tracer.

## 📌 Project Overview

The aim of the project is to propose a modernized network architecture that integrates both wired (LAN) and wireless (WLAN) connections across six major departments. The implementation is done using **Cisco Packet Tracer**, simulating all essential networking operations.

---

## 🧠 Objectives

- Upgrade and enhance the flexibility of the existing network.
- Integrate secure communication between departments.
- Enable file transfers via FTP and DNS resolution via DNS server.
- Test network using CLI tools like ping and FTP commands.
- Implement routing, VLANs, and IP management for better control.

---

## 🏢 Departments Covered

1. Server Room
2. Design Labs
3. Manufacturing Unit
4. Conference Hall
5. Sales Reception
6. Factory Outlet

---

## 🛠 Technologies & Tools Used

- Cisco Packet Tracer
- Star Topology (Logical & Physical)
- LAN/WLAN
- FTP, DNS, DHCP Servers
- CLI Commands

---

## 🔧 Network Devices Used

- 3 × 2811 Routers
- 6 × 2960-24TT Switches
- 2 × Access Point PT
- 1 × FTP Server
- 1 × DNS Server
- 1 × DHCP Server
- 1 × Web Server
- 11 × PC PT
- 11 × Laptop PT
- Copper straight-through & Serial DCE Cables

---

## 🧩 IP Allocation (Sample)

**Design Labs (192.168.0.0):**
- DHCP Server: `192.168.0.100`
- PC: `192.168.0.1` – `192.168.0.2`
- Laptop: `192.168.0.6` – `192.168.0.7`

**Manufacturing Unit (10.10.0.0):**
- PC: `10.10.0.1` – `10.10.0.2`
- Laptop: `10.10.0.3` – `10.10.0.4`

(Other subnet ranges listed in full report)

---

## ⚙️ Key Implementations

- VLAN setup for different departments.
- FTP operations: `put` and `get` file from server.
- Static & dynamic IP setup.
- Use of WIC–2T module for router expansion.
- Server connectivity testing from all departments.

---

## 📁 Simulation Operations

1. Created & transferred file from PC to FTP server.
2. Retrieved files using FTP `get` command.
3. Verified inter-device connectivity using ping.
4. Simulated message transfer between devices.

---

## 🧪 Testing & Results

- Verified connectivity for all subnets.
- Successfully demonstrated FTP upload/download.
- Ensured server access from all PCs & laptops.
- Performed simulations for VLAN testing.

---

## 📌 Conclusion

The designed network architecture fulfills the requirements of a secure, flexible, and fail-safe industrial networking system. It enables optimized data sharing and connectivity across all six departments with both LAN and WLAN support.

---

## 🚀 Getting Started

**Ayush Kumar**  
B.Tech CSE | Data Analyst Enthusiast  
[LinkedIn]( http://www.linkedin.com/in/ayush-kumar-4137 ) | [GitHub]( https://github.com/CodeWithXayush )
├── README.md
├── report/
│ └── automobile_networking_report.docx
├── simulation/
│ └── automobile_network_design.pkt (optional: Cisco Packet Tracer file)

