# DevTown_Hack_Like-_Pro_Cyber-Security-project-1
# 💻⚔️ Hack Like a Pro: Mastering the Ultimate CTF Challenge

## 🛡️ Cybersecurity Lab Project – Penetration Testing with Nmap & Metasploit  
**👨‍🏫 Assigned by:** DevTown  

---

## 🎯 Objective

This project provides practical experience in penetration testing by covering:

- 🔍 Identifying the target system using reconnaissance techniques  
- 📡 Scanning for open ports and active services using **Nmap**  
- 🚨 Detecting potential vulnerabilities on the target machine  
- 💥 Exploiting those vulnerabilities using **Metasploit (msfconsole)**  
- 🔐 Gaining shell access to the target system  
- 📝 Documenting all findings in a professional penetration testing report  

---

## 🔬 Proof of Concept (PoC)

A complete Proof of Concept (PoC) is available in this repository.

---

## 📌 Execution Summary

### 1. 🔎 Target Discovery

- Identified the target IP using `netdiscover`.

### 2. 🛠️ Port & Service Enumeration (Nmap)

Performed a detailed Nmap scan to gather:

- ✅ Open Ports  
- ⚙️ Running Services  
- 🖥️ Operating System Details  
- 🔑 Service Banners and Encryption Keys  

### 3. 🌐 Services Identified

The Nmap scan revealed the following services:

- **FTP** – ProFTPD 1.3.3c  
- **HTTP** – Web server  
- **SSH** – Secure shell access  

### 4. 🚩 Vulnerability Exploitation

- The FTP service (ProFTPD 1.3.3c) was found to be vulnerable.  
- Used **Metasploit Framework** to exploit the vulnerability.  
- Successfully gained shell access to the target system.

### 5. 🔍 Post-Exploitation Activities

- Accessed and examined the `/etc/passwd` file to enumerate user accounts.  
- Explored password cracking strategies using **John the Ripper** and **Hashcat** for further post-exploitation.

---

## 🧠 Conclusion

This lab simulated a real-world penetration testing scenario, strengthening essential skills in:

- Information Gathering  
- Vulnerability Scanning  
- Exploitation Techniques  
- Post-Exploitation Strategies  

It offered a comprehensive introduction to ethical hacking using widely-used tools like **Nmap** and **Metasploit**.

---
