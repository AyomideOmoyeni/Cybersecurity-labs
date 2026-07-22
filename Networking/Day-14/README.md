# Day 14 – VPN

## Objective

To understand how Virtual Private Networks (VPNs) provide secure communication over untrusted networks and how different VPN configurations are used for remote access and network-to-network connections.

---

## Topics Covered

- VPN
- VPN Tunneling
- VPN Encryption
- Full Tunnel
- Split Tunnel
- IPSec VPN
- Site-to-Site VPN
- SSL/TLS VPN
- VPN vs Proxy
- Zero Trust

---

## Key Concepts Learned

### What is a VPN?

A VPN (Virtual Private Network) creates a secure connection between a device or network and another network over an untrusted network such as the internet.

VPNs are commonly used to:

- Secure traffic over untrusted networks
- Provide remote access to company resources
- Connect remote workers to organizational networks
- Connect separate networks securely

---

### VPN Tunneling

VPN tunneling creates a logical pathway through which VPN traffic travels between the user and the VPN server or between two networks.

The traffic is protected as it travels through the tunnel.

---

### VPN Encryption

VPNs can use encryption to protect data while it is traveling across a network.

Encryption converts readable data (plaintext) into ciphertext, helping prevent unauthorized parties from easily reading intercepted traffic.

---

### Full Tunnel

With a full-tunnel VPN configuration, most or all of a device's network traffic is routed through the VPN.

Example:

    Computer → VPN → Internet

This can provide centralized security controls but may increase bandwidth usage and latency.

---

### Split Tunnel

With split tunneling, only selected traffic is routed through the VPN.

For example:

    Company Traffic → VPN → Company Network

    Personal Internet Traffic → Direct Internet

Split tunneling can reduce VPN bandwidth usage but may allow some traffic to bypass organizational security controls.

---

### IPSec VPN

IPSec (Internet Protocol Security) is a suite of protocols used to secure IP communications.

It can provide:

- Encryption
- Authentication
- Data Integrity

IPSec is commonly used in site-to-site VPN connections.

---

### Site-to-Site VPN

A site-to-site VPN securely connects two or more networks through VPN gateways.

Example:

    Network A → VPN Gateway
                    │
              IPSec Tunnel
                    │
               VPN Gateway
                    ↓
                Network B

This allows devices in separate locations to communicate securely over the internet.

---

### SSL/TLS VPN

SSL/TLS VPNs use TLS to secure VPN connections, commonly for remote access.

This allows remote users to securely access organizational resources.

Although the term "SSL VPN" is still commonly used, modern implementations generally use TLS because SSL is obsolete.

---

### VPN vs Proxy

A proxy typically acts as an intermediary for specific application traffic.

A VPN generally operates at a broader network level and can route traffic from multiple applications through a secure VPN connection.

---

### Zero Trust

Zero Trust is a security model based on the principle:

> "Never trust, always verify."

Being connected to a company VPN does not automatically give a user access to every internal resource.

Access should be:

- Authenticated
- Authorized
- Verified
- Limited to the resources required

This follows the principle of least privilege.

---

## Practical Exercise

I inspected the VPN settings available on Windows and reviewed the available VPN configuration options.

I examined the VPN types available on the system, including:

- Automatic
- IKEv2
- SSTP
- L2TP/IPsec
- PPTP

I also connected these configuration options to the VPN concepts learned during the theory session, including IPSec, TLS-based VPNs, and remote access.

No VPN connection was created or established during the exercise.

---

## Key Takeaways

- VPNs create secure connections over untrusted networks.
- VPN tunneling provides a logical pathway for protected traffic.
- Full tunneling routes most or all traffic through the VPN.
- Split tunneling routes only selected traffic through the VPN.
- IPSec is commonly used to secure site-to-site VPN connections.
- SSL/TLS VPNs use TLS to secure remote access.
- Site-to-site VPNs connect entire networks.
- A VPN does not automatically make a user trusted.
- Zero Trust requires continuous authentication and authorization.
- Access should be limited according to the user's permissions and requirements.

---

## Skills Gained

- VPN Fundamentals
- VPN Tunneling
- Full vs Split Tunneling
- IPSec VPN Concepts
- Site-to-Site VPN Concepts
- SSL/TLS VPN Concepts
- VPN Configuration Awareness
- Zero Trust Security Principles