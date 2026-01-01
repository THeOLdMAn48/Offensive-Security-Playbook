# Passive Reconnaissance

## 📌 Category
### Reconnaissance

---

## 🧠 What is Passive Reconnaissance?
Passive reconnaissance is the process of gathering information about a target **without directly interacting** with its systems.  
The objective is to collect maximum intelligence while remaining **stealthy and undetected**.

Passive recon relies heavily on **OSINT (Open Source Intelligence)**.

---

## 🎯 Objectives
- Identify domains and subdomains
- Discover IP ranges and hosting details
- Understand technology stack
- Collect publicly available organizational data
- Reduce detection risk in early attack phases

---

## 🧰 Tools Used in Passive Reconnaissance

---

### 🔍 Google Dorking
**Description:**  
Uses advanced search operators to discover sensitive or interesting information indexed by search engines.

<img src="images/google-dorking.png" alt="Google Dorking Screenshot" width="700"/>

---

### 🌍 WHOIS
**Description:**  
Provides domain registration details such as registrar, organization, name servers, and creation dates.

<img src="images/whois.png" alt="WHOIS Enumeration Screenshot" width="700"/>

---

### 📡 crt.sh (Certificate Transparency)
**Description:**  
Extracts subdomains and hostnames from publicly logged SSL/TLS certificates.

<img src="images/crtsh.png" alt="crt.sh Subdomain Enumeration Screenshot" width="700"/>

---

### 🛰️ Shodan
**Description:**  
Search engine for internet-exposed devices, services, ports, and technologies using passive data collection.

<img src="images/shodan.png" alt="Shodan Search Screenshot" width="700"/>

---

### 🛰️ Censys
**Description:**  
Indexes hosts, certificates, and services across the internet to analyze external attack surface.

<img src="images/censys.png" alt="Censys Enumeration Screenshot" width="700"/>

---

### 🧠 theHarvester
**Description:**  
Collects emails, subdomains, and hosts from public sources such as search engines and PGP servers.

<img src="images/theharvester.png" alt="theHarvester Output Screenshot" width="700"/>

---

### 🧬 Amass (Passive Mode)
**Description:**  
Performs passive subdomain enumeration using multiple OSINT data sources.

<img src="images/amass.png" alt="Amass Passive Enumeration Screenshot" width="700"/>

---

### 📄 ExifTool
**Description:**  
Extracts metadata from public documents to reveal usernames, software versions, and timestamps.

<img src="images/exiftool.png" alt="ExifTool Metadata Screenshot" width="700"/>

---

### 🧑‍💻 GitHub Search
**Description:**  
Identifies exposed domains, configuration files, API references, and sensitive information in public repositories.

<img src="images/github-recon.png" alt="GitHub Recon Screenshot" width="700"/>

---

## 🛡️ Detection & Defense (Blue Team View)
- Limit publicly exposed information
- Monitor certificate transparency logs
- Prevent sensitive data leaks in public repositories
- Apply proper metadata sanitization
- Implement OSINT exposure monitoring

---

## ⚠️ Legal & Ethical Notice
All reconnaissance activities documented here are performed **only in authorized lab environments** such as:
- TryHackMe
- Hack The Box
- OWASP Juice Shop
- Test domains

Unauthorized reconnaissance on real-world targets is illegal.

---

## 📝 Notes
Passive reconnaissance is the **foundation of every attack lifecycle**.  
Strong defenders minimize what attackers can learn without direct access.
