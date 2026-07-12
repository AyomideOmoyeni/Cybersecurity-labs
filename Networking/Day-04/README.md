# Day 4 - Ports and Common Network Services

## Objective

Understand the concept of network ports, their role in network communication, and identify common ports used by popular services. Learn how to inspect active network connections and running processes using Windows networking commands.

---

## Topics Covered

- Network Ports
- Port Ranges
- Common Network Services
- Open vs Closed Ports
- TCP vs UDP Ports
- Process IDs (PID)
- Active Network Connections

---

## What is a Port?

A network port is a logical communication endpoint that allows multiple applications and services to communicate over the same network connection.

Think of it like this:

- **IP Address** → The address of an apartment building.
- **Port** → The apartment number.

The IP address identifies the computer, while the port identifies the specific application or service running on that computer.

---

## Port Ranges

| Port Range | Category |
|------------|----------|
| 0 – 1023 | Well-known Ports |
| 1024 – 49151 | Registered Ports |
| 49152 – 65535 | Dynamic (Ephemeral) Ports |

---

## Common Ports

| Port | Service | Description |
|------|---------|-------------|
| 20 | FTP | File Transfer (Data) |
| 21 | FTP | File Transfer (Control) |
| 22 | SSH | Secure Remote Login |
| 23 | Telnet | Remote Login (Insecure) |
| 25 | SMTP | Sending Email |
| 53 | DNS | Domain Name Resolution |
| 80 | HTTP | Web Browsing |
| 443 | HTTPS | Secure Web Browsing |
| 3389 | RDP | Remote Desktop |

---

## Practical Exercises

### Display Active Network Connections

```cmd
netstat -an
```

Displays all active network connections and listening ports.

---

### Display Network Connections with Process IDs

```cmd
netstat -ano
```

Displays all active network connections together with the Process ID (PID) of the application using each connection.

---

### List Running Processes

```cmd
tasklist
```

Lists all currently running processes on the system.

---

## Key Learnings

- Learned that an IP address identifies a device, while a port identifies a specific application or service.
- Understood the different categories of network ports.
- Learned the purpose of common networking ports such as 22, 53, 80, 443, and 3389.
- Understood the difference between open and closed ports.
- Learned how to inspect active network connections using `netstat`.
- Learned that Process IDs (PIDs) help identify which application owns a network connection.

---

## Reflection

Today's lesson helped me understand how multiple services communicate on the same computer using different ports. I also learned how cybersecurity professionals use tools like `netstat` and `tasklist` to investigate active network connections and identify the applications responsible for them. This practical exercise strengthened my understanding of how networking concepts are applied in system administration and cybersecurity.

---

# Screenshots

## Active Network Connections

![netstat -an](screenshots/netstat-an.png)

---

## Network Connections with Process IDs

![netstat -ano](screenshots/netstat-ano.png)

---

## Running Processes

![tasklist](screenshots/tasklist.png)