
# 🏢 NetFusion Corp – Smart Office Network Simulation

![Built with Cisco Packet Tracer](https://img.shields.io/badge/Built%20With-Cisco%20Packet%20Tracer%208.x-blue?style=for-the-badge)
![Language](https://img.shields.io/badge/Socket%20Tool-Python%203.10+-yellow?style=for-the-badge)
![Project Type](https://img.shields.io/badge/Type-Network%20Simulation%20+%20Socket%20Programming-lightblue?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-Intermediate%20to%20Advanced-green?style=for-the-badge)
![License](https://img.shields.io/github/license/saadoxyz/netfusion-smart-office?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

---

> ✨ **Mission:**  
Design and deploy a **smart office network** for **NetFusion Corp**, complete with **department segmentation**, **DHCP & DNS**, **ACL rules**, **web/email servers**, and **IoT sensor simulation** — all powered by **Cisco Packet Tracer** and enhanced with a **Python-based socket communication tool**.

---

## 🚀 Project Highlights

| Section                | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| 🌐 **Network Design**    | 1 Router, 2 Switches, 3 Departments, Server Farm, 2 IoT Devices             |
| 🧱 **VLAN & Routing**    | VLAN 10/20/30 for HR, IT, Finance + Router-on-a-Stick + Trunking           |
| 🔐 **ACL Security**      | Inter-department isolation & limited server access                         |
| 📡 **IoT Integration**   | Simulated sensor data flow to IoT server from IT sector                    |
| 🌍 **Web & DNS Services**| Internal web portal, DNS for `web.netfusion.local`, etc.                   |
| 📧 **Mail Server**       | Functional mail service with ACL to block external access                  |
| 🧪 **Python Chat Tool**  | Internal messaging via Python socket programming (bonus)                   |

---

## 🖥️ Topology Overview (Visual)

### 📊 Smart Office Network Topology

<img width="978" height="335" alt="image" src="https://github.com/user-attachments/assets/d2ae6070-2cd4-4727-b034-73ac41008762" />

---

## 🔧 Configuration Tasks

### 1️⃣ **Network Design**

* ✅ 1 Router, 2 Switches
* ✅ HR, IT, Finance — 2 PCs each
* ✅ Server Farm (Web, DNS, DHCP, Email)
* ✅ 2 IoT devices in IT department

### 2️⃣ **VLANs & Inter-VLAN Routing**

* VLAN 10 → HR
* VLAN 20 → IT
* VLAN 30 → Finance
* Implement trunking & router-on-a-stick (802.1Q)

### 3️⃣ **DHCP & DNS**

* DHCP server assigns IPs to each VLAN
* DNS resolves:

  * `web.netfusion.local`
  * `mail.netfusion.local`

### 4️⃣ **Web & Email Server**

* Web server hosts smart office welcome page
* Email server for internal mail
* Verify access from one PC per VLAN

### 5️⃣ **Access Control Lists**

* HR ❌ IT access
* Finance ➡️ Web server only
* Block public access to email server

### 6️⃣ **IoT Sensor Integration**

* 2 sensors in IT send data to central IoT server
* Simulate real-time data flow

---

## 📦 Tools Used

| Tool                    | Purpose                                 |
| ----------------------- | --------------------------------------- |
| Cisco Packet Tracer 8.x | Network design, VLANs, ACLs, IoT        | |
| Draw\.io / Figma        | Network diagram (SVG/PNG export)        |

---

## 📧 Contact

📩 **Email:** [saado652004@gmail.com](mailto:saado652004@gmail.com)
🐙 **GitHub:** [@saadoxyz](https://github.com/saadoxyz)


---

> 🧠 *"Networks that are smart, segmented, and secure — that's the future of the modern workplace."*

```
