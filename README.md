# 🔐 Secure Enterprise Network Design

## 📌 Project Overview

This project demonstrates a secure enterprise network designed and implemented using Cisco Packet Tracer.
The goal is to apply cybersecurity principles such as segmentation, access control, and secure communication in a real-world simulation.

---

## 🏗️ Network Topology

![Network Topology](images/topology.png)

### 📝 Description:

This is the full network design including:

* Router for inter-VLAN routing
* Switch for internal connectivity
* PCs representing different departments
* Server for centralized services

👉 This shows the overall structure of the secure network.

---

## 🧩 VLAN Configuration

![VLAN Configuration](images/vlan.png)

### 📝 Description:

The network is divided into four VLANs:

* VLAN 10 → HR Department
* VLAN 20 → IT Department
* VLAN 30 → Guest Network
* VLAN 40 → Server Network

👉 This ensures **network segmentation**, meaning each department is isolated for security.

---

## ⚙️ Access Control List (ACL)

![ACL Configuration](images/acl.png)

### 📝 Description:

ACL rules were applied on the router to:

* Block Guest network from accessing the Server
* Allow controlled communication between VLANs

👉 This implements **Access Control Security**, preventing unauthorized access.

---

## 🔐 Secure Remote Access (SSH)

![SSH Login](images/ssh.png)

### 📝 Description:

SSH was configured on the router to:

* Enable encrypted remote management
* Replace insecure Telnet
* Protect login credentials

👉 This ensures **secure administrative access** to the router.

---

## 🧪 Network Testing (Ping Results)

![Ping Test](images/ping.png)

### 📝 Description:

Testing was performed to verify network security:

* HR → Server ✔️ (Allowed)
* Guest → Server ❌ (Blocked by ACL)

👉 This confirms that security rules are working correctly.

---

## 🔐 Security Principles Applied

* Least Privilege (users only access what they need)
* Network Segmentation (VLAN separation)
* Access Control (ACL restrictions)
* Defense in Depth (multiple security layers)
* Secure Communication (SSH encryption)

---

## 🛠️ Tools Used

* Cisco Packet Tracer

---

## 📌 Conclusion

This project demonstrates how a secure enterprise network can be designed using VLANs, ACLs, DHCP, SSH, and Port Security.
It successfully applies cybersecurity principles in a practical simulation environment.
