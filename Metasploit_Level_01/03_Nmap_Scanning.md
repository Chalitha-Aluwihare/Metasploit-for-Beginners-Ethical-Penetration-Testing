# Nmap Scanning - Metasploit Level 01

## Objective
To scan the target machine (Metasploitable 2) using Nmap from Kali Linux.

Target IP:
192.168.50.2

---

## 1️⃣ Basic Scan

Command:
nmap 192.168.50.2

Purpose:
This command scans open ports on the target machine.

Result:
Multiple ports were found open including:
- 21 (FTP)
- 22 (SSH)
- 23 (Telnet)
- 80 (HTTP)

(Screenshot Here)

---

## 2️⃣ Default Script Scan

Command:
nmap -sC 192.168.50.2

Purpose:
Runs default Nmap scripts to detect vulnerabilities and services.

Result:
Detected service information and possible vulnerabilities.

(Screenshot Here)

---

## 3️⃣ Service Version Detection

Command:
nmap -sC -sV 192.168.50.2

Purpose:
Detect service versions running on open ports.

Result:
Showed versions like:
- vsftpd 2.3.4
- Apache 2.2.8
- OpenSSH

This helps identify exploitable services.

(Screenshot Here)

---

## Conclusion
Nmap scanning successfully identified multiple vulnerable services on the target machine.
