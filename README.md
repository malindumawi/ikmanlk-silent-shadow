# ikmanlk-silent-shadow

🕵️ Silent Shadow: Passive Reconnaissance & OSINT Assessment
==================================================

🚀 Project Overview
"Silent Shadow" is a passive reconnaissance (OSINT) project conducted on ikman.lk, one of Sri Lanka’s leading online marketplaces. The assessment focuses on identifying publicly exposed attack surfaces without performing any active scanning or generating detectable traffic.

The project strictly follows passive reconnaissance principles to ensure zero interaction with the target infrastructure.

--------------------------------------------------
🎯 Objectives
--------------------------------------------------
- Identify publicly exposed infrastructure and assets
- Map the organization’s digital attack surface
- Analyze human and email exposure risks
- Discover publicly accessible documents and metadata
- Provide risk-based remediation strategies

--------------------------------------------------
🛠️ Tools & Technologies
--------------------------------------------------
- crt.sh (Certificate Transparency Logs)
- dig (DNS Enumeration)
- BGP.he.net (ASN & IP Analysis)
- WHOIS
- Google Dorking
- LinkedIn & RocketReach
- Hunter.io
- HaveIBeenPwned
- Wappalyzer
- ExifTool

--------------------------------------------------
📂 Assessment Phases
--------------------------------------------------

1. 🌐 Infrastructure & DNS Mapping
- Subdomain discovery using crt.sh
- DNS analysis using dig
- ASN & IP mapping using BGP.he.net
- Identified Cloudflare CDN and AWS backend

2. 👤 Human Attack Surface Analysis
- Employee role mapping via LinkedIn
- Email pattern analysis using Hunter.io
- Identified predictable email formats (first.last@ikman.lk)
- Highlighted phishing and BEC risks

3. 📄 Document & Metadata Mining
- Google Dorking for exposed documents
- Identification of publicly indexed PDFs
- Metadata extraction using ExifTool
- Detection of external file hosting risks

4. 🧠 Technology Stack Fingerprinting
- CMS: WordPress
- Backend: PHP & MySQL
- Cloud: AWS + Cloudflare
- Analytics & marketing integrations
- Security features (HSTS, reCAPTCHA)

--------------------------------------------------
🔍 Key Findings
--------------------------------------------------
✔ Publicly accessible admin portal (admin.ikman.lk)  
✔ Predictable corporate email structure (high phishing risk)  
✔ Exposure of employee roles and identities  
✔ Publicly indexed documents referencing external downloads  
✔ Heavy reliance on third-party SaaS services  

(Findings derived from detailed analysis) fileciteturn3file0

--------------------------------------------------
⚠️ Risk Highlights
--------------------------------------------------
- High Risk: Public admin endpoints vulnerable to brute-force attacks  
- High Risk: Email pattern predictability enabling spear phishing  
- Medium Risk: Public document exposure leading to phishing/malware risks  
- Supply Chain Risk: Multiple third-party integrations  

--------------------------------------------------
🛡️ Recommendations
--------------------------------------------------
- Restrict admin access via VPN or IP whitelisting  
- Enforce Multi-Factor Authentication (MFA)  
- Implement DMARC, SPF, and email security policies  
- Remove sensitive endpoints from search engine indexing  
- Limit public exposure of employee information  
- Monitor brand misuse and external file distribution  

--------------------------------------------------
📊 Outcomes
--------------------------------------------------
- Successfully mapped attack surface using OSINT  
- Identified multiple high-risk exposure points  
- Delivered actionable security recommendations  
- Demonstrated real-world passive reconnaissance techniques  

--------------------------------------------------
⚠️ Disclaimer
--------------------------------------------------
This project was conducted using passive reconnaissance techniques only.
No active scanning or unauthorized access was performed.

--------------------------------------------------
👤 Author
--------------------------------------------------
Malindu Wijayarathna

--------------------------------------------------
📄 License
--------------------------------------------------
Academic and Educational Use Only

==================================================
