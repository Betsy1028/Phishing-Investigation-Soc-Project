# Phishing Investigation & Incident Response (SOC Project)

## Overview

This project simulates a real-world phishing investigation performed by a Security Operations Center (SOC) analyst. The goal is to demonstrate how phishing emails are analyzed, documented, and responded to using practical techniques and industry-standard processes.

This is a **hands-on project**, built to reflect the type of work expected in a Tier 1 / Tier 2 SOC role.

---

## What This Project Demonstrates

* Identifying phishing indicators in email content and headers
* Analyzing malicious URLs used for credential harvesting
* Extracting and documenting Indicators of Compromise (IOCs)
* Applying incident response methodology (containment, eradication, recovery)
* Mapping activity to the MITRE ATT&CK framework
* Writing clear, professional SOC documentation

---

## Tools & Platforms Used

* PowerShell (Windows)
* VirusTotal
* URLScan.io
* Email header analysis
* MITRE ATT&CK Framework

---

## Project Structure

```
Phishing-Investigation-SOC/
├── artifacts/
│   └── phishing_email.eml
│
├── analysis/
│   ├── email_header_analysis.md
│   ├── url_analysis.md
│   └── ioc_summary.md
│
├── incident-response/
│   ├── containment.md
│   ├── eradication.md
│   └── recovery.md
│
├── screenshots/
│   ├── virustotal_results.png
│   ├── urlscan_results.png
│   └── sandbox_execution.png
│
└── report/
    └── phishing_incident_report.md
```

---

## Investigation Summary

A phishing email impersonating PayPal was analyzed. The email used urgency, brand impersonation, and a malicious URL designed to harvest user credentials. Multiple red flags were identified during header and URL analysis, confirming the email as malicious.

---

## Incident Response Actions

* Malicious sender and URL blocked
* Phishing email removed from affected mailboxes
* Credentials reset as a precaution
* Security controls reviewed and updated

---

## MITRE ATT&CK Mapping

* T1566.002 – Phishing: Spearphishing Link
* T1056 – Input Capture

---

## Why This Project Matters

This project reflects real SOC workflows and decision-making. It demonstrates technical analysis skills, documentation ability, and an understanding of incident response processes — all critical for entry-level cybersecurity roles.

---

## Disclaimer

This project was created for educational purposes only. All samples are sanitized and do not contain live malware or active phishing infrastructure.
