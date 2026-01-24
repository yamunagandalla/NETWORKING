# ⚡ Physical Layer (OSI Layer 1)

The Physical Layer is the **lowest layer** of the OSI model.
It is responsible for **transmitting raw bits (0s and 1s) over a physical medium**.

This layer deals with the **actual hardware and signals** that carry data between devices.

---

## Main Responsibilities of the Physical Layer

The Physical Layer focuses on **how data physically travels** from one device to another.

Its main responsibilities are:

* Bit Transmission
* Signaling
* Physical Media & Hardware

---

## 1️⃣ Bit Transmission

The Physical Layer converts data into **bits (0s and 1s)** and sends them over the medium.

* No frames
* No packets
* No addresses

Just a stream of **electrical, light, or radio signals** representing binary data.

### Example:

When you send a message:

```
Hi
```

It is converted into binary like:

```
01001000 01101001
```

These bits are what the Physical Layer actually transmits.

---

## 2️⃣ Signaling

Bits are sent in the form of **signals**.

Depending on the medium, signals can be:

* Electrical signals → Copper cables (Ethernet)
* Light signals → Fiber optic cables
* Radio waves → Wi-Fi, Bluetooth

The Physical Layer defines:

* Voltage levels
* Signal timing
* Data transmission speed

---

## 3️⃣ Physical Media & Hardware

This layer includes the actual networking **hardware** used to transmit data.

### Examples of Physical Layer components:

* Ethernet cables
* Fiber optic cables
* Network Interface Card (NIC) hardware
* Hubs
* Repeaters
* Wireless signals (Wi-Fi)

These devices do **not** understand frames or IP addresses.
They only transmit and receive **raw bits**.

---

## What the Physical Layer Does NOT Do

The Physical Layer does not handle:

* IP addresses
* MAC addresses
* Error checking
* Data formatting

All of that is done by **higher layers**.

---

## How the Physical Layer Works (Simple Flow)

1. Data Link Layer sends a frame
2. Physical Layer converts frame into bits
3. Bits are converted into signals
4. Signals travel through cable or air
5. Receiver gets signals and converts back into bits

---

## Key Point Summary

* Lowest layer of OSI
* Transmits raw bits (0s and 1s)
* Uses electrical, light, or radio signals
* Involves cables, NICs, hubs, repeaters
* Does not understand data structure, only signals
