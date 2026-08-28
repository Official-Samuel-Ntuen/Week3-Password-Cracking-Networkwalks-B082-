# Week 3 - Password Cracking with JTR & Networkwalks Tools
## Password Cracking with JTR and Networkwalks Tools



![Skill](https://img.shields.io/badge/Skill-Cybersecurity-red)
![Kali](https://img.shields.io/badge/Kali_Linux-v2026.1-purple)
![Skill](https://img.shields.io/badge/Penetration_Testing-Skill-red)
![GitHub](https://img.shields.io/badge/GitHub-Official--Samuel--Ntuen-black?logo=github)
![NetworkWalks](https://img.shields.io/badge/NetworkWalks-orange)
![Ethical](https://img.shields.io/badge/Ethical_Hacking-darkgreen)
![Waqas](https://img.shields.io/badge/-Samuel_M._Ntuen-red)


---

## 🎯 Objectives
- Understand the basics of password cracking
- Extract password hashes from a protected PDF
- Use John the Ripper to recover a password
- Use Networkwalks tools for password recovery
- Understand the importance of strong passwords

---

## 🛠️ Tools Used
- John the Ripper (JTR)
- PDF Hash Extractor (onlinehashcrack.com)
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Kali Linux

---

## 📋 Module 1 — JTR (John the Ripper)

### Steps:
1. Obtained the authorized password-protected PDF
2. Extracted the PDF hash using Online Hash Crack PDF extractor
3. Saved the hash as `hash1.txt`
4. Ran John the Ripper to crack the hash
5. Retrieved the cracked password
6. Opened the PDF using the recovered password

### Commands Used:
```bash
john hash1.txt
john --show hash1.txt
```

### Flag Captured:
**nw{cybersecurity_flag_captured_2608}**

---

## 📋 Module 2 — Networkwalks Tools

### Steps:
1. Uploaded the authorized PDF to Networkwalks Hash Calculator
2. Copied the generated `$pdf$` hash
3. Pasted hash into Networkwalks Password Cracker
4. Recovered the password
5. Opened the PDF to verify

---

## 📚 What I Learned

### Password Cracking Concepts:
- Passwords are not stored as plain text — they are stored as **hashes**
- A hash is a one-way function that converts text into a fixed string
- Password cracking works by comparing hashes, not actual passwords

### John the Ripper:
- JTR is a powerful open-source password cracking tool
- It supports many hash types including PDF, ZIP, and Office files
- The `pdf2john` tool extracts hashes from PDF files
- Dictionary and brute-force attacks can be used to crack hashes

### Hash Extraction:
- Every password-protected PDF contains a hash of the password
- Tools like pdf2john and online hash extractors can retrieve this hash
- The hash starts with `$pdf$` for PDF files

### Networkwalks Tools:
- Browser-based tools can also extract and crack PDF hashes
- The Networkwalks Hash Calculator generates the hash from the PDF
- The Networkwalks Password Cracker attempts to recover the password

### Security Awareness:
- Weak passwords can be cracked very quickly
- Strong passwords should be long, complex, and unique
- Password cracking should only be done on authorized systems
- Understanding how attacks work helps build better defenses

---
## ⚠️ Disclaimer
This project is for educational purposes only. All tools were used on authorized files in a controlled lab environment.

---

## 🔗 References
- John the Ripper: https://www.openwall.com/john/
- Networkwalks: https://networkwalks.com/
- Networkwalks Hash Calculator: https://networkwalks.com/hash-calculator/
- Networkwalks Password Cracker: https://networkwalks.com/password-cracker/



👤 **Author**

**Samuel M. Ntuen**

Cybersecurity Intern — Batch: **B082-NetworkWalks**

LinkedIn: *https://www.linkedin.com/in/samuelntuen/*


📌 **Project Information**

**Program Name**: Cybersecurity Internship at NetworkWalks Academy | **Week**: 03 | **Repository**: GitHub
