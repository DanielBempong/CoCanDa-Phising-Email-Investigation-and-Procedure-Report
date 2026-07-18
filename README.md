# CoCanDa-Phising-Email-Investigation-and-Procedure-Report

# 📧 Phishing Email Investigation | SOC Incident Response Case Study

## Overview

This repository showcases a hands-on **phishing email investigation** and  **Procedures** performed using industry-standard Digital Forensics and Incident Response (DFIR) methodologies. The objective was to analyze a suspicious email, determine whether it posed a credible threat, identify Indicators of Compromise (IOCs), validate email authentication mechanisms, and document the investigation following Security Operations Center (SOC) best practices.

The investigation involved examining raw email headers, decoding Base64-encoded content, verifying file signatures, inspecting email attachments, and mapping attacker behavior to the **MITRE ATT&CK Framework**. Through systematic forensic analysis, the email was determined to be a phishing attempt leveraging a spoofed sender, failed SPF authentication, a mismatched Reply-To address, and a disguised attachment designed to deceive the recipient.

No evidence indicated successful malware execution or endpoint compromise; however, the investigation demonstrates the structured workflow SOC analysts use to identify, validate, and respond to email-based threats.

---

## Objectives

* Investigate a suspected phishing email.
* Analyze raw email headers and metadata.
* Validate SPF authentication results.
* Decode Base64-encoded email content.
* Perform file signature analysis to detect disguised files.
* Identify and document Indicators of Compromise (IOCs).
* Assess the potential impact on the target.
* Map attacker behavior to the MITRE ATT&CK framework.
* Produce a professional SOC incident report with findings and recommendations.

---

## Skills Demonstrated

* Phishing Email Analysis
* Email Header Analysis
* Digital Forensics
* Incident Response
* IOC Identification
* File Signature Analysis
* Threat Intelligence
* MITRE ATT&CK Mapping
* Security Documentation
* Root Cause Analysis
* Threat Assessment
* Security Reporting

---

## Tools Used

* **CyberChef** – Decoded Base64-encoded email content and extracted embedded data.
* **HxD Hex Editor** – Verified file signatures (magic bytes) to determine true file types.
* **Notepad++** – Reviewed raw email headers and message source.
* **Gary Kessler File Signature Database** – Verified actual file types and detected disguised attachments.
* **VirusTotal** *(if applicable)* – Checked files, URLs, and hashes against known threat intelligence.
* **MITRE ATT&CK Framework** – Mapped attacker tactics and techniques.

---

## Key Findings

* Identified a spoofed sender address.
* Detected an SPF authentication failure.
* Analyzed a suspicious PDF attachment.
* Verified that one attachment had a disguised file type using file signature analysis.
* Extracted multiple Indicators of Compromise (IOCs).
* Identified the originating IP address and spoofing infrastructure.
* Determined the attack aligns with **MITRE ATT&CK T1566.001 – Spearphishing Attachment**.
* Found no evidence of successful endpoint compromise.

---

## Repository Contents

* **Phishing Email Investigation Report**
* Supporting Evidence
* Investigation Screenshots
* Indicators of Compromise (IOCs)
* MITRE ATT&CK Mapping
* Investigation Methodology
* References and Supporting Resources

---

## Learning Outcomes

This project strengthened my practical skills in phishing investigations, digital forensics, incident response, email authentication analysis, and threat hunting. It demonstrates my ability to analyze suspicious emails, validate forensic evidence, document findings, and communicate technical information in a structured, professional format aligned with real-world SOC operations.

This repository is part of my cybersecurity portfolio and reflects my commitment to continuously developing hands-on SOC, DFIR, and threat detection skills while applying industry best practices to real-world security investigations.

