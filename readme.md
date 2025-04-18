# 🔒 Network Scanning with Nmap (Windows)

## 📌 Project Overview
This project demonstrates how to perform network scanning on your local machine and router using **Nmap on Windows**. It includes installation steps, command usage, and analysis of scan results.

## 🛠️ Tools & Setup
- **OS**: Windows 10/11
- **Tool**: [Nmap](https://nmap.org/)
- **Targets**:
  - Localhost: `127.0.0.1`
  - Router IP: `192.168.X.X`

## 🧪 Scan Commands Used
```bash
nmap -sS -sV 127.0.0.1 -oN localhost_scan.txt
nmap -sS -sV 192.168.X.X -oN router_scan.txt
