# 🐴 Trojans – Detailed Explanation

---

## 🔹 What is a Trojan?
A **Trojan horse (Trojan)** is a type of malicious software that **pretends to be legitimate software** but actually performs harmful actions once executed.

- Named after the Greek myth of the wooden horse used to infiltrate Troy.
- Unlike viruses or worms, **Trojans do not self-replicate**.
- Often used to **steal information, install malware, or create backdoors**.

---

## 🔹 How Trojans Work

1. **Delivery**
   - Distributed via email attachments, downloads, pirated software, or fake updates.

2. **Execution**
   - User runs the Trojan thinking it is legitimate software.

3. **Payload Activation**
   - Trojan performs malicious activities like:
     - Stealing credentials or banking info
     - Installing backdoors
     - Logging keystrokes
     - Downloading additional malware

4. **Persistence**
   - Some Trojans modify system settings or registry to survive reboots.

---

## 🔹 Types of Trojans

1. **Backdoor Trojans** – Allow attackers remote access to the infected system.
2. **Downloader Trojans** – Download and install other malware.
3. **Infostealer Trojans** – Steal sensitive data like passwords, banking info, or cookies.
4. **Banking Trojans** – Target financial applications to steal money.
5. **Ransomware Trojans** – Encrypt files and demand ransom.
6. **DDoS Trojans** – Turn infected systems into bots for coordinated attacks.

---

## 🔹 Tools / Techniques Used

- **Social Engineering** – Convincing users to execute malicious files.
- **Phishing Emails** – Attachments or links carrying Trojans.
- **Fake Software Updates** – Masquerading as legitimate updates for browsers or OS.
- **Exploit Kits** – Using browser or software vulnerabilities to deliver Trojans.

---

## 🔹 Case Studies / Real-World Examples

1. **Zeus Trojan** – Targeted banking credentials and caused millions in financial loss.
2. **Emotet** – Initially a banking Trojan, later used to distribute other malware.
3. **Trojan-Spy.Win32** – Spyware Trojan that logs keystrokes and sends data to attackers.

---

## 🔹 Layer of the OSI Model Affected

- **Application Layer (Layer 7)** – Executes malicious code via software or browser.
- **Transport Layer (Layer 4)** – Communicates with attacker servers for data exfiltration.
- **Network Layer (Layer 3)** – Sends stolen data over the internet.

---

## 🔹 Detection & Prevention

**Detection:**
- Antivirus/antimalware software scanning for signatures.
- Monitoring unusual system behavior or network connections.
- Checking for unexpected processes or high CPU usage.

**Prevention:**
- Avoid downloading software from untrusted sources.
- Do not open email attachments or links from unknown senders.
- Keep OS, browsers, and software updated.
- Enable firewalls and endpoint monitoring.

---

## ✅ Summary
**Trojans** disguise themselves as legitimate software to trick users into execution. They can steal information, provide remote access, or install other malware. Unlike viruses or worms, they do not self-replicate. Prevention relies on user awareness, safe downloading practices, and robust endpoint security.
