# TCP vs UDP Comparison

| Feature           | TCP                           | UDP                          |
|------------------|-------------------------------|------------------------------|
| Protocol Type     | Connection-oriented            | Connectionless               |
| Reliability       | Reliable (acknowledgment, retransmission) | Unreliable (no guarantee)   |
| Speed             | Slower (more overhead)         | Faster (minimal overhead)    |
| Use Cases         | Web browsing, email, file transfer | Streaming, VoIP, gaming     |
| Flow Control      | Yes                            | No                           |
| Packet Ordering   | Guarantees order               | No ordering guarantee        |

## Common Ports
- **TCP**: 80 (HTTP), 443 (HTTPS), 22 (SSH), 25 (SMTP)
- **UDP**: 53 (DNS), 67/68 (DHCP), 161 (SNMP), 123 (NTP)
