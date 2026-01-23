🌐 Network Layer (OSI Layer 3)

The Network Layer is responsible for delivering data from the source device to the destination device across different networks.

It focuses on where the data should go and how it should reach there, not on applications or message order.

Main Responsibilities of the Network Layer

The Network Layer has three main parts:

Logical Addressing

Routing

Path Determination

1️⃣ Logical Addressing (IP Addressing)

Logical addressing means assigning a unique IP address to every device on a network.

IP address identifies a device globally

Used to communicate across different networks (internet)

Works at the Network Layer

Example:

Mobile phone: 192.168.1.10

Laptop: 10.0.0.5

Google server: 142.250.195.46

When data is sent:

Source IP → sender’s IP address

Destination IP → receiver’s IP address

IP addresses are used instead of MAC addresses because MAC works only inside a local network.

2️⃣ Routing

Routing is the process of forwarding data from one network to another using routers.

Routers operate at the Network Layer

Router reads the destination IP address

Decides the next router to forward the data

Example:

Data path:

Sender → Router A → Router B → Router C → Receiver


Each router:

Checks destination IP

Forwards the packet to the next hop

This forwarding process is called routing.

3️⃣ Path Determination

Path determination means selecting the best possible path to reach the destination network.

The Network Layer chooses paths based on:

shortest distance

fastest speed

least traffic (congestion)

Real-life example:

Going from hostel to college:

Road 1: Short but heavy traffic

Road 2: Long but less traffic

You choose Road 2 because it is faster overall.
This decision is similar to path determination in networking.

If one path fails:

Another path is automatically selected

How the Network Layer Works (Simple Flow)

Transport Layer passes data to the Network Layer

Network Layer adds:

Source IP address

Destination IP address

Best path is selected

Data is routed through multiple routers

Data reaches the destination network

Network Layer Protocols

IP (Internet Protocol) – logical addressing and packet delivery

ICMP – error reporting

Routing protocols (used by routers):

RIP

OSPF

BGP

Key Point Summary

Network Layer works with IP addresses

Handles routing and path selection

Responsible for inter-network communication

Routers operate at this layer
