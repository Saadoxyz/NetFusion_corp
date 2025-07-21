<img width="978" height="335" alt="image" src="https://github.com/user-attachments/assets/d2ae6070-2cd4-4727-b034-73ac41008762" />
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
<svg width="650" height="220" xmlns="http://www.w3.org/2000/svg">
  <style>
    .box { fill: #333; stroke: #0ff; stroke-width: 2; rx: 6; }
    .text { font: bold 13px sans-serif; fill: #fff; text-anchor: middle; }
    .iot { fill: #88f; stroke: #fff; stroke-width: 2; rx: 6; }
  </style>
  <!-- Router -->
  <rect x="275" y="20" width="100" height="40" class="box"/>
  <text x="325" y="45" class="text">Router</text>
  <!-- Switches -->
  <rect x="100" y="80" width="100" height="40" class="box"/>
  <text x="150" y="105" class="text">Switch 1</text>
  <rect x="450" y="80" width="100" height="40" class="box"/>
  <text x="500" y="105" class="text">Switch 2</text>
  <!-- Departments -->
  <rect x="30" y="140" width="90" height="40" class="box"/>
  <text x="75" y="165" class="text">HR Dept</text>
  <rect x="150" y="140" width="90" height="40" class="box"/>
  <text x="195" y="165" class="text">Finance</text>
  <rect x="470" y="140" width="90" height="40" class="box"/>
  <text x="515" y="165" class="text">IT Dept</text>
  <!-- Server Farm -->
  <rect x="275" y="140" width="100" height="40" class="box"/>
  <text x="325" y="165" class="text">Server Farm</text>
  <!-- IoT -->
  <rect x="580" y="140" width="60" height="40" class="iot"/>
  <text x="610" y="165" class="text">IoT</text>
  <!-- Lines -->
  <line x1="325" y1="60" x2="150" y2="80" stroke="#0ff" stroke-width="2"/>
  <line x1="325" y1="60" x2="500" y2="80" stroke="#0ff" stroke-width="2"/>
  <line x1="150" y1="120" x2="75" y2="140" stroke="#0ff" stroke-width="2"/>
  <line x1="150" y1="120" x2="195" y2="140" stroke="#0ff" stroke-width="2"/>
  <line x1="500" y1="120" x2="470" y2="140" stroke="#0ff" stroke-width="2"/>
  <line x1="500" y1="120" x2="610" y2="140" stroke="#0ff" stroke-width="2"/>
  <line x1="325" y1="60" x2="325" y2="140" stroke="#0ff" stroke-width="2"/>
</svg>




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
