# Day 08 – Subnetting Practice

## Objective
To strengthen my understanding of subnetting by identifying network addresses, broadcast addresses, usable host ranges, and calculating the number of usable hosts using CIDR notation.

---

## Topics Covered

- CIDR Notation (/24 - /30)
- Block Size
- Network Address
- Broadcast Address
- First Usable Host
- Last Usable Host
- Usable Hosts Calculation

---

## Key Concepts Learned

### Block Size
The block size determines the size of each subnet and can be calculated using:

256 - Last Octet of the Subnet Mask

Examples:

- /25 = 128
- /26 = 64
- /27 = 32
- /28 = 16
- /29 = 8
- /30 = 4

---

### Network Address

The first IP address in a subnet.

---

### Broadcast Address

The last IP address in a subnet, used to communicate with all hosts within that subnet.

---

### First & Last Host

- First Host = Network Address + 1
- Last Host = Broadcast Address - 1

---

### Usable Hosts

Usable Hosts = 2^(32 - Prefix) - 2

Examples:

- /28 = 14 Hosts
- /29 = 6 Hosts
- /30 = 2 Hosts

---

## Practical Exercises

Solved multiple subnetting questions involving:

- /25
- /26
- /27
- /28
- /29
- /30

Calculated:

- Block Size
- Network Address
- Broadcast Address
- First Host
- Last Host
- Usable Hosts

---

## Key Takeaways

- Subnetting divides large networks into smaller and more manageable networks.
- Every subnet contains a Network Address and a Broadcast Address.
- The first and last addresses cannot be assigned to devices.
- CIDR notation determines the subnet size and the number of available hosts.
- Understanding subnetting is essential for network design, troubleshooting, and cybersecurity.

---

## Screenshots

Stored inside the screenshots folder.

---

## Skills Gained

- IPv4 Addressing
- CIDR Notation
- Subnetting
- Network Planning
- Logical Problem Solving