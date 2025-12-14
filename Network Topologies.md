# 🧩 Network Topologies

## 📌 What is a Network Topology?

A **network topology** refers to the **physical or logical layout** of how devices are connected to each other in a network.

It defines:
- How devices are interconnected
- How data flows between devices
- How the network is structured

🔐 **Cybersecurity Importance:**  
The topology of a network directly affects:
- Performance
- Fault tolerance
- Security
- Attack surface

---

## ⭐ Star Topology

### 📖 Description
- All devices are connected to a **central device** (router or switch)
- Each device has a **dedicated link** to the central node
- Data passes through the central device before reaching the destination

### ✅ Advantages
- Easy to install and manage
- Failure of one device does not affect others
- Centralized monitoring and control

### ❌ Disadvantages
- If the central device fails, the **entire network fails**
- Requires more cabling compared to some other topologies

### 🔐 Cybersecurity Perspective
- Centralized control makes monitoring and access control easier
- Central device becomes a **high-value target** for attackers
- Strong security is required on routers/switches

---

## 🕸️ Mesh Topology

### 📖 Description
- Devices are connected to **multiple other devices**
- Data can travel through **multiple paths**
- Can be:
  - **Full Mesh:** every device connected to every other device
  - **Partial Mesh:** only some devices have multiple connections

### ✅ Advantages
- Very high reliability and fault tolerance
- No single point of failure
- Strong network resilience

### ❌ Disadvantages
- Expensive to implement
- Complex to configure and maintain
- Requires more cabling and management

### 🔐 Cybersecurity Perspective
- Difficult for attackers to bring down the entire network
- High availability improves defense
- Multiple paths increase complexity of monitoring and security management

---

## 🚌 Bus Topology

### 📖 Description
- All devices are connected to a **single main cable** called the bus
- Data is broadcast along the cable
- All devices receive the data, but only the intended device accepts it

### ✅ Advantages
- Simple design
- Low cost
- Uses less cable

### ❌ Disadvantages
- Failure of the main cable affects the whole network
- Performance degrades as devices increase
- Difficult to troubleshoot

### 🔐 Cybersecurity Perspective
- Data is visible to all connected devices
- High risk of:
  - Eavesdropping
  - Data interception
- Least secure topology

---

## 🔐 Importance of Topology in Cybersecurity

Network topology determines:
- How data moves through the network
- Where firewalls and security controls should be placed
- How vulnerable the network is to attacks

Choosing the right topology helps in designing:
- Secure networks
- Reliable communication
- Scalable infrastructure

---

## 📌 Summary

- **Star Topology:** Centralized control, easier security management
- **Mesh Topology:** High availability, strong resilience
- **Bus Topology:** Simple but less secure and less reliable

---

⭐ *These notes are written for learning, revision, and cybersecurity fundamentals.*

