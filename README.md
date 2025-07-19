# 🏦 ITI-Bank Network Infrastructure Project

## 🔧 Project Objectives

- Design a **scalable** and **secure** network for a bank branch.
- Implement **subnetting** and **VLAN segmentation**.
- Configure **inter-VLAN routing** using Router-on-a-Stick.
- Enable **OSPF** for dynamic routing between routers.
- Secure access with **SSHv2** and **port security**.
- Ensure end devices can communicate across VLANs and remote offices.

---

## 🖥️ Network Structure

### 🔢 Subnetting
- Network: `172.16.10.0/24`
- Subnet Mask: `/27`
- Subnets Created: 8 (using **Fixed Length Subnet Masking**)

### 🧩 VLANs
- **VLAN 10** – Management (CEO)  
- **VLAN 20** – Marketing (Copywriters)  
- **VLAN 30** – Accounting (Dialers)  
- **VLAN 100** – Native VLAN (for trunk links)

### 🌐 Router-on-a-Stick
- Sub-interfaces configured on **R1** to enable **inter-VLAN routing**.

### 🔁 Dynamic Routing
- **OSPF** implemented on routers **R1**, **R2**, and **R3**.

### 🔐 Security
- **SSHv2** enabled on **R3** and **S1-Office3**.
- **Port security** enabled on all access ports.

---

## 📁 Files Included

- `Project Documentation.docx` – Full documentation of IP assignments and network design.
- `ITI-Bank Network Project.pkt` – Cisco Packet Tracer file (lab setup and configurations) *(not included here – to be added)*.
- `FLSM Subnetting Table.docx` – Subnetting table using Fixed Length Subnet Masking.
- `Project Topology.png` – Visual representation of the network.
- `README.md` – Project overview.

---

## ✅ Skills Demonstrated

- Network design and IP planning
- VLAN and inter-VLAN configuration
- Routing protocol implementation (**OSPF**)
- SSH and switch port security configuration
- Realistic documentation and topology visualization
