# 🧾 AWS CloudTrail

**Purpose:**  
Records and monitors **API activity** across your AWS account for **auditing, compliance, and incident response**.

---

## 🔑 What It Does
- Captures every **API call** made in AWS (who, when, from where, and what).  
- Tracks activity from **AWS Console, CLI, SDKs, and services**.  
- Stores **event history** in CloudTrail console or delivers to **S3**.  
- Integrates with **CloudWatch Logs** and **EventBridge** for alerting and automation.

---

## ⚙️ Key Security Use Cases
| Scenario | Example |
|-----------|----------|
| Auditing | Identify who modified IAM roles or deleted resources. |
| Threat detection | Detect unusual API activity (e.g., login from unfamiliar IP). |
| Compliance | Retain logs for PCI DSS, HIPAA, or SOC 2 reporting. |
| Incident investigation | Correlate events with GuardDuty or Detective findings. |

---

## 🧭 Integrations
- **CloudWatch Logs:** Stream CloudTrail events for metric filters and alerts.  
- **GuardDuty:** Uses CloudTrail data for threat detection.  
- **Detective:** Analyzes CloudTrail logs for root-cause investigation.  
- **Security Hub:** Aggregates and scores activity findings.  
- **EventBridge:** Automates response to specific API actions.

---

## 💡 Exam Tips
- **CloudTrail = Who did what, when, and from where.**  
- **Enabled by default** for the last 90 days of event history (management events).  
- Create **Organization Trail** for multi-account logging.  
- Encrypt logs with **KMS**, store in **S3**, and restrict access via **Bucket Policy + IAM**.  
- *Exam trigger:* “Need to audit API actions across all AWS accounts.” → ✅ **CloudTrail**

---

**1-Line Summary:**  
> 🧠 *CloudTrail = Records all API activity for auditing, compliance, and forensic analysis.*
