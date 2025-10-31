# 🧩 AWS Config

**Purpose:**  
Continuously **monitors, records, and evaluates configurations** of AWS resources for **compliance and change tracking**.

---

## 🔑 What It Does
- Tracks **resource configuration changes** over time (who changed what).  
- Evaluates configurations against **rules** (AWS-managed or custom).  
- Provides **compliance reports** and integrates with **Security Hub**.  
- Helps with **auditing**, **governance**, and **incident response**.

---

## ⚙️ Key Security Use Cases
| Scenario | Example |
|-----------|----------|
| Compliance | Check if all S3 buckets are encrypted or public access is disabled. |
| Governance | Detect if IAM policies are overly permissive. |
| Incident response | Identify when a resource’s security group was modified. |
| Continuous monitoring | Trigger alerts when resources drift from secure baselines. |

---

## 🧭 Integrations
- **Security Hub:** Shares compliance findings.  
- **EventBridge:** Automates remediation workflows.  
- **Systems Manager Automation:** Auto-fix noncompliant resources.  
- **CloudTrail:** Correlate changes to specific users/actions.  
- **SNS / Lambda:** Notify or remediate config violations.

---

## 💡 Exam Tips
- **Config = Resource compliance and change tracking.**  
- **Rules** evaluate configurations; **Conformance Packs** group related rules.  
- Supports **multi-account aggregation**.  
- Logs stored in **S3**, optionally encrypted with **KMS**.  
- *Exam trigger:* “Which service detects if S3 buckets are public or unencrypted?” → ✅ **AWS Config**

---

**1-Line Summary:**  
> 🧾 *Config = Tracks resource changes and evaluates compliance with security and governance rules.*
