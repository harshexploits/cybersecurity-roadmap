<div align="center">

# 🛡️ Cybersecurity Roadmap

**A complete, structured path from IT fundamentals to Cyber Security Expert — based on [roadmap.sh/cyber-security](https://roadmap.sh/cyber-security)**

[![Based on](https://img.shields.io/badge/based%20on-roadmap.sh-8B5CF6?style=for-the-badge)](https://roadmap.sh/cyber-security)
[![Track](https://img.shields.io/badge/track-Offensive%20%2B%20Defensive-10B981?style=for-the-badge)](#)
[![Maintained by](https://img.shields.io/badge/made%20by-harshexploits-FF0000?style=for-the-badge)](https://github.com/harshexploits)

</div>

---

## 📌 How to use this roadmap

- Work through the **6 phases in order** — each phase builds on the previous one.
- ✅ = completed · 🔄 = in progress · ⬜ = not started
- Every phase ends with **hands-on practice** — don't skip it. Security is a practical skill.
- The official visual roadmap lives at **[roadmap.sh/cyber-security](https://roadmap.sh/cyber-security)** — this repo is the structured, checklist-style companion.

---

## Phase 1 — Fundamental IT Skills ⬜

The layer everything else stands on. If you can't troubleshoot a machine or explain what a DHCP server does, stop here first.

### 💻 Computer Fundamentals
- ⬜ Computer hardware components (CPU, RAM, storage, PSU, motherboard)
- ⬜ Connection types and their function — NFC, WiFi, Bluetooth, Infrared
- ⬜ OS-independent troubleshooting
- ⬜ Popular productivity suites — MS Office, Google Suite, iCloud

### 🖥️ Operating Systems (Windows / Linux / macOS)
Learn the following **for each OS**:
- ⬜ Installation and configuration · different versions and their differences
- ⬜ Navigating using GUI and CLI
- ⬜ File permissions · installing software and applications
- ⬜ Performing CRUD operations on files · troubleshooting
- ⬜ Common commands

### 🌐 Computer Networking
- ⬜ IP terminology — localhost, loopback, CIDR, subnet mask, default gateway
- ⬜ Basics of subnetting · public vs private IP addresses
- ⬜ Understand the terminology: **VLAN, DMZ, ARP, VM, DHCP, DNS, NAT, IP, Router, Switch, VPN**
- ⬜ Network types — MAN, LAN, WAN, WLAN
- ⬜ Network topologies — Star, Ring, Mesh, Bus
- ⬜ Services and their functions — DHCP, DNS, NTP, IPAM

### 🔌 Network Protocols
- ⬜ SSH, RDP, FTP, SFTP, HTTP/HTTPS, SSL/TLS
- ⬜ The OSI model · common protocols and their uses
- ⬜ Common ports and their uses · SSL and TLS basics
- ⬜ Basics of NAS and SAN

### 🧰 Core Networking Tools
- ⬜ `ipconfig` · `ping` · `dig` · `netstat` · `route` · `nmap` · `tcpdump` · `arp` · `tracert` · `nslookup` · `iptables`

---

## Phase 2 — Security Fundamentals ⬜

### 🎯 Core Concepts
- ⬜ CIA Triad (Confidentiality, Integrity, Availability) · understand handshakes
- ⬜ Authentication vs Authorization · MFA & 2FA
- ⬜ Privilege escalation
- ⬜ Defense in depth · Zero Trust core concepts
- ⬜ The definition of risk · backups and resiliency
- ⬜ Cyber Kill Chain · honeypots
- ⬜ Basics of IDS and IPS · concept of isolation
- ⬜ Blue / Red / Purple teams
- ⬜ False Positive / False Negative / True Positive / True Negative
- ⬜ Basics of Threat Intel & OSINT

### 🔐 Cryptography Basics
- ⬜ Hashing · salting · key exchange
- ⬜ Private vs public keys · PKI
- ⬜ Obfuscation

### 🦠 Malware & Attacks
- ⬜ How malware works and its types
- ⬜ Web-based attacks and the OWASP Top 10
- ⬜ Common attacks — DoS vs DDoS, MITM, CSRF, Spoofing, SQL Injection, XSS
- ⬜ Brute force vs password spraying · Pass the Hash
- ⬜ Zero-days — known vs unknown · APTs
- ⬜ Directory traversal · buffer overflow · memory leaks

### 🎭 Social Engineering
- ⬜ Phishing · Smishing · Vishing (Whishing) · Whaling
- ⬜ Spam vs Spim · shoulder surfing · tailgating · dumpster diving
- ⬜ Reconnaissance and impersonation · watering hole attack · drive-by attack · typo squatting

### 📡 Wireless Security
- ⬜ WEP vs WPA vs WPA2 vs WPA3 · WPS · EAP vs PEAP
- ⬜ Evil twin · deauth attack · rogue access point · VLAN hopping · DNS poisoning · replay attack

### 🧪 Hands-on Practice
- ⬜ Set up a home lab (VirtualBox / VMware / Proxmox — hypervisor, HostOS vs GuestOS)
- ⬜ Install Kali Linux or ParrotOS
- ⬜ Complete your first 10 TryHackMe rooms

---

## Phase 3 — Defensive Security & Operations ⬜

### 🪵 Logs & Monitoring
- ⬜ Event logs, syslogs, netflow, packet captures, firewall logs — find and read them
- ⬜ SIEM and SOAR — what they are and how they fit together

### 🔥 Hardening & Endpoint Security
- ⬜ Operating system hardening
- ⬜ Hardening concepts — MAC-based, NAC-based, port blocking, group policy, patching, sinkholes, ACLs, jump server
- ⬜ Endpoint security — Antivirus, Antimalware, EDR, DLP
- ⬜ Firewalls — NGFW, HIPS, NIDS, NIPS, host-based firewalls, sandboxing

### 🚨 Incident Response
- ⬜ The IR process: **Preparation → Identification → Containment → Eradication → Recovery → Lessons Learned**
- ⬜ IR & discovery tools — `dig`, `nmap`, `ping`, `arp`, `cat`, `dd`, `tracert`, `winhex`, `autopsy`, `ipconfig`, `memdump`, FTK Imager
- ⬜ Concept of runbooks · basics of forensics

### 🕵️ Threat Intelligence
- ⬜ Frameworks — **MITRE ATT&CK, Cyber Kill Chain, Diamond Model**
- ⬜ Common standards — ISO, NIST, RMF, CIS, CSF
- ⬜ Threat-intel tools — VirusTotal, urlscan, any.run, Joe Sandbox, urlvoid, WHOIS
- ⬜ Basics of vulnerability management · threat hunting

### 🏢 Governance
- ⬜ Roles of compliance and auditors · stakeholders (HR, Legal, Management)
- ⬜ Penetration testing rules of engagement
- ⬜ Perimeter vs DMZ vs segmentation

---

## Phase 4 — Offensive Security ⬜

- ⬜ Common hacking tools (nmap, Burp Suite, Metasploit ecosystem — understand, don't just run)
- ⬜ Common exploit frameworks
- ⬜ Basics of reverse engineering
- ⬜ LOLBAS · GTFOBINS · WADCOMS — living-off-the-land techniques
- ⬜ Web application attack methodology (deep OWASP Top 10)
- ⬜ Build a structured pentest report — this separates hobbyists from professionals

### 🚩 Hands-on Practice
- ⬜ HackTheBox — complete 20+ machines (start with easy tier)
- ⬜ TryHackMe — Offensive path
- ⬜ VulnHub — 5 vulnerable VMs end-to-end
- ⬜ picoCTF / SANS Holiday Hack Challenge
- ⬜ pwncollege
- ⬜ **Real bug bounty** (HackerOne / Bugcrowd / YesWeHack) — always within program scope

---

## Phase 5 — Cloud Security ⬜

- ⬜ Concept of security in the cloud · cloud vs on-premises differences
- ⬜ Cloud services — SaaS, PaaS, IaaS
- ⬜ Cloud models — private, public, hybrid
- ⬜ Common environments — **AWS, GCP, Azure**
- ⬜ Infrastructure as Code · serverless
- ⬜ Basics and general flow of deploying in the cloud
- ⬜ Common cloud storage — S3, Dropbox, iCloud, Box, OneDrive, Google Drive
- ⬜ Hands-on: deploy a small secure architecture on AWS free tier

---

## Phase 6 — Programming & Keep Leveling Up ⬜

### 💻 Languages
- ⬜ **Python** (automate everything you do more than twice)
- ⬜ **Bash** (non-negotiable for Linux work)
- ⬜ Go (modern security-tooling language)
- ⬜ JavaScript (web-app security)
- ⬜ C++ (understand memory corruption)
- ⬜ PowerShell (Windows environments)

### 📜 Certifications

| Level | Certs |
|---|---|
| **Beginner** | CompTIA A+, Network+, Security+, Linux+, CCNA |
| **Advanced** | CEH, CISA, CISM, GSEC, GPEN, GWAPT, GIAC, OSCP, CREST, CISSP |

> 💡 Suggested order: **Security+ → eJPT/CEH → OSCP**. Don't collect certs — collect proof of skill.

### 🔁 Continuous Learning
- ⬜ Contribute to open-source security tools
- ⬜ Write write-ups for every CTF machine you solve
- ⬜ Follow the community — this field changes weekly
- ⬜ Teach what you learn (blog, notes, talks)

---

<div align="center">

**Credit:** Topic structure based on the official [roadmap.sh Cyber Security roadmap](https://roadmap.sh/cyber-security) by [roadmap.sh](https://roadmap.sh) · this repo adapts it into a personal progress tracker.

**Maintained by [harshexploits](https://github.com/harshexploits)**

</div>
