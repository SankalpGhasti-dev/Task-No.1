# 🛡 Task No.1 – Local Network Port Scanning (Elevate Labs)

## Overview  
This repository contains Task No.1 from Elevate Labs, focused on scanning a local network for open ports using Nmap.  
The objective was to understand open ports, analyze exposed services, and learn basic network reconnaissance techniques.

---

## 📁 Repository Structure

Task-No.1/
├─ Interview_Question      # Interview questions and answers  
├─ Screenshots            # Masked screenshots of scan results  
├─ scan_result.txt        # Sanitized Nmap scan output  
└─ README.md              # Documentation  

---

## 🎯 Objective

- Perform TCP SYN scan on local network  
- Identify open ports and services  
- Understand security risks  
- Document findings professionally  

---

## 🛠 Tools Used

- Kali Linux (VirtualBox)  
- Nmap  
- Wireshark (conceptual understanding)  

---

## 🌐 Network Information

Private Network Range: 10.X.X.0/24  

(Two hosts detected: Kali VM and Windows host)

Note: IP and MAC addresses have been masked for security.

---

## 🚀 Command Used

sudo nmap -sS 10.X.X.0/24 -oN scan_result.txt

---

## 📊 Findings

- Multiple hosts detected on the local network  
- Open ports such as SSH (22) and HTTP (80) observed depending on device  

---

## ⚠ Security Observations

- Open SSH ports can be targeted for brute-force attacks  
- Open HTTP ports expose web services  
- Multiple open ports increase attack surface  

---

## 📚 Interview Questions

This repository includes answers to:

- What is an open port?  
- How does Nmap perform TCP SYN scanning?  
- TCP vs UDP scanning  
- How to secure open ports  
- Firewall role in port management  
- Port scanning and attacker perspective  
- How Wireshark complements port scanning  

---

## 📸 Screenshots

The Screenshots folder contains:

- IP identification  
- Nmap scan execution  
- Scan results  

(All sensitive information masked.)

---

## 🧠 Learning Outcomes

- Learned TCP SYN scanning using Nmap  
- Understood open ports and associated risks  
- Practiced basic network reconnaissance  
- Learned security sanitization before publishing results  
- Improved GitHub documentation skills  

---

## 🔧 Technical Skills Demonstrated

- Network reconnaissance  
- Port scanning  
- Security analysis  
- Linux terminal usage  
- VirtualBox networking  
- GitHub documentation  

---

## ⚠ Disclaimer

All scans were performed only on my own local network for educational purposes.

---

## 📄 License

MIT License

---

### Author  
Sankalp Ghasti  

GitHub: https://github.com/SankalpGhasti-dev
