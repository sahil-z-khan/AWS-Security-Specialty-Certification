# 🧮 AWS Security Hub

**Purpose:**  
Centralized **security and compliance dashboard** that aggregates findings from multiple AWS and partner services.

---

## 🔑 What It Does
- Collects, normalizes, and prioritizes findings from:  
  - **GuardDuty** (threats)  
  - **Inspector** (vulnerabilities)  
  - **Macie** (sensitive data)  
  - **IAM Access Analyzer**, **Config**, and 3rd-party tools  
- Maps results to frameworks (e.g., **CIS**, **PCI DSS**).  
- Provides an overall **security posture score**.

---

## ⚙️ Key Use Cases
| Scenario | Example |
|-----------|----------|
| Centralize alerts | View GuardDuty, Inspector, and Macie findings in one place |
| Compliance checks | CIS AWS Foundations Benchmark results |
| Automate response | Send findings to EventBridge for remediation workflows |

---

## 🧭 Integrations
- **GuardDuty, Inspector, Macie:** Ingest findings  
- **Config:** Compliance rules  
- **EventBridge:** Automate fixes  
- **CloudWatch:** Monitor metrics  
- **Organizations:** Multi-account view  

---

## 💡 Exam Tips
- **Security Hub = Aggregator**, not detector.  
- Findings use **AWS Security Finding Format (ASFF)**.  
- Focus on **compliance visibility + centralized management**.  
- *Exam trigger:* “Single pane of glass for AWS security findings.” → ✅ **Security Hub**

---

**1-Line Summary:**  
> 🧠 *Security Hub = Central dashboard that aggregates and prioritizes all AWS security findings and compliance results.*
