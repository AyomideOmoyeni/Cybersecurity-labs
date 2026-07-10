# Networking - Day 1

## Objective

Understand the fundamentals of computer networking and become familiar with basic networking commands available on Windows.

---

## Topics Covered

- Computer Networks
- LAN vs WAN
- IPv4 Addresses
- DNS (Domain Name System)
- Default Gateway
- Routers
- HTTP vs HTTPS

---

## Practical Exercises

### 1. `ipconfig`

Used `ipconfig` to inspect my network configuration.

Key information identified:
- My IPv4 address
- Subnet mask
- Default gateway
- Active network adapter

---

### 2. `ping google.com`

Verified internet connectivity and observed:
- DNS resolving a domain name into an IP address
- Successful replies from Google's server
- Round-trip response time
- TTL values

---

### 3. `ping ecampus.fuoye.edu.ng`

The request timed out.

Instead of assuming the server was offline, I learned that many servers block ICMP (ping) requests for security reasons.

---

### 4. `tracert ecampus.fuoye.edu.ng`

Used `tracert` to view the path packets took to reach the destination.

Observed:
- My default gateway
- Multiple network hops
- One router that didn't respond to ICMP
- Successful arrival at the destination server

---

### 5. `getmac`

Retrieved the MAC address of my network adapter and learned the difference between MAC addresses and IP addresses.

---

## Key Learnings

- Every device on a network has an IP address.
- DNS translates domain names into IP addresses.
- Routers forward traffic between networks.
- A failed ping does not necessarily mean a website or server is down.
- Traceroute helps identify the route packets take across a network.
- MAC addresses identify devices on a local network, while IP addresses identify devices across networks.

---

## Reflection

Today's biggest lesson was learning not to jump to conclusions when troubleshooting a network.

Initially, I assumed a failed ping meant a server was unavailable. After using `tracert` and discussing the results, I understood that servers can intentionally ignore ICMP requests while remaining fully operational.

This was my first hands-on networking lab, and it gave me a much better understanding of how devices communicate across networks.