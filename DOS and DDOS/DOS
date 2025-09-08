# 🛑 Denial of Service (DoS) Attack – Detailed Overview

---

## 📌 Introduction

A **Denial of Service (DoS)** attack is a malicious attempt to make a machine, network, or service unavailable to its intended users by **overwhelming resources** or **exploiting vulnerabilities**.  

When performed by multiple distributed systems (often compromised into a **botnet**), it becomes a **Distributed Denial of Service (DDoS)** attack.  

---

## ⚙️ How DoS Works

1. **Target Selection** – An attacker chooses a server, application, or network.  
2. **Attack Method** – Attacker floods the target with requests or exploits protocol/application weaknesses.  
3. **Resource Exhaustion** – CPU, memory, bandwidth, or application threads get saturated.  
4. **Service Disruption** – Legitimate users cannot access the service.  

---

## 🔹 Types of DoS Attacks

### 1. Volume-Based Attacks
- **Example:** ICMP Flood, UDP Flood  
- **Goal:** Saturate bandwidth with massive traffic.  

### 2. Protocol-Based Attacks
- **Example:** SYN Flood, Ping of Death  
- **Goal:** Exploit vulnerabilities in network protocols.  

### 3. Application-Layer Attacks
- **Example:** HTTP Flood, Slowloris  
- **Goal:** Target web servers by exhausting application-level resources.  

### 4. Resource Depletion Attacks
- **Example:** TCP connection exhaustion  
- **Goal:** Overload server’s CPU, memory, or disk resources.  

### 5. Permanent DoS (PDoS)
- **Example:** Attacks that corrupt firmware or hardware  
- **Goal:** Render device permanently unusable.  

---

## 🔧 Tools Used in DoS/DDoS

- **Slowloris** → Keeps connections open with partial requests.  
- **HOIC (High Orbit Ion Cannon)** → Open-source tool to launch floods.  
- **Mirai Botnet** → Uses IoT devices to launch large-scale DDoS.  
- **LOIC (Low Orbit Ion Cannon)** → Early tool for traffic flooding.  

---

## 📚 Real-World Case Studies

### 1. GitHub DDoS (2018)
- **Attack:** 1.35 Tbps memcached amplification.  
- **Impact:** Temporary service disruption.  
- **Mitigation:** Akamai rerouted and scrubbed malicious traffic.  

### 2. Dyn DNS Attack (2016)
- **Attack:** Mirai botnet launched massive DDoS on Dyn DNS.  
- **Impact:** Twitter, Netflix, Reddit, Spotify went offline.  
- **Mitigation:** Traffic filtering, IoT security improvements.  

### 3. Krebs on Security (2016)
- **Attack:** 620 Gbps DDoS by Mirai botnet.  
- **Impact:** Akamai withdrew free DDoS protection due to scale.  
- **Mitigation:** Migrated to Google’s Project Shield.  

### 4. Estonia Cyberattacks (2007)
- **Attack:** Government and banking sites hit by large-scale DDoS.  
- **Impact:** National-level disruption for weeks.  
- **Mitigation:** NATO cooperation, traffic filtering, IP blacklisting.  

### 5. Philippine Media (2018–2019)
- **Attack:** Independent news portals taken offline by DDoS.  
- **Impact:** Press freedom suppressed.  
- **Mitigation:** Partnered with Qurium for hosting and filtering.  

---

## ⚠️ Impact of DoS/DDoS

- 💸 **Financial Losses:** Millions lost due to downtime (Amazon ~ $220k/min).  
- 🏢 **Operational Disruption:** Government and business services halted.  
- 🌍 **Reputation Damage:** Loss of customer trust.  
- 🔗 **Collateral Impact:** One provider’s downtime affects multiple services.  

---

## 🛡️ Mitigation Strategies

### ✅ Network-Level Defenses
- Firewalls with rate-limiting.  
- IDS/IPS for anomaly detection.  
- Blacklisting malicious IPs.  

### ✅ Application-Level Defenses
- Web Application Firewall (WAF).  
- Load balancing across servers.  
- CAPTCHAs and request throttling.  

### ✅ Cloud-Based Defenses
- **CDN and DDoS providers**: Cloudflare, Akamai, AWS Shield, Google Cloud Armor.  
- Traffic rerouting and scrubbing centers.  

### ✅ Architectural Defenses
- Anycast routing to distribute load globally.  
- Redundancy and failover systems.  
- Optimized backend with caching.  

### ✅ Preventive Measures
- Secure IoT devices (patch & update).  
- Regular penetration testing.  
- Incident response and business continuity plans.  

---

## 🔬 Research & Future Defense

- **AI-Based Detection:** ResNet, ML models detect DoS/DDoS with 99% accuracy.  
- **Blockchain Mitigation:** Decentralized collaboration against large-scale DDoS.  
- **Artificial Immune Systems:** Adaptive detection using anomaly recognition.  

---

## 📝 Summary

- **DoS/DDoS** → Disrupt availability by exhausting resources.  
- **Examples:** SYN floods, Slowloris, Mirai botnet.  
- **Case Studies:** GitHub (2018), Dyn DNS (2016), Estonia (2007).  
- **Impact:** Financial, reputational, and operational losses.  
- **Mitigation:** Requires **layered defense** (network, application, cloud, architecture).  

---

## 📖 References

- [Cloudflare – What is DDoS?](https://www.cloudflare.com/learning/ddos/what-is-a-ddos-attack/)  
- [Wikipedia – Denial-of-service attack](https://en.wikipedia.org/wiki/Denial-of-service_attack)  
- [Rapid7 – DoS Attacks Explained](https://www.rapid7.com/fundamentals/denial-of-service-attacks/)  
- [Case Studies – OmniCyber Security](https://www.omnicybersecurity.com/case_studies/case-study-denial-of-service-attacks/)  

---
