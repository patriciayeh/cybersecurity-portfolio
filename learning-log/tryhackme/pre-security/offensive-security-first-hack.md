## 🕵️ TryHackMe – Offensive Security: First Website Hack

> *"To outsmart a hacker, you need to think like one."*

This TryHackMe room introduces **Offensive Security** by teaching you to **hack a simulated bank application (FakeBank)** in a safe, legal environment. The goal is to understand hacker tactics to improve system defenses.

---

### 🔹 What I Learned
- How attackers exploit vulnerabilities and find hidden endpoints
- Using **Gobuster** to brute-force website directories and pages
- Identifying unsecured admin portals and sensitive data
- Practicing **ethical hacking** to report vulnerabilities responsibly

---

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
