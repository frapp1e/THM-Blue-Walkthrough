# TryHackMe - Blue Walkthrough

This project is a walkthrough of the **"Blue" room** on TryHackMe. It demonstrates how to exploit the **MS17-010 (EternalBlue)** vulnerability in a Windows machine using **Metasploit**, escalate privileges to **NT AUTHORITY\SYSTEM**, dump password hashes, and capture all flags.

---

## 🛠️ Tools Used

- Nmap
- Metasploit
- Mimikatz / Hashdump
- CrackStation (for password cracking)
- Windows CLI

---

## 📌 Steps Covered

### 1. Reconnaissance
- Scan target with Nmap
- Detect MS17-010 vulnerability

### 2. Gaining Access
- Launch Metasploit
- Use EternalBlue exploit
- Get reverse shell

### 3. Privilege Escalation
- Convert shell to Meterpreter
- Escalate to SYSTEM
- Migrate process

### 4. Password Cracking
- Dump hashes
- Crack with CrackStation
- Retrieve Jon’s password

### 5. Flag Hunting
- Locate and read 3 flags:
  - `flag1.txt` (root directory)
  - `flag2.txt` (System32\config)
  - `flag3.txt` (Jon's Documents)

---

## 📚 What I Learned

- How to identify and exploit MS17-010
- Privilege escalation techniques in Windows
- Working with Meterpreter sessions
- Password hash handling and cracking
- Navigating a compromised Windows system

---

## 🔗 References

- [TryHackMe - Blue Room](https://tryhackme.com/room/blue)
- [MS17-010 Advisory](https://technet.microsoft.com/en-us/library/security/ms17-010.aspx)
- [CrackStation](https://crackstation.net)

---

## 👤 Author

**[Fran Olivares]**  
Cybersecurity student | Ethical Hacker | ASIX  
[LinkedIn](https://linkedin.com/in/fran-olivares) 

---
