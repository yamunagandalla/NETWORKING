# 📘 Computer Networks – Basics (Cybersecurity-Oriented Notes)

## 📌 What is a Network?

A **network** is a collection of two or more devices that are connected so they can **communicate and share data** with each other.

### Common Devices in a Network
- Computers
- Smartphones
- Servers
- Routers
- Switches
- IoT devices (CCTV, smart TVs, sensors)

### Types of Connections
- **Wired:** Ethernet cables, Fiber optics  
- **Wireless:** Wi-Fi, Bluetooth, Cellular networks  

---

## 🔑 Key Characteristics of a Network

### 1️⃣ Devices Can Send and Receive Data
Devices in a network are not isolated.

- **Sending data:** messages, files, images, requests  
- **Receiving data:** accepting information from other devices  

This two-way communication enables:
- Internet browsing
- Video calls
- File sharing
- Online applications

---

### 2️⃣ Each Device Has a Unique Identity (IP & MAC Address)

Every device must be uniquely identified so data reaches the correct destination.

#### IP Address (Internet Protocol Address)
- Logical address
- Identifies a device’s location in a network
- Used for routing data

#### MAC Address (Media Access Control Address)
- Physical hardware address
- Permanently assigned to the NIC
- Identifies the device at the hardware level

➡️ **IP + MAC together ensure accurate communication**

---

### 3️⃣ Communication Follows Predefined Rules (Protocols)

Devices communicate using standardized rules called **protocols**.

Protocols define:
- Data format
- Transmission method
- Error detection and correction

#### Common Protocols
- **TCP/IP** – reliable data transmission  
- **HTTP / HTTPS** – web communication  
- **FTP** – file transfer  

Without protocols, devices cannot understand each other.

---

### 4️⃣ Data Is Transmitted in Small Units Called Packets

- Large data is divided into **packets**
- Each packet contains:
  - Part of data
  - Destination information
- Packets may take different paths
- Receiver reassembles packets

✅ Improves speed, efficiency, and reliability

---

## 🌐 Why Networks Exist

### 1️⃣ To Share Internet Access
- One internet connection shared among many devices
- Router distributes internet from ISP

🔐 **Cybersecurity Note:**  
One insecure device can compromise the entire network.

---

### 2️⃣ To Share Files and Resources
- File sharing
- Shared printers
- Storage servers
- Common databases and applications

🔐 Improper security can lead to unauthorized access.

---

### 3️⃣ To Enable Communication
Networks support:
- Email
- Messaging
- Voice calls
- Video conferencing

🔐 Communication data is a major target for attackers.

---

### 4️⃣ To Allow Centralized Control and Security
Administrators can:
- Authenticate users
- Monitor activity
- Apply security policies
- Control access

Centralized control helps detect and respond to threats.

---

### 5️⃣ Importance from a Cybersecurity Perspective
- Networks are the **pathway for all data**
- Attackers exploit networks
- Defenders protect networks using:
  - Firewalls
  - IDS/IPS
  - Encryption

➡️ Every cyber attack and defense operates through networks.

---

## 📡 Types of Networks

### 1️⃣ LAN – Local Area Network

#### Definition
Connects devices within a **small area** (home, office, school).

#### Coverage Area
- One room
- One building
- Small campus

#### Examples
- Home Wi-Fi
- Office network
- Computer lab

#### Technical Characteristics
- Very high speed
- Low latency
- Private ownership
- Uses Ethernet or Wi-Fi

#### Cybersecurity Perspective
Common LAN attacks:
- Wi-Fi password cracking
- ARP spoofing
- Packet sniffing
- Man-in-the-Middle (MITM)
- Exploiting vulnerable devices

---

### 2️⃣ WAN – Wide Area Network

#### Definition
Connects multiple LANs over large geographical areas.

#### Coverage Area
- Cities
- Countries
- Entire world

#### Examples
- Internet
- ISP networks (Jio, Airtel, BSNL)
- Corporate global networks

#### Technical Characteristics
- Lower speed than LAN
- Higher latency
- Uses fiber, satellites, leased lines
- Managed by ISPs

#### Cybersecurity Perspective
WAN threats:
- DDoS attacks
- Server exploitation
- Phishing
- Data interception
- Malware distribution

Security focuses on:
- Encryption
- Firewalls
- IDS/IPS
- Secure routing

---

### 3️⃣ MAN – Metropolitan Area Network

#### Definition
Covers a **city or large campus**, connecting multiple LANs.

#### Coverage Area
- City
- Town
- University campus

#### Examples
- Government city networks
- University networks
- Metro fiber networks

#### Cybersecurity Perspective
Vulnerabilities:
- Public Wi-Fi attacks
- Rogue access points
- Traffic monitoring
- Unauthorized inter-LAN access

Security measures:
- Network segmentation
- Authentication
- Encryption

---

### 4️⃣ PAN – Personal Area Network

#### Definition
A small personal network within a short range.

#### Coverage Area
- 1–10 meters

#### Examples
- Bluetooth earphones
- Smartwatch ↔ phone
- Mobile hotspot

#### Technical Characteristics
- Short range
- Low power
- Wireless
- Device-to-device

#### Cybersecurity Perspective
Threats:
- Bluetooth hacking (BlueBorne)
- Unauthorized pairing
- Device tracking
- Data leakage

Security relies on:
- Device updates
- Strong pairing authentication
- Turning off Bluetooth when not needed

---

## 📊 Comparison Table

| Network Type | Coverage Area | Example | Speed | Cyber Risk |
|-------------|--------------|--------|-------|------------|
| PAN | Few meters | Bluetooth devices | High | Medium |
| LAN | Home / Office | Wi-Fi network | Very High | High |
| MAN | City / Campus | University network | Medium | Medium |
| WAN | Countries / World | Internet | Lower | Very High |

---

## 📌 Final Note
Understanding networks is **fundamental to cybersecurity**.

Every:
- Cyber attack  
- Defense mechanism  
- Security tool  

operates **through networks**.

---

⭐ *These notes are written for learning, revision, and cybersecurity foundations.*

