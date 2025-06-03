# DevTown_Hack_Like-_Pro_Cyber-Security-project-1
# 💻⚔️ Hack Like a Pro: Mastering the Ultimate CTF Challenge

## 🛡️ Cybersecurity Lab Project – Penetration Testing with Nmap & Metasploit  
**👨‍🏫 Assigned by:** DevTown  

---

## 🎯 Objective

This project provides practical, hands-on experience in ethical hacking by covering the full penetration testing lifecycle:

- 🔍 Identifying the target system through active reconnaissance  
- 📡 Scanning open ports and detecting active services using **Nmap**  
- 🚨 Identifying vulnerabilities in exposed services  
- 💥 Exploiting discovered vulnerabilities using **Metasploit (msfconsole)**  
- 🔐 Gaining unauthorized shell access to the target system  
- 📝 Documenting all steps and findings in a detailed professional report  

---

## 🧰 Tools Used

Here are the tools used during this lab project:

| 🧪 Tool               | 🔎 Purpose                                                   |
|-----------------------|-------------------------------------------------------------|
| `Netdiscover`         | Identify IP address of the target on the local network      |
| `Nmap`                | Perform port scanning and service enumeration               |
| `Metasploit Framework`| Exploit known vulnerabilities and gain shell access         |
| `Google Dorking`      | Discover public vulnerabilities for specific software       |
| `Linux Commands`      | Navigate file system and perform post-exploitation tasks    |
| `John the Ripper`     | Crack password hashes (discussed as theoretical step)       |
| `Hashcat`             | Alternative password cracker (discussed as theoretical step)|

---

## 🔬 Proof of Concept (PoC)

📁 A comprehensive **Proof of Concept (PoC)** has been uploaded in this repository, illustrating every phase of the engagement.

---

## 📌 Execution Summary

### 1. 🔎 Target Discovery

- Utilized `netdiscover` to identify the IP address of the target machine on the local network.

### 2. 🛠️ Port & Service Enumeration (Nmap)

Performed a detailed scan using **Nmap** to extract the following:

- ✅ Open Ports  
- ⚙️ Running Services  
- 🖥️ Operating System Fingerprint  
- 🔑 Encryption keys and service banners  

### 3. 🌐 Services Identified

The target machine was found running the following services:

- **FTP** – ProFTPD 1.3.3c  
- **HTTP** – Web server (port 80)  
- **SSH** – Secure Shell (port 22)  

### 4. 🚩 Vulnerability Exploitation

- Found **ProFTPD 1.3.3c** to be vulnerable using public exploit databases and search techniques.  
- Leveraged the **Metasploit Framework** to exploit the FTP vulnerability.  
- Gained **shell access** successfully.

### 5. 🔍 Post-Exploitation Activities

- Accessed and examined `/etc/passwd` for user account details.  
- Theoretically explored **password cracking** methods using:
  - 🧠 **John the Ripper**
  - ⚡ **Hashcat**

---

## 🧠 Conclusion

This lab provided a structured, real-world simulation of a typical penetration test, reinforcing critical cybersecurity skills:

- 🎯 Reconnaissance and Enumeration  
- 🛠️ Vulnerability Analysis  
- 💣 Exploitation Using Metasploit  
- 🔍 Post-Exploitation Techniques  

It offered valuable exposure to **Nmap**, **Metasploit**, and other tools widely used in ethical hacking and Capture the Flag (CTF) environments.

---

## 📁 Repository Structure


