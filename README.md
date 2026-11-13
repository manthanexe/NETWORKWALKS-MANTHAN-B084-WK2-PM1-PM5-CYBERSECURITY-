# NETWORKWALKS-MANTHAN-B084-WK2-PM1-PM5-CYBERSECURITY-
Week 2 Cybersecurity Internship Report - Practical Modules PM1 and # NETWORKWALKS Cybersecurity Internship - Week 2 Report

- **Intern Name:** Manthan Acharya
- **Internship Batch:** B084
- **Domain:** Cybersecurity
- **Reporting Week:** Week 2
- **Organization:** NETWORKWALKS
- **Practical Modules:** W2-PM1 and W2-PM5

---

## 1. Introduction
During the second week of my cybersecurity internship at NETWORKWALKS, I focused on practical reconnaissance techniques, domain footprinting, web technology identification, HTTP response analysis, and network scanning. The exercises provided hands-on exposure to commonly used cybersecurity tools available in Kali Linux and helped build an understanding of how security professionals gather information about domains, websites, and network hosts.

The practical work covered two modules:
* **W2-PM1:** Footprinting with Multiple Kali Linux Tools.
* **W2-PM5:** Zenmap-Based Network Scanning.

---

## 2. Objectives
* Understand domain footprinting and reconnaissance.
* Gather domain registration and DNS-related information.
* Perform DNS enumeration using reconnaissance tools.
* Identify website technologies and publicly detectable WAF information.
* Examine HTTP response headers.
* Understand host discovery and basic network scanning.
* Gain practical experience with Zenmap and Nmap.
* Follow ethical scanning practices and maintain a clearly defined scope.

---

## 3. W2-PM1: Footprinting with Multiple Kali Linux Tools

### 3.1 WHOIS - Domain Information Gathering
* **Objective:** Retrieve publicly available domain registration information. WHOIS is a lookup protocol used to obtain registration-related details about a domain.
* **Information available:** Domain registrar, creation/expiration dates, name servers, registration status, and publicly disclosed registrant info.
* **Example Command:** `whois example.com`

### 3.2 DNSRecon - DNS Enumeration
* **Objective:** Identify DNS records and gather information about a domain's DNS infrastructure.
* **Key Activities:** DNS record enumeration, identifying name servers, mail servers, and collecting publicly available DNS information.
* **Example Command:** `dnsrecon -d example.com`

### 3.3 NSLookup - DNS Lookup
* **Objective:** Perform DNS queries and understand domain name resolution using a command-line utility to query DNS servers.
* **Example Command:** `nslookup example.com`

### 3.4 WhatWeb - Website Technology Fingerprinting
* **Objective:** Identify technologies used by a website (web server technologies, CMS, JavaScript frameworks, etc.).
* **Example Command:** `whatweb https://example.com`

### 3.5 WAFW00F - Web Application Firewall Detection
* **Objective:** Identify whether a website appears to be protected by a WAF and detect its technology.
* **Example Command:** `wafw00f https://example.com`

### 3.6 cURL - HTTP Response Header Analysis
* **Objective:** Examine HTTP response headers (status codes, Content-Type, server information, security headers) using cURL.
* **Example Command:** `curl -I https://example.com`

---

## 4. W2-PM5: Zenmap-Based Network Scanning

### 4.1 Introduction to Zenmap
Zenmap is the graphical user interface for Nmap, providing a visual interface for configuring scans, viewing results, and analyzing discovered hosts and services.

### 4.2 Host Discovery
* **Objective:** Identify active hosts within an authorized network environment.
* **Procedure:** Entered an authorized target in Zenmap, selected an appropriate discovery scan, and reviewed responding systems.

### 4.3 Quick Scan
* **Objective:** Perform a basic network scan to discover open ports, detected services, and service versions.

### 4.4 Practical Scanning Target
* **Target used:** `scanme.nmap.org` (Provided by the Nmap project for testing and practice purposes in accordance with published guidelines).

---

## 5. Tools and Technologies Used
| Tool | Purpose |
| :--- | :--- |
| **Kali Linux** | Cybersecurity testing environment |
| **WHOIS** | Domain registration lookup |
| **DNSRecon** | DNS enumeration |
| **NSLookup** | DNS queries and resolution |
| **WhatWeb** | Website technology fingerprinting |
| **WAFW00F** | WAF detection and fingerprinting |
| **cURL** | HTTP response analysis |
| **Zenmap** | GUI-based network scanning |
| **Nmap** | Network discovery and scanning |

---

## 6. Key Learnings
* Domain footprinting provides useful initial insights into registration details.
* DNS enumeration maps out infrastructure and records associated with a target.
* Website fingerprinting identifies underlying web applications and frameworks.
* WAF detection uncovers publicly visible web security mechanisms.
* HTTP response headers reveal communication details and server behaviors.
* Host discovery and port scanning accurately map active network nodes and exposed services.
* Ethical reconnaissance requires strict adherence to authorized scopes and evidence-based reporting.

---

## 7. Ethical Considerations
* Conducted all exercises strictly within authorized scopes.
* Avoided unauthorized access, exploitation, or disruption of targets.
* Documented findings accurately based on actual tool output.

---

## 8. Conclusion
Week 2 of the NETWORKWALKS cybersecurity internship provided deep, practical exposure to domain reconnaissance, DNS enumeration, web fingerprinting, HTTP header analysis, and network scanning via Zenmap and Nmap. This reinforced core cybersecurity concepts and improved technical command-line proficiency.

---

## 9. Practical Evidence and Documentation
* Screenshots of tool executions (`Zenmap`, `DNSRecon`, `WhatWeb`, `WAFW00F`, `NSLookup`) are uploaded directly to this repository.
* Full formal documentation is compiled in the submitted PDF report (`Week-2-Report-Manthan-Acharya-B084.pdf`).

**Submitted by:** Manthan Acharya  
**Role:** Cybersecurity Intern - Batch B084  
**Organization:** NETWORKWALKS


