# Offensive Security Playbook 🔴

A structured and ethical offensive cybersecurity knowledge base documenting real-world attack methodologies, tools, lab-based exploitation, detection techniques, and mitigations.

This repository represents my hands-on cybersecurity learning journey, focused on offensive security (red teaming) while maintaining strong ethical and defensive awareness.

---

## 🎯 Purpose of This Repository

- Document offensive security attacks in a **structured and professional manner**
- Practice attacks **only in authorized lab environments**
- Build a personal **red team knowledge base**
- Demonstrate practical cybersecurity skills to recruiters and security teams
- Bridge the gap between **attack execution and defense/detection**

---

## ⚠️ Legal & Ethical Disclaimer

> This repository is strictly for **educational and ethical hacking purposes only**.  
> All techniques demonstrated here are practiced in **authorized lab environments** such as:
> - TryHackMe  
> - Hack The Box  
> - DVWA  
> - OWASP Juice Shop  

🚫 **Do NOT use these techniques on real systems without explicit permission.**  
The author is not responsible for any misuse of the information provided.

(See `DISCLAIMER.md` for full details)

---

## 📂 Repository Structure

```
📦 offensive-security-playbook
 ┣ 📄 README.md
 ┣ 📄 DISCLAIMER.md
 ┣ 📄 ROADMAP.pdf
 │
 ┣ 📂 01-Reconnaissance
 │   ┣ passive-recon.md
 │   ┣ active-recon.md
 │   ┗ tools.md
 │
 ┣ 📂 02-Web-Attacks
 │   ┣ sql-injection.md
 │   ┣ xss.md
 │   ┣ idor.md
 │   ┣ file-upload.md
 │   ┣ auth-bypass.md
 │
 ┣ 📂 03-Network-Attacks
 │   ┣ nmap-enumeration.md
 │   ┣ smb-attacks.md
 │   ┣ mitm.md
 │   ┣ brute-force.md
 │   ┗ dos-attacks.md
 │
 ┣ 📂 04-Linux-Privilege-Escalation
 │   ┣ enumeration.md
 │   ┣ suid-abuse.md
 │   ┣ cron-abuse.md
 │   ┗ sudo-misconfig.md
 │
 ┣ 📂 05-Windows-Privilege-Escalation
 │   ┣ service-misconfig.md
 │   ┣ dll-hijacking.md
 │   ┣ registry-abuse.md
 │   ┗ token-impersonation.md
 │
 ┣ 📂 06-Active-Directory
 │   ┣ ad-enumeration.md
 │   ┣ kerberoasting.md
 │   ┣ asrep-roasting.md
 │   ┣ lateral-movement.md
 │   ┗ dcsync.md
 │
 ┣ 📂 07-Wireless-Attacks
 │   ┣ wifi-attacks.md
 │   ┗ evil-twin.md
 │
 ┣ 📂 08-Cloud-Attacks
 │   ┣ cloud-misconfig.md
 │   ┣ iam-privesc.md
 │   ┣ ssrf-metadata.md
 │   ┗ exposed-keys.md
 │
 ┣ 📂 09-Mobile-Security
 │   ┣ android-attacks.md
 │   ┗ ios-attacks.md
 │
 ┣ 📂 10-Post-Exploitation
 │   ┣ persistence.md
 │   ┣ lateral-movement.md
 │   ┗ lolbins.md
 │
 ┣ 📂 11-Detection-and-Defense
 │   ┣ mitre-mapping.md
 │   ┣ siem-detections.md
 │   ┗ mitigations.md
 │
 ┗ 📂 12-TryHackMe-Writeups
     ┣ room-name-1.md
     ┗ room-name-2.md

```
---
Each directory contains:
- Attack explanation
- Tools used
- Lab-based steps
- Detection techniques
- Mitigation strategies
---

## 🧠 Topics Covered

### 🌐 Web Application Attacks
- SQL Injection
- XSS
- IDOR
- Authentication Bypass
- File Upload Vulnerabilities
- API Security Issues

### 🖧 Network Attacks
- Reconnaissance & Enumeration
- MITM Attacks
- SMB Exploitation
- Brute Force Attacks
- Denial of Service (DoS)

### 🐧 Linux & 🪟 Windows Attacks
- Privilege Escalation Techniques
- Misconfigurations
- Credential Abuse
- Enumeration Methodologies

### 🏢 Active Directory Attacks
- Kerberoasting
- AS-REP Roasting
- Pass-the-Hash / Ticket
- Lateral Movement
- Domain Privilege Escalation

### ☁️ Cloud & 📱 Mobile Security
- Cloud Misconfigurations
- IAM Privilege Escalation
- Android & iOS Security Issues

### 🛡️ Detection & Defense
- MITRE ATT&CK Mapping
- SIEM Detection Ideas
- Defensive Mitigations

---

## 🛠️ Tools & Technologies

- Kali Linux
- Burp Suite
- OWASP ZAP
- Nmap
- Metasploit
- Hydra
- Python & Bash
- BloodHound
- Wireshark

---

## 📈 Learning Roadmap

This repository follows a structured roadmap:
1. Reconnaissance
2. Initial Access
3. Exploitation
4. Privilege Escalation
5. Lateral Movement
6. Post-Exploitation
7. Detection & Mitigation

Refer to `ROADMAP.pdf` for the complete plan.

---

## 🤝 Contributions & Feedback

This is a personal learning repository.  
Feedback, suggestions, and discussions are welcome.

---

## 👤 Author

**Om Gohil**  
Cybersecurity Enthusiast | Offensive Security Learner  
TryHackMe: THeOLdMAn  

---

## ⭐ Final Note

> “Learn attacks to build better defenses.”

If you find this repository useful, feel free to ⭐ star it.
