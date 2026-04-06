# My Notes on the OSI Model

The OSI (Open Systems Interconnection) model is the foundation of networking. Understanding these 7 layers is essential for identifying where a security breach or network issue is occurring.

---

### The 7 Layers and Security Focus

1. **Physical Layer (Layer 1):** Deals with hardware, cables, and bits.
   * *Security:* Preventing physical tampering or wiretapping.
2. **Data Link Layer (Layer 2):** Uses MAC addresses for local communication.
   * *Security:* Guarding against ARP poisoning and MAC spoofing.
3. **Network Layer (Layer 3):** Handles routing and IP addresses.
   * *Security:* Monitoring for IP spoofing and ICMP attacks.
4. **Transport Layer (Layer 4):** Ensures data delivery via TCP or UDP.
   * *Security:* Identifying port scans and SYN floods.
5. **Session Layer (Layer 6):** Manages the connection between devices.
   * *Security:* Preventing session hijacking.
6. **Presentation Layer (Layer 6):** Formats data and handles encryption (SSL/TLS).
   * *Security:* Checking for SSL/TLS vulnerabilities.
7. **Application Layer (Layer 7):** What the user sees (HTTP, DNS).
   * *Security:* Defending against SQL injection and Phishing.

---

### Personal Takeaways:
To remember the layers easily from bottom to top, I use the phrase: **"Please Do Not Throw Sausage Pizza Away"**. 

In Cybersecurity, most of my focus will be on Layers 3, 4, and 7 because that's where most remote attacks happen. IP addresses are the main identifiers at Layer 3, while Layer 4 is all about ensuring the data gets there in one piece.

---
*Last Updated: April 6, 2026*
