# 🔗 Data Link Layer (OSI Layer 2)

The Data Link Layer is responsible for **node-to-node delivery of data within the same local network**.

It ensures that data sent from one device reaches the **correct device on the same network without errors**.

While the Network Layer handles communication **between different networks**, the Data Link Layer handles communication **inside a single network**.

---

## Main Responsibilities of the Data Link Layer

The Data Link Layer has **three main responsibilities**:

* Framing
* Physical Addressing (MAC Addressing)
* Error Detection

---

## 1️⃣ Framing

Framing means dividing the data into smaller units called **frames**.

* Network Layer gives data in the form of **packets**
* Data Link Layer converts those packets into **frames**

A frame contains:

* Data (payload)
* MAC address of sender
* MAC address of receiver
* Error checking information

### Example:

Imagine putting a letter into an envelope:

* Letter = Data
* Envelope = Frame
* Address on envelope = MAC address

So, framing is like **packing data into envelopes** for delivery inside the local network.

---

## 2️⃣ Physical Addressing (MAC Addressing)

Each device on a network has a **MAC (Media Access Control) address**.

* MAC address is a **physical address**
* It is **unique** for every network device
* Used to deliver data within the same local network

### Example:

If your laptop sends data to a printer on the same Wi-Fi:

* Source MAC = your laptop’s MAC
* Destination MAC = printer’s MAC

Switches use **MAC addresses** to send frames to the correct device.

> IP address is used to reach the correct **network**.
> MAC address is used to reach the correct **device inside that network**.

---

## 3️⃣ Error Detection

The Data Link Layer checks if the frame was damaged during transmission.

It adds an error-checking value called **FCS (Frame Check Sequence)**.

At the receiver side:

* Frame is checked
* If error is found → frame is discarded

This layer can **detect errors**, but usually retransmission is handled by the **Transport Layer**.

---

## Devices Working at Data Link Layer

* Switch
* Bridge
* Network Interface Card (NIC)

These devices use **MAC addresses** to forward data.

---

## How the Data Link Layer Works (Simple Flow)

1. Network Layer sends a packet
2. Data Link Layer:

   * Converts packet into frame
   * Adds source and destination MAC addresses
   * Adds error detection bits
3. Frame is sent through the Physical Layer
4. Receiver checks frame for errors
5. If correct → sent to Network Layer

---

## Key Point Summary

* Works inside a local network
* Uses MAC addresses
* Converts packets into frames
* Detects transmission errors
* Switches operate at this layer
