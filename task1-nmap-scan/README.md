# 🔍 Cyber Security Internship – Task 1: Network Port Scanning using Nmap

## 🧠 Objective:
To perform network reconnaissance by scanning the local network using **Nmap** to identify active hosts and their **open TCP ports**, analyze exposed services, and understand potential security implications.

---

## 🛠️ Tools Used:
- **Nmap** – For scanning the network and identifying open ports.
- **Operating System** – Kali Linux
- **Optional Tool** – Wireshark (for packet analysis, not used in this task)

---

## 🖥️ Commands Executed:

```bash
ifconfig
nmap -sS 10.17.238.0/24
nmap -sS 10.17.238.0/24 -oN scan_results.txt
