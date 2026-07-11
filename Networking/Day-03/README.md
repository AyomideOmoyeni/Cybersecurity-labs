# Day 3 - TCP vs UDP

## Objective
Understand the differences between TCP and UDP and when each protocol is used.

## Topics Covered
- TCP
- UDP
- Three-Way Handshake
- Reliability vs Speed
- Connection-Oriented vs Connectionless

## Key Learnings
- TCP guarantees reliable and ordered delivery of data.
- UDP prioritizes speed over reliability.
- TCP establishes a connection before transmitting data.
- UDP sends data without establishing a connection.
- Different applications choose TCP or UDP based on their requirements.

## Practical Exercises
- ping google.com
- nslookup google.com

## TCP vs UDP

| TCP | UDP |
|------|------|
| Reliable | Fast |
| Connection-oriented | Connectionless |
| Ordered delivery | No guaranteed order |
| Retransmits lost packets | Does not retransmit |
| Used for web browsing, email, SSH | Used for gaming, streaming, VoIP, DNS |

## Reflection

Today's lesson taught me that choosing between TCP and UDP depends on the application's needs. If reliability is critical, TCP is the better choice. If speed is more important than perfect delivery, UDP is the better option.