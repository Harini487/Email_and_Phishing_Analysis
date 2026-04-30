# 📧 Email_and_Phishing_Analysis - Threat Intelligence Reports
 
> A curated collection of real-world phishing emails analyzed using industry-standard tools and methodologies, documented in the style of a professional Security Operations Center (SOC).
 
---
 
## 📌 Overview
 
This repository showcases hands-on phishing email analysis across a range of attack types — from basic credential harvesting to sophisticated macro-based malware delivery. Each case includes the original email sample (`.eml`), and a formal SOC-style analysis report in (`.txt`) format (supporting intelligence screenshots are available on my notion site).
 
The project demonstrates practical skills in:
- Email header forensics and authentication analysis (SPF, DKIM, DMARC)
- URL and domain reputation analysis (VirusTotal, Cisco Talos, DomainTools)
- Malicious attachment analysis and OLE/VBA macro extraction
- Threat intelligence reporting and IOC documentation
- Use of professional tools: PhishTool, eioc.py [https://github.com/MalwareCube/Email-IOC-Extractor], emldump.py [https://github.com/DidierStevens/DidierStevensSuite/blob/master/emldump.py], oledump.py [https://github.com/DidierStevens/DidierStevensSuite/blob/master/oledump.py] , nslookup and dig
---
 
## 🗂️ Repository Structure
 
```
Email_and_Phishing_Analysis/
│
├── emails/
│   ├── challenge1.eml
│   ├── challenge2.eml
│   ├── challenge3.eml
│   ├── sample-1000.eml
│   └── sample-1001.eml
│   
|── Reports/
│   ├── Report_challenge1.txt
│   ├── Report_challenge2.txt
│   ├── Report_challenge2.txt
│   ├── Report_sample-1000.txt
│   └── Report_sample1001.txt
│
├── tools/
│   ├── eioc.py
│   ├── emldump.py
│   └── oledump.py
│
└── README.md
```
 
---
