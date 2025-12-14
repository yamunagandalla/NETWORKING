# 📘 Network Devices 

## 🔹 1) Hub

### ✅ What is a Hub?
A **hub** is a basic networking device that connects multiple computers in a network and **broadcasts data to all devices**.  
It does **not** decide, filter, or know the destination.

### 🔁 How Hub Works
1. Data comes from one computer  
2. Hub sends it to **all connected computers**  
3. Only the intended device processes it  

➡ Hub does **not** know sender or receiver.

### 🧠 Intelligence Level
- Very low (**dumb device**)

### 📡 Network Layer
- Works at **Physical Layer (Layer 1)** of OSI model

### ⚠️ Disadvantages
- Very slow  
- High collision  
- No security  
- Easy sniffing  
- Wastes bandwidth  

### 📌 Where Used?
- Old networks  
- Rarely used today  

### 🛡️ Cybersecurity View
- Very insecure  
- Any device can capture data  
- Easy target for attackers  

### 🧠 One-Line Memory
👉 **Hub = Broadcast device (dumb, insecure)**

---

## 🔹 2) Switch

### ✅ What is a Switch?
A **switch** connects multiple devices and sends data **only to the intended device**.  
Smarter than a hub.

### 🔁 How Switch Works
1. Reads **MAC address**  
2. Stores MAC addresses in a **MAC table**  
3. Sends data **only to the correct port**  

➡ No unnecessary broadcasting

### 🧠 Intelligence Level
- Medium (**smart device**)

### 📡 Network Layer
- Works at **Data Link Layer (Layer 2)**

### ⭐ Advantages
- Faster than hub  
- No collisions  
- Better security  
- Efficient data transfer  

### 📌 Where Used?
- Homes (sometimes)  
- Colleges  
- Offices  
- Labs  
- Server rooms  

### 🛡️ Cybersecurity View
- Harder to sniff data  
- Supports VLANs & port security  
- Vulnerable if misconfigured  

### 🧠 One-Line Memory
👉 **Switch = Sends data using MAC address (smart)**

---

## 🔹 3) Router

### ✅ What is a Router?
A **router** connects **different networks** and routes data using **IP addresses**.  
(Home WiFi box = router)

### 🔁 How Router Works
1. Reads **IP address**  
2. Chooses **best path**  
3. Forwards data between networks (LAN ↔ Internet)  

### 🧠 Intelligence Level
- Very high (**most intelligent device**)

### 📡 Network Layer
- Works at **Network Layer (Layer 3)**

### ⭐ Functions
- IP addressing (DHCP)  
- Internet access  
- Firewall  
- NAT & port blocking  
- Traffic filtering  
- VPN support  

### 📌 Where Used?
- Homes  
- Offices  
- Colleges  
- ISPs  
- Data centers  

### 🛡️ Cybersecurity View
- First line of defense  
- Blocks attacks  
- Controls incoming/outgoing traffic  
- Critical security device  

### 🧠 One-Line Memory
👉 **Router = Connects networks using IP (very smart)**

---

## 📊 Comparison Table (Exam Important)

| Feature       | Hub         | Switch          | Router              |
|---------------|------------|----------------|------------------|
| Intelligence  | Dumb       | Smart          | Very Smart        |
| Address Used  | None       | MAC            | IP                |
| OSI Layer     | Layer 1    | Layer 2        | Layer 3           |
| Speed         | Slow       | Fast           | Fastest           |
| Security      | Very Poor  | Good           | Excellent         |
| Internet      | No         | No             | Yes               |
| Used Today    | No         | Yes            | Yes               |

### 🧠 Final Memory Trick
- **Hub → Broadcast → Dumb**  
- **Switch → MAC → Smart**  
- **Router → IP + Internet → Very Smart**

