# Network Layer (Layer 3) & IP Packets

The Network Layer is like the global postal system for data. It ensures packets reach the correct destination using IP addresses.

### Key Concept: The IP Header
Every packet has a header containing:
- **Source & Destination IP:** Where it's from and where it's going.
- **TTL (Time to Live):** A counter that prevents packets from looping forever.
- **Protocol:** Tells the device if it's using TCP or UDP.

### IPv4 vs IPv6
- **IPv4:** 32-bit (e.g., 192.168.1.1). Running out of addresses.
- **IPv6:** 128-bit (e.g., 2001:db8::). Provides almost infinite addresses and better security.

### Why Security Analysts care?
By analyzing IP headers, we can detect **IP Spoofing** (fake sender addresses) and track the origin of a network attack.
