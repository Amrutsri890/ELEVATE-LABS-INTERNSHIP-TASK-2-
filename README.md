# ELEVATE-LABS-INTERNSHIP-TASK-2-
Identify phishing characteristics in a suspicious email sample.
# What I Did:

Collected a phishing email sample that appeared to impersonate PayPal.
Extracted the raw email headers (email_headers.txt) and performed header analysis to check for spoofing, SPF/DKIM/DMARC failures, and mismatched sender domains.
Inspected the email body for red flags such as urgent language, fake links, poor grammar, and brand impersonation.
Hovered over suspicious links and captured the real URL (link_hover.png).
Used analysis tools (SpamAssassin / header analyzers / VirusTotal) to validate the findings.
Documented the results in analysis_report.md along with screenshots.

# Email Phishing Analysis Project

**Author:** S. Sai Amrutha  
**Institution:** GD Goenka University  
**Program:** BTech CSE - Cybersecurity  
**Internship:** Elevate Labs

## Project Overview

This repository contains a comprehensive analysis of phishing email samples as part of an internship task. The project demonstrates practical cybersecurity skills through hands-on email forensics, header analysis, and phishing detection techniques.

## Objectives

- Analyze suspicious email samples to identify phishing indicators
- Examine email headers for spoofing and authentication failures  
- Create educational awareness content about phishing detection
- Apply cybersecurity tools for email forensics and threat analysis

## Tools and Technologies

- **EML Analyzer** - Email header analysis and forensic investigation
- **ChatGPT** - Research assistance and content analysis
- **Google Forms** - Interactive phishing awareness quiz creation
- **Gmail** - Email platform for phishing simulation
- **Header Analysis Tools** - Technical verification and authentication checks

## Project Components

### 1. Phishing Email Creation & Analysis
- Created a realistic phishing email simulation impersonating PayPal
- Sender: `paypaldepartments.org@gmail.com` (intentionally suspicious)
- Subject: "URGENT: CONFORM YOUR RECENT PAYPAL ACTIVITY"
- Incorporated common phishing tactics: urgency, poor grammar, fake links

### 2. Interactive Awareness Quiz
Developed a comprehensive Google Forms quiz covering:
- **Sender Verification** - Identifying spoofed domains
- **Grammar & Spelling** - Recognizing linguistic red flags
- **Urgency Tactics** - Understanding psychological manipulation
- **Link Analysis** - Hover-to-reveal malicious URLs

### 3. Technical Header Analysis
Conducted detailed forensic analysis including:
- **Basic Headers** - Message ID, timestamps, sender verification
- **Authentication Results** - SPF, DKIM, DMARC validation
- **OLEID Analysis** - Malicious attachment detection
- **Spam Scoring** - SpamAssassin rating (6.30/10)

## Key Findings

### Phishing Indicators Identified
- ✅ **Spoofed Sender** - Gmail address impersonating PayPal corporate domain
- ✅ **Authentication Failures** - Missing DKIM signatures and SPF validation
- ✅ **Social Engineering** - Urgent threats and fear-based messaging  
- ✅ **Suspicious Links** - Malicious URLs (paypal-secure-verify.com)
- ✅ **Poor Grammar** - Intentional spelling errors and typos
- ✅ **Visual Deception** - HTML formatting and large images

### Technical Analysis Results
```
SpamAssassin Score: 6.30/10 (High Risk)
Authentication Status: FAILED
DKIM Verification: ABSENT
SPF Check: FAILED
Blacklist Status: FLAGGED
```

## Learning Outcomes

This project enhanced understanding of:
- **Email Forensics** - Technical analysis of email headers and routing
- **Phishing Psychology** - Social engineering tactics and user manipulation
- **Authentication Protocols** - SPF, DKIM, and DMARC security frameworks
- **Threat Detection** - Identifying malicious indicators and red flags
- **Cybersecurity Awareness** - Creating educational content for end users

## Repository Structure

```
├── Task-2-BY-AMMU.pdf          # Complete analysis report
├── README.md                   # Project documentation
├── phishing-sample/            # Email samples and headers
├── analysis-tools/             # EML analyzer outputs
└── awareness-quiz/             # Google Forms quiz content
```

## Educational Impact

The project includes an interactive awareness quiz that teaches users to:
- Identify suspicious sender domains
- Recognize grammatical errors as phishing indicators
- Understand urgency-based social engineering
- Practice safe link verification techniques

## Professional Skills Demonstrated

- **Technical Analysis** - Email header forensics and tool utilization
- **Documentation** - Comprehensive reporting and findings presentation  
- **Education Design** - Interactive learning content creation
- **Threat Assessment** - Risk evaluation and indicator identification
- **Critical Thinking** - Systematic approach to cybersecurity investigation

## Future Applications

This foundational work in email security analysis prepares for advanced roles in:
- **Security Operations Centers (SOC)**
- **Incident Response Teams**
- **Digital Forensics**
- **Cybersecurity Awareness Training**
- **Threat Intelligence Analysis**

## Contact Information

**Email:** 240160226211.sunkavalli@gdgu.org  
**Institution:** GD Goenka University  
**Program:** BTech Computer Science & Engineering (Cybersecurity)

---

*This project demonstrates practical application of cybersecurity principles in real-world threat analysis scenarios, combining technical expertise with educational outreach to strengthen organizational security posture.*
