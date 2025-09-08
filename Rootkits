# 👾 Rootkits – Detailed Explanation

---

## 🔹 What is a Rootkit?
A **rootkit** is a type of malicious software designed to **gain unauthorized root or administrative access** to a system and **remain hidden**.

- The term “root” refers to the highest-level user in Unix/Linux systems.
- Rootkits **hide processes, files, network connections, and system modifications** to avoid detection.
- Often used to maintain **persistent access** for attackers and to conceal other malware.

---

## 🔹 How Rootkits Work

1. **Installation**
   - Delivered via Trojans, malware, exploits, or social engineering.

2. **Privilege Escalation**
   - Rootkits gain administrative/root privileges to manipulate system resources.

3. **Hiding Techniques**
   - Hooking system calls, modifying kernel modules, or using stealth processes.

4. **Malicious Actions**
   - Concealing other malware, logging keystrokes, stealing data, or creating backdoors.

---

## 🔹 Types of Rootkits

1. **User-Mode Rootkits**
   - Operate at application layer; easier to detect than kernel rootkits.

2. **Kernel-Mode Rootkits**
   - Operate at OS kernel level; harder to detect and highly stealthy.

3. **Bootkits**
   - Infect the Master Boot Record (MBR) or UEFI; loads before OS, very persistent.

4. **Firmware Rootkits**
   - Reside in hardware firmware (BIOS, network cards); extremely hard to remove.

5. **Memory Rootkits**
   - Reside in system memory; vanish after reboot but can perform attacks while active.

---

## 🔹 Tools / Techniques Used

- **Hooking API/System Calls** – Intercepting system functions to hide activities.
- **Kernel Module Manipulation** – Altering kernel code for stealth.
- **Firmware Tampering** – Modifying hardware-level firmware.
- **Polymorphic & Metamorphic Techniques** – To avoid signature-based detection.

---

## 🔹 Case Studies / Real-World Examples

1. **Sony BMG Rootkit (2005)** – Music CDs installed rootkit on Windows PCs to prevent copying.
2. **Stuxnet** – Used rootkit functionality to hide malware from industrial control systems.
3. **Rustock Botnet** – Used rootkits to remain undetectable while sending spam emails.

---

## 🔹 Layer of the OSI Model Affected

- **Application Layer (Layer 7)** – User-mode rootkits hide applications and processes.
- **System/Kernel Layer (Below Layer 7)** – Kernel/root-level rootkits manipulate OS functions.
- **Network Layer (Layer 3)** – Rootkits may hide network activity and exfiltration.

---

## 🔹 Detection & Prevention

**Detection:**
- Signature-based antivirus may fail; use behavioral monitoring.
- Detect hidden processes, files, or network connections.
- Use integrity checkers like Tripwire or specialized rootkit detectors (chkrootkit, rkhunter).

**Prevention:**
- Keep OS and software updated.
- Limit administrative privileges.
- Use secure boot, UEFI, and firmware protection.
- Avoid running untrusted applications or opening unknown attachments.

---

## ✅ Summary
**Rootkits** provide attackers stealthy and persistent access by hiding system modifications, processes, and malware. They are hard to detect and can operate at user, kernel, boot, firmware, or memory levels. Prevention involves strong system security, restricted privileges, and specialized monitoring tools.
