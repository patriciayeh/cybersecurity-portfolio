# 🛡️ TryHackMe - Introduction to Cybersecurity

This combined log covers my **introductory offensive and defensive cybersecurity exercises** from TryHackMe. These hands-on labs helped me understand both sides of cybersecurity — how attackers exploit vulnerabilities and how defenders detect, analyze, and respond to threats.

---

## ⚒️ Room 1: Defensive Security Introduction

This room introduces the fundamentals of **defensive cybersecurity** and the role of the **Blue Team** in protecting systems, networks, and data. I learned how organizations **prevent, detect, and respond** to cyber threats through SOC operations, threat intelligence, digital forensics, incident response, and malware analysis.

### 🧠 Skills Practiced
- **SOC Operations** → Monitoring systems, detecting suspicious activity, and investigating alerts  
- **Threat Intelligence** → Identifying adversaries, predicting attacks, and preparing defenses  
- **DFIR (Digital Forensics & Incident Response)** →  
  - Collecting and analyzing forensic evidence  
  - Following structured response methodologies  
  - Containment, eradication, and recovery processes  
- **Malware Analysis** → Understanding malware behavior through static and dynamic analysis  
- **SIEM Basics** → Hands-on investigation of security alerts using simulated environments

### 🛠️ Tools & Concepts Used
- **SIEM** – Security Information and Event Management  
- **Threat Intelligence Feeds** – Understanding attacker tactics & techniques  
- **Logs & Monitoring** – Reviewing authentication attempts, IP activity, and network intrusions  
- **Digital Forensics** – Disk, memory, and log analysis

### 📌 Key Takeaways
- Defensive security focuses on **protecting** systems rather than exploiting them.
- The **SOC** is the frontline team that monitors and responds to potential threats.
- **Threat intelligence** helps anticipate attacks and strengthen defenses.
- **DFIR** skills are critical for investigating incidents and minimizing damage.
- Malware analysis techniques (static & dynamic) are essential to understand evolving threats.

---

## ⚔️ Room 2: Offensive Security Introduction

> *"To outsmart a hacker, you need to think like one."*

This TryHackMe room introduces **Offensive Security** by teaching you to **hack a simulated bank application (FakeBank)** in a safe, legal environment. The goal is to understand hacker tactics to improve system defenses.

### 🔹 What I Learned
- How attackers exploit vulnerabilities and find hidden endpoints
- Using **Gobuster** to brute-force website directories and pages
- Identifying unsecured admin portals and sensitive data
- Practicing **ethical hacking** to report vulnerabilities responsibly

### 🛠️ Hands-On Practice
**Objective:** Discover hidden pages and exploit a vulnerability to transfer `$2000` from account `2276` to `8881`.

**Steps:**
1. **Launch FakeBank** – Start the virtual machine.
2. **Scan with Gobuster** -  ```gobuster -u http://fakebank.thm -w wordlist.txt dir```
3. **Found hidden path** - ```/bank-transfer```
4. **Exploit the Transfer Page** – Use the discovered endpoint to perform the transfer.
5. **Verify Results** – Refresh your account page to confirm the successful hack.

### 🧠 Key Takeaways
- Thinking like a hacker strengthens your security mindset.
- Recon tools like Gobuster are vital for discovering vulnerabilities.
- Hands-on environments make security learning more effective.
- Always practice responsible, authorized testing.

> ✅ Outcome: Successfully completed my first simulated website hack and gained foundational skills in offensive security and web vulnerability discovery.
