<h1 align="center"> 
   🔐Footprint and Network Scanning <br>
</h1>
<p align="center"
  <b> Reconnaissance of Networkwalks.com and a local network scanning using Kali linux tools and Zenmap </b>
</p>

<p align="center">

<img src="https://img.shields.io/badge/Skill-Cybersecurity-111827?style=flat-square&labelColor=9f1239">

<img src="https://img.shields.io/badge/Ver-VirtualBox%207.2-2563eb?style=flat-square">

<img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-b45309?style=flat-square">

<img src="https://img.shields.io/badge/Skill-PasswordCracking-111827?style=flat-square">

<br>

<img src="https://img.shields.io/badge/PDFPassword%20Cracking-991b1b?style=flat-square">

<img src="https://img.shields.io/badge/Skill-Ethical Hacking-111827?style=flat-square">

<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github">

<img src="https://img.shields.io/badge/Kali%20Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white">

<br>

<img src="https://img.shields.io/badge/NetworkWalks-7f1d1d?style=flat-square">

<img src="https://img.shields.io/badge/Ethical%20Hacking-9a3412?style=flat-square">

<img src="https://img.shields.io/badge/Oluwatumilara%20Emmanuel%20Opakunbi-991b1b?style=flat-square">

</p>

<hr>

# 🎯 Project Overview
In this week's project, There are two phases:

1. **John The Ripper Password Cracking** using  --- gathering domain, technology DNS, and firewall information from a safe distance.

2. **Local Network Scanning** using Zenmap --- to discover live hosts on the network.
   
<hr>

# 📌 Overview

This repository contains my Week 3 Cybersecurity Internship labs focused on password cracking, hash analysis, and password security.

The labs demonstrate password auditing techniques using:

- 🛠️ John the Ripper
- 🖥️ Johnny GUI
- 🌐 Networkwalks Hash Calculator
- 🔓 Networkwalks Password Cracker
- 📖 Dictionary-based attacks
> ⚠️ The following activities were carried out for educational purposes on authorized files and systems.

<hr>

# 📚 Labs Completed

1️⃣ W3-PM1 — John the Ripper + Johnny GUI
🎯 Objective
Crack the password of a password-protected PDF using John the Ripper (JTR) and its graphical interface, Johnny.

🛠️ Tools Used
Tool	Purpose
John the Ripper 1.9.0-jumbo-1	Password cracking
Johnny GUI 2.2	Graphical interface for JTR
PDF Hash Extractor	Extract PDF password hash
🔬 Methodology
Downloaded and extracted John the Ripper.
Downloaded and installed Johnny GUI.
Configured Johnny to use john.exe.
Extracted the PDF hash.
Saved the extracted hash into hash.txt.
Loaded the hash into Johnny.
Performed a dictionary attack.
Successfully recovered the password.
✅ Result
Cracked Password:

good-luck

📸 Screenshots
01 — JTR Download
JTR Download

02 — Johnny Installation
Johnny Installation

03 — Johnny Settings
Johnny Settings

04 — Hash Extracted
Hash Extracted

05 — Hash Loaded
Hash Loaded

06 — Password Cracked
Password Cracked

07 — Locked pdf
Locked pdf

08 — After Entering Password
unlocked pdf

2️⃣ W3-PM2 — Networkwalks Online Tools
🎯 Objective
Crack the password of a password-protected PDF using Networkwalks online security tools.

🛠️ Tools Used
Tool	Purpose
Networkwalks Hash Calculator	Generate/extract PDF hash
Networkwalks Password Cracker	Password security testing
🔬 Methodology
Uploaded the PDF to the Networkwalks Hash Calculator.
Generated the PDF hash.
Copied the generated hash.
Pasted the hash into the Password Cracker.
Ran the available dictionary attack.
Successfully recovered the password.
✅ Result
Cracked Password:

password1

📸 Screenshots
01 — Hash Calculator
Hash Calculator

02 — Password Cracker
Password Cracker

04 — Password Cracked
Password Cracked

05 — Unlocked pdf
Unlocked pdf

🏆 Flags Captured
Module	Flag
🔐 W3-PM1	nw[cybersecurity_flag_captured_2608]
🌐 W3-PM2	nw{networkwalks_persistence_jtr_270521}
📂 File Descriptions
File	Description
W3-PM1-JTR-Johnny/hash.txt	PDF hash extracted for JTR
W3-PM1-JTR-Johnny/cracked-password.txt	Password recovered using JTR
W3-PM1-JTR-Johnny/screenshots/	JTR + Johnny screenshots
W3-PM2-NWTools/hash.txt	PDF hash generated using NW Tools
W3-PM2-NWTools/cracked-password.txt	Password recovered using NW Tools
W3-PM2-NWTools/screenshots/	Networkwalks screenshots
flags.txt	Flags captured during the labs
🧠 Key Learnings
🔑 Hashing vs Encryption
Hashing is generally a one-way transformation used to represent data as a fixed-length value.

Encryption is a reversible process where encrypted information can be decrypted using an appropriate key.

Understanding this distinction is important when studying password storage and password attacks.

📖 Dictionary Attacks
A dictionary attack attempts passwords from a predefined wordlist.

The labs demonstrated how predictable passwords such as:

password1
good-luck
can be vulnerable to dictionary-based attacks.

🛡️ Password Security Lessons
Strong passwords should:

✅ Be long and unique
✅ Use uppercase and lowercase characters
✅ Include numbers and special characters
✅ Avoid common words
✅ Avoid predictable patterns
✅ Never be reused across multiple accounts
Additional protection can be provided through:

🔐 Password managers
🔑 Multi-factor authentication
🛡️ Strong password policies
🚨 Account lockout and rate limiting
🌐 Real-World Relevance
Password-cracking techniques are useful during authorized cybersecurity assessments for:

🔍 Evaluating password policies
🛡️ Identifying weak credentials
🎓 Security awareness and education
🔐 Testing password-protection mechanisms
🚨 Understanding attacker techniques
The purpose of ethical password auditing is to identify weaknesses before malicious attackers can exploit them.

💻 John the Ripper Commands
Dictionary Attack
john --wordlist=rockyou.txt hash.txt
Display Recovered Password
john --show hash.txt
⚠️ These commands should only be used against hashes and systems you are authorized to test.

🛠️ Tools & Resources
Tool	Purpose	Link
John the Ripper	Password auditing and cracking	https://www.openwall.com/john/
Johnny GUI	GUI for John the Ripper	https://openwall.info/wiki/john/johnny
Networkwalks	Cybersecurity training/tools	https://networkwalks.com/
📊 Lab Summary
Lab	Tool	Attack Type	Result
W3-PM1	JTR + Johnny	Dictionary Attack	good-luck
W3-PM2	NW Tools	Dictionary Attack	password1
📈 Skills Practiced
Linux Cybersecurity JTR Networking

🔐 Password security
🔎 Hash analysis
🛠️ John the Ripper
🖥️ Johnny GUI
📖 Dictionary attacks
🌐 Security tools
📝 Security documentation
📸 Technical evidence collection
📬 Connect With Me
💼 LinkedIn:
My-LINKEDIN

🐙 GitHub:
My-GITHUB

🙏 Acknowledgments
Special thanks to:

Waqas Karim (CCIE)
Instructor & Mentor

NETWORKWALKS
For providing hands-on cybersecurity training and practical lab experience.

⚠️ Disclaimer
This repository was created for educational and cybersecurity training purposes only.

All password-cracking techniques demonstrated here were performed against authorized files and systems as part of a formal training environment.

Unauthorized access, password cracking, or testing of systems without permission may be illegal.
