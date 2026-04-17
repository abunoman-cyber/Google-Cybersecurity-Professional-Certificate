# Understanding Network Protocols

Network protocols are the rules that devices follow to communicate. Without them, the internet would be chaos. I've categorized them into three main types based on what they do.

---

### 1. Communication Protocols
* **TCP (Transmission Control Protocol):** Reliability is key here. It uses a **Three-way Handshake** (SYN, SYN/ACK, ACK) before sending data.
* **UDP (User Datagram Protocol):** Speed over reliability. No handshake. Used for DNS and video streaming.
* **HTTP (Port 80):** Standard web protocol, but insecure.
* **DNS (Port 53):** Translates domain names (like .com) into IP addresses.

### 2. Management Protocols
* **ICMP:** Used for error reporting and diagnostics. This is what powers the `ping` command.
* **SNMP:** Helps network admins monitor device performance and manage configurations.

### 3. Security Protocols
* **HTTPS (Port 443):** Secure web browsing using SSL/TLS encryption.
* **SFTP (Port 22):** Securely transferring files using SSH. Much better than the old, insecure FTP.

---

### Key Security Takeaway:
Protocols like HTTP and DNS can be vulnerable. As a security analyst, I need to know which ports are open and ensure that encrypted versions (like HTTPS/SFTP) are being used to protect data in transit.

*Status: Module 2 Notes Started | April 17, 2026*
