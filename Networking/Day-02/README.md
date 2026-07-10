# Networking - Day 2

## Objective

Understand the OSI (Open Systems Interconnection) model and how data travels between devices over a network.

---

## Topics Covered

- The OSI Model
- The Seven Layers of the OSI Model
- Encapsulation and Decapsulation
- IP Addresses
- MAC Addresses
- Routers and Switches
- Data Transmission

---

## Theory

The OSI model is a conceptual framework that standardizes how computers communicate over a network. It divides communication into seven layers, with each layer performing a specific function. Understanding these layers makes it easier to troubleshoot networks and understand how data moves from one device to another.

---

## The Seven Layers

### Layer 7 – Application

The layer where users interact with network services through applications such as Chrome, WhatsApp, Outlook, and ChatGPT.

### Layer 6 – Presentation

Responsible for formatting data, encryption, decryption, and compression so that both communicating systems understand the information.

### Layer 5 – Session

Establishes, manages, and terminates communication sessions between devices.

### Layer 4 – Transport

Breaks data into smaller segments and ensures reliable delivery. TCP and UDP operate at this layer.

### Layer 3 – Network

Uses IP addresses to determine the best route for data to travel between networks. Routers operate at this layer.

### Layer 2 – Data Link

Uses MAC addresses for communication between devices on the same local network. Switches primarily operate at this layer.

### Layer 1 – Physical

Converts data into electrical signals, radio waves, or light signals for transmission through physical media.

---

## Practical Exercise

I followed the journey of a request from my computer to a server using the OSI model.

Example:

Typing:

https://chatgpt.com

The communication follows this order:

1. Application Layer – The request is initiated through my web browser.
2. Presentation Layer – The data is formatted and encrypted.
3. Session Layer – A communication session is established with the server.
4. Transport Layer – The request is broken into segments and prepared for delivery.
5. Network Layer – IP addresses are used to determine the destination.
6. Data Link Layer – MAC addresses are used to communicate with the next device on the local network.
7. Physical Layer – The data is transmitted as electrical signals or radio waves.

The server then processes the request and sends the response back through the same layers in reverse order.

---

## Key Learnings

- The OSI model is a framework for understanding network communication.
- Every layer has a unique responsibility.
- Routers use IP addresses to move data between networks.
- Switches use MAC addresses to communicate within a local network.
- The Session Layer manages communication sessions.
- The Transport Layer is responsible for delivering data reliably.
- Data is encapsulated before transmission and decapsulated when received.

---

## Reflection

Today's lab helped me move beyond memorizing the seven OSI layers. Walking through how a simple request travels from my browser to a server made the model much easier to understand.

One concept I initially confused was the difference between the Session Layer and the Transport Layer. Through practice, I learned that the Session Layer manages the communication session, while the Transport Layer focuses on delivering data reliably.

This practical approach made the OSI model much more meaningful than simply memorizing definitions.

---

## Next Steps

- Learn the difference between TCP and UDP.
- Explore common networking protocols and the layers they operate on.
- Continue building practical networking skills through hands-on labs.