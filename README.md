# Task 1: Foundation & Environment Setup
**Cybersecurity & Ethical Hacking Internship – ApexPlanet Software Pvt. Ltd.**

## 1. Lab Environment Setup
- **Host OS:** Windows (WSL2 Environment)
- **Attacker Machine:** Kali Linux Rolling (`juveriya123@MSI`)
- **Tools Configured:** Nmap, OpenSSL, Netcat, Net-tools, Tcpdump

---

## 2. Cybersecurity Basics
- **CIA Triad:**
  - **Confidentiality:** Ensuring sensitive data is accessible only to authorized users (e.g., encryption, access controls).
  - **Integrity:** Maintaining accuracy and trustworthiness of data against unauthorized modification (e.g., hashing, digital signatures).
  - **Availability:** Ensuring systems and data remain accessible when needed (e.g., redundancy, DDoS protection).
- **Common Threats:** Phishing, Malware, DDoS, SQL Injection, Brute Force, Ransomware.
- **Attack Vectors:** Social Engineering, Wireless Attacks, Insider Threats.

---

## 3. Networking Basics
- **OSI Model (7 Layers):** Physical, Data Link, Network, Transport, Session, Presentation, Application.
- **TCP/IP Suite:** Network Interface, Internet (IP), Transport (TCP/UDP), Application (HTTP/HTTPS, DNS).
- **Core Concepts:**
  - **DNS:** Translates human-readable domain names into IP addresses.
  - **HTTP vs. HTTPS:** HTTPS encrypts web traffic using SSL/TLS certificates.
  - **IP Addressing, Subnetting & NAT:** Logical addressing (`127.0.0.1` loopback, private ranges) and Network Address Translation for routing private traffic to public networks.

---

## 4. Cryptography Basics
- **Symmetric Encryption (AES-256):** Uses the same secret key for both encryption and decryption. Fast and ideal for bulk data.
- **Asymmetric Encryption (RSA/ECC):** Uses a public key to encrypt and a private key to decrypt.
- **Hashing (MD5, SHA-256):** One-way cryptographic function used to verify file integrity.
- **SSL/TLS & Digital Certificates:** Secures data in transit and verifies server identity.

---

## 5. Linux Command Cheat-Sheet

| Category | Command | Description |
| :--- | :--- | :--- |
| **Navigation** | `pwd` | Print current working directory |
| | `ls -la` | List all files and hidden directories with permissions |
| | `cd <dir>` | Change directory |
| **Permissions** | `chmod 755 <file>` | Change file read/write/execute permissions |
| | `chown user:group <file>` | Change file owner and group |
| **Packages** | `sudo apt update` | Refresh package repository index |
| | `sudo apt install <pkg>` | Install a software package |
| | `dpkg -l` | List all installed Debian packages |
| **Networking** | `ifconfig` / `ip a` | Display network interfaces and IP addresses |
| | `ping -c 4 <host>` | Test network reachability via ICMP |
| | `netstat -tuln` | Show active listening ports and connections |
| | `traceroute <host>` | Trace the network path packets take to a destination |
| **Security & Crypto** | `nmap <target>` | Scan target host for open TCP ports |
| | `sudo tcpdump -i lo icmp` | Capture live ICMP network packets |
| | `openssl enc -aes-256-cbc` | Encrypt/decrypt files using AES-256 |
