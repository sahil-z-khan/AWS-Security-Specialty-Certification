# 🔍 Amazon Macie

**Purpose:**  
Automatically **discover, classify, and protect sensitive data** (like PII/PHI) stored in **Amazon S3**.

---

## 🔑 What It Does
- Scans S3 buckets using **ML + pattern matching**.  
- Detects **personally identifiable info (PII)**, credentials, and secrets.  
- Flags **public, unencrypted, or misconfigured** buckets.

---

## ⚙️ Key Use Cases
| Scenario | Example Finding |
|-----------|-----------------|
| PII exposure | S3 object with credit card or SSN |
| Public bucket | Bucket accessible to “Everyone” |
| Compliance | Identify sensitive data for GDPR, HIPAA, etc. |

---

## 🧭 Integrations
- **Security Hub:** Centralize findings  
- **EventBridge:** Automate alerts or remediation  
- **KMS:** Ensure S3 encryption  
- **CloudWatch:** Monitor scan metrics  

---

## 💡 Exam Tips
- **Macie = S3 + Sensitive Data** (always associate these two).  
- Focuses on **data privacy**, not threat or vulnerabilities.  
- Findings rated by severity and data type.  
- Detects **sensitive data patterns** → not malware or CVEs.  
- Common Q: “Which service finds exposed PII in S3?” → ✅ **Macie**

---

**1-Line Summary:**  
> 🔒 *Macie = Automated data discovery and PII protection for S3 buckets.*
