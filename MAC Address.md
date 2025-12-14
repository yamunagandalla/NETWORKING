# 🌟 MAC Address – Media Access Control

## 1️⃣ What is a MAC Address?
- **MAC = Media Access Control Address**  
- Unique, permanent **hardware ID** given to every network device (laptop, phone, router, WiFi adapter, smart TV, etc.)  

### 🧠 Analogy
- Device’s **fingerprint**  
- Your **network identity** inside a LAN  
- Permanent (does not change unless deliberately spoofed)  

---

## 🔹 Format of a MAC Address
- **12 hexadecimal digits** (0–9, A–F)  
- Examples:  
  - `A4:5E:60:12:3F:9B`  
  - `A4-5E-60-12-3F-9B`  

- **First 6 digits** → Manufacturer ID  
- **Last 6 digits** → Unique device ID  

---

## 🔹 Where MAC Addresses are Used
- **LAN Communication:** Switches use MAC addresses to send data to correct device  
- **Device Identification:** Router knows which device is which  
- **Network Filtering:** Access Points or Firewalls can allow/block devices by MAC  

---

## 🔹 MAC vs IP

| Feature       | MAC                  | IP                  |
|---------------|-------------------|-------------------|
| Type          | Hardware address    | Software address  |
| Changes?      | Permanent           | Can change (dynamic) |
| Layer         | Data Link Layer (Layer 2) | Network Layer (Layer 3) |
| Purpose       | Identify device in LAN | Identify device on Internet |

---

## 🔹 Cybersecurity Perspective
- MAC addresses can be **spoofed** (attacker pretends to be another device)  
- Used in **network filtering & access control**  
- Attackers can **track devices** in public WiFi  
- Important in **ARP spoofing attacks** and **MITM attacks**  

---

## 🔹 How to See Your MAC Address
- **Windows:**  
  ```bash
  ipconfig /all
Look for Physical Address under your network adapter.

Linux:

bash
Copy code
ifconfig
or

bash
Copy code
ip addr
Look for ether.

Android/iPhone:
Settings → About Phone → WiFi MAC Address

💡 Simple One-Line Definition
A MAC address is a permanent, unique hardware ID of every network device used in local networks.
