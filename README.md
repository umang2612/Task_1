# Task 1: Scan Your Local Network for Open Ports

## 🛡️ Objective

Learn how to discover open ports on devices within your local network to better understand your network's exposure and potential vulnerabilities.

---

## 🧰 Tools Required

- [Nmap](https://nmap.org/) (Primary tool)
- [Wireshark](https://www.wireshark.org/) (Optional for deeper packet analysis)

---

## 📝 Steps to Complete

1. **Install Nmap**  
   Download and install from the official [Nmap website](https://nmap.org/download.html).

2. **Find Your Local IP Range**  
   Use the command `ipconfig` (Windows) or `ifconfig/ip a` (Linux/macOS) to determine your local IP range (e.g., `192.168.1.0/24`).

3. **Perform a TCP SYN Scan**  
   Run the following Nmap command in your terminal:  
   ```bash
   nmap -sS 192.168.1.0/24
