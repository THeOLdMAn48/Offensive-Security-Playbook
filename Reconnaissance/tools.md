# Reconnaissance Tools

## 📌 Category
Reconnaissance

---

## 🧠 Overview
Reconnaissance tools are used to collect information about targets during the early stages of an attack.  
These tools help identify domains, subdomains, services, technologies, and exposed assets.

Recon tools are divided into **Passive** and **Active** categories based on interaction with the target.

---

## 🔍 Passive Reconnaissance Tools

---

### 🌐 Google Dorking
**Description:**  
Uses advanced search queries to identify publicly exposed files, directories, and sensitive information indexed by search engines.

### Google dork cheatsheet

## Search filters
| Filter          | Description                                        | Example                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
| allintext      | Searches for occurrences of all the keywords given. | `allintext:"keyword"` |
| intext      | Searches for the occurrences of keywords all at once or one at a time. | `intext:"keyword"` |
| inurl      | Searches for a URL matching one of the keywords. | `inurl:"keyword"` |
| allinurl      | Searches for a URL matching all the keywords in the query. | `allinurl:"keyword"` |
| intitle      | Searches for occurrences of keywords in title all or one. | `intitle:"keyword"` |
| allintitle      | Searches for occurrences of keywords all at a time. | `allintitle:"keyword"` |
| site      | Specifically searches that particular site and lists all the results for that site. | `site:"www.google.com"` |
| filetype      | Searches for a particular filetype mentioned in the query. | `filetype:"pdf"` |
| link      | Searches for external links to pages. | `link:"keyword"` |
| numrange      | Used to locate specific numbers in your searches. | `numrange:321-325` |
| before/after      | Used to search within a particular date range. | `filetype:pdf & (before:2000-01-01 after:2001-01-01)` |
| allinanchor (and also inanchor)      | This shows sites which have the keyterms in links pointing to them, in order of the most links. | `inanchor:rat` |
| allinpostauthor (and also inpostauthor)      | Exclusive to blog search, this one picks out blog posts that are written by specific individuals. | `allinpostauthor:"keyword"` |
| related      | List web pages that are “similar” to a specified web page. | `related:www.google.com` |
| cache      | Shows the version of the web page that Google has in its cache. | `cache:www.google.com` |


---

### 🌍 WHOIS
**Description:**  
Retrieves domain ownership, registrar, and name server information from public records.

<img src="images/whois.png" alt="WHOIS Screenshot" width="700"/>

---

### 📡 crt.sh
**Description:**  
Analyzes Certificate Transparency logs to uncover subdomains and related hostnames.

<img src="images/crtsh.png" alt="crt.sh Screenshot" width="700"/>

---

### 🛰️ Shodan
**Description:**  
Search engine for discovering internet-facing services, devices, and exposed ports using passive data sources.

<img src="images/shodan.png" alt="Shodan Screenshot" width="700"/>

---

### 🛰️ Censys
**Description:**  
Indexes hosts, services, and SSL certificates to map an organization’s external attack surface.

<img src="images/censys.png" alt="Censys Screenshot" width="700"/>

---

### 🧠 theHarvester
**Description:**  
Collects emails, subdomains, and host information from public data sources.

<img src="images/theharvester.png" alt="theHarvester Screenshot" width="700"/>

---

### 🧬 Amass (Passive Mode)
**Description:**  
Performs passive subdomain enumeration using multiple OSINT sources.

<img src="images/amass.png" alt="Amass Screenshot" width="700"/>

---

### 📄 ExifTool
**Description:**  
Extracts metadata from publicly accessible documents to reveal user and system information.

<img src="images/exiftool.png" alt="ExifTool Screenshot" width="700"/>

---

### 🧑‍💻 GitHub Search
**Description:**  
Searches public repositories for exposed domains, configuration files, and sensitive references.

<img src="images/github-recon.png" alt="GitHub Recon Screenshot" width="700"/>

---

## 🖧 Active Reconnaissance Tools

---

### 🧭 Nmap
**Description:**  
Performs host discovery, port scanning, service enumeration, and OS detection.

<img src="images/nmap.png" alt="Nmap Screenshot" width="700"/>

---

### ⚡ Masscan
**Description:**  
High-speed port scanner for large-scale network reconnaissance.

<img src="images/masscan.png" alt="Masscan Screenshot" width="700"/>

---

### 🔌 Netcat
**Description:**  
Networking utility used for banner grabbing and service interaction.

<img src="images/netcat.png" alt="Netcat Screenshot" width="700"/>

---

### 🕵️ Nikto
**Description:**  
Web server scanner that identifies vulnerabilities and misconfigurations.

<img src="images/nikto.png" alt="Nikto Screenshot" width="700"/>

---

### 📂 Gobuster
**Description:**  
Discovers hidden directories, files, and DNS names through brute-force techniques.

<img src="images/gobuster.png" alt="Gobuster Screenshot" width="700"/>

---

### 📂 Dirsearch
**Description:**  
Advanced directory and file brute-forcing tool for web applications.

<img src="images/dirsearch.png" alt="Dirsearch Screenshot" width="700"/>

---

### 🌐 WhatWeb
**Description:**  
Identifies technologies used by web servers and applications.

<img src="images/whatweb.png" alt="WhatWeb Screenshot" width="700"/>

---

### 🔍 Wappalyzer
**Description:**  
Detects frontend and backend technologies through browser-based analysis.

<img src="images/wappalyzer.png" alt="Wappalyzer Screenshot" width="700"/>

---

## ⚠️ Legal & Ethical Notice
All tools listed are used strictly in **authorized lab environments** only.

---

## 📝 Notes
Reconnaissance tools provide critical intelligence that shapes exploitation strategies.  
Effective defenders reduce information exposure at this stage.
