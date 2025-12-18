\# Email Header Analysis



\## 📌 Overview

This analysis focuses on identifying suspicious indicators within the email headers of a suspected phishing email impersonating PayPal.



---



\## 🔍 Header Fields Reviewed



\### From Address


- Domain uses a **lookalike character** (capital “I” instead of lowercase “l”)
- Common impersonation technique used in phishing campaigns

---

### Received Header

- Sending server is listed as **unknown**
- IP address is external and not associated with PayPal infrastructure
- Indicates spoofed sender information

---

### Message-ID

- Message-ID domain does not match legitimate PayPal domains
- Often used to bypass basic email filtering

---

### SPF / DKIM / DMARC
- No SPF, DKIM, or DMARC authentication results present
- Legitimate PayPal emails typically pass all three checks
- Absence increases likelihood of spoofing

---

## 🚩 Red Flags Identified
- Brand impersonation (PayPal)
- Lookalike domain usage
- Suspicious sending IP
- Missing authentication results

---

## 🧠 Analyst Assessment
Based on header inconsistencies and authentication failures, this email is classified as **malicious phishing**.

---

## 🧩 MITRE ATT&CK Mapping
- **T1566.002 – Phishing: Spearphishing Link**

---

## ✅ Conclusion
The analyzed email exhibits multiple indicators consistent with phishing attacks and should be blocked and reported within the organization.
