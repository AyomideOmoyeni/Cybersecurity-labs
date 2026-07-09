# 🌐 Networking Labs | Day 1

## 🎯 Objective

Understand the fundamentals of networking and become familiar with basic Windows networking commands.

---

## 🛠️ Tools Used

- Windows Command Prompt
- ipconfig
- ping
- tracert
- getmac

---

## 📖 Concepts Covered

- LAN vs WAN
- IP Addressing
- DNS
- Routers
- Default Gateway
- Network Adapters

---

## 💻 Practical Exercises

### 1. ipconfig

**Purpose**

Displays the current network configuration.

**Observation**

- Active adapter: Wi-Fi
- IPv4 Address: 192.168.100.3
- Default Gateway: 192.168.100.1

---

### 2. ping google.com

**Purpose**

Tests connectivity to Google's server.

**Observation**

- 0% packet loss
- Average response time: 12 ms

---

### 3. ping ecampus.fuoye.edu.ng

**Observation**

DNS resolved successfully, but the server did not respond to ICMP requests.

**Lesson**

A failed ping does not always mean a server is offline.

---

### 4. tracert ecampus.fuoye.edu.ng

**Observation**

Successfully traced the route through multiple hops before reaching the destination.

---

## 🎓 Key Takeaways

- DNS translates domain names into IP addresses.
- Routers forward traffic between networks.
- Traceroute reveals the path packets take.
- Troubleshooting requires evidence, not assumptions.

---

## 🚀 Next Lab

OSI Model
