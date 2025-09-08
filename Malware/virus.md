# 🦠 Computer Virus – Detailed Explanation  

---

## 🔹 What is a Computer Virus?  
A **computer virus** is a type of **malware** that attaches itself to a legitimate program or file and spreads when that program/file is executed.  
It requires **human action** (like opening an infected file or running a program) to propagate, unlike worms which spread automatically.  

Viruses can damage files, steal data, slow down systems, and even disable entire networks.  

---

## 🔹 How a Virus Works (Lifecycle)
1. **Infection** – The virus attaches itself to a host file, boot sector, or program.  
2. **Execution** – When the infected file/program is run, the virus activates.  
3. **Replication** – The virus makes copies of itself and spreads to other files, devices, or networks.  
4. **Payload Execution** – It performs its malicious purpose (deleting files, stealing credentials, showing messages, etc.).  
5. **Dormancy (optional)** – Some viruses stay hidden until a trigger event (e.g., a specific date).  

---

## 🔹 Types of Computer Viruses
1. **File Infector Viruses** – Attach to executable files (`.exe`, `.com`).  
   - Example: **Cascade Virus** (made text “fall” on screen).  

2. **Boot Sector Viruses** – Infect the Master Boot Record (MBR) of storage devices.  
   - Example: **Michelangelo Virus**.  

3. **Macro Viruses** – Written in scripting languages like VBA; spread via documents (Word, Excel).  
   - Example: **Melissa Virus**.  

4. **Polymorphic Viruses** – Change their code every time they infect to evade detection.  
   - Example: **Storm Worm**.  

5. **Metamorphic Viruses** – Rewrite their own code to avoid detection.  

6. **Resident Viruses** – Hide in system memory and infect files automatically.  

7. **Multipartite Viruses** – Attack multiple areas (files + boot sector).  

---

## 🔹 Tools Used to Create or Analyze Viruses
- **Creation (used by attackers)**  
  - Malware development kits (illegal)  
  - Exploit frameworks (e.g., Metasploit with payloads)  
  - Custom scripting languages  

- **Detection & Analysis (used by defenders)**  
  - **Antivirus software**: Avast, Kaspersky, Windows Defender  
  - **Static analysis tools**: IDA Pro, Ghidra, PEiD  
  - **Dynamic analysis tools**: Cuckoo Sandbox, Any.Run  
  - **Threat intelligence platforms**: VirusTotal, Hybrid Analysis  

---

## 🔹 Latest Virus Outbreaks & Case Studies
1. **ILOVEYOU Virus (2000)**  
   - Spread via email attachments.  
   - Caused **$10 billion damage** globally.  

2. **Stuxnet (2010)**  
   - Targeted Iranian nuclear facilities.  
   - Extremely advanced, infected Siemens SCADA systems.  

3. **Conficker Worm (2008–2009)**  
   - Technically a worm, but virus-like behavior.  
   - Infected **millions of computers worldwide**.  

4. **COVID-19 Themed Malware (2020)**  
   - Attackers spread virus-infected files disguised as COVID-19 dashboards.  

5. **Emotet (2014–2021, resurgence 2022)**  
   - A polymorphic virus that evolved into a botnet and ransomware dropper.  

---

## 🔹 Which Layer Does a Virus Affect?  
Viruses generally affect the following **layers of a system/network**:  

- **Application Layer (OSI Model Layer 7)** –  
  Infects files, programs, and documents (macro viruses, file infectors).  

- **Operating System Layer** –  
  Resident viruses modify system libraries, registry, or services.  

- **Boot/Hardware Layer** –  
  Boot sector viruses target the Master Boot Record (MBR) of storage drives.  

👉 In short: Viruses primarily target the **Application Layer** but some extend deeper into **OS and hardware layers**.  

---

## 🔹 Extra Insights
- **Motives**: Cybercrime (financial gain), hacktivism, espionage, vandalism.  
- **Delivery**: Email attachments, malicious USBs, pirated software, infected websites.  
- **Impact**: Data theft, corruption, financial loss, denial of service.  

---

## ✅ Summary  
A **virus** is a self-replicating malware that needs a host file/program. It infects files, OS, or boot sectors, spreads via human action, and delivers a payload ranging from pranks to large-scale cyberattacks. Case studies like **ILOVEYOU** and **Stuxnet** show their real-world impact. Viruses mostly attack the **Application Layer**, but advanced ones go deeper into OS and hardware.  