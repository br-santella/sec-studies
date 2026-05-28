# 📙🔐​ Pre-Security Notebook
Main concepts of the Pre-Security Learning Path by TryHackMe. Access: https://tryhackme.com/paths

## 🌐 Network Fundamentals

### 🖥️ What is a Network?
A **network** is a collection of connected things. While we see networks in everyday life (like public transit or the power grid), in computing, a network refers to **technological devices connected together to share data**.
* Can scale from just **2 devices** to **billions** (like the global internet).
* **Cybersecurity Connection:** You cannot protect a system without understanding how data moves through it.

---

### 🌍 The Internet: Public vs. Private
The Internet is a "network of networks." It connects billions of smaller networks together. Networks generally fall into two categories:

| Network Type | Description | Example |
| :--- | :--- | :--- |
| **🔒 Private Network** | A closed, internal network where devices connect locally. | Your home Wi-Fi or a corporate office network. |
| **🌐 Public Network** | An open network accessible to anyone, connecting private networks together. | The Internet. |

---

### 🆔 Identifying Devices on a Network
To communicate, devices use two main types of identification: **IP Addresses** (logical) and **MAC Addresses** (physical).

#### 📍 IP Address (Internet Protocol)
An IP address is a **logical identifier** assigned to a device on a network for a period of time.
* **The Rule:** An IP address must be unique within its specific network. Two devices cannot share the same IP address on the same network at the same time.
* **Protocols:** IP addresses follow strict formatting rules (protocols) so different devices can speak the same language.
* **Dual Identity:** A single device will have a **Private IP** for its local network and a **Public IP** to communicate over the internet.

#### 🛠️ MAC Address (Media Access Control)
A MAC address is a **physical, permanent identifier** burned into a device's Network Interface Card (NIC) at the factory. 
* **Format:** A 12-character hexadecimal number (base-16), usually split by colons or hyphens.
* **Structure:** It is split cleanly into two halves:

```text
 Example MAC:  A4 : C3 : F0 : 85 : AC : 2D
              |-----------| |-----------|
                Vendor ID     Unique Device ID
               (Manufacturer)   (Serial No.)
