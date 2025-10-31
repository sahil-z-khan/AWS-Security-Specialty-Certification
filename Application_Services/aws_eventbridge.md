# ⚡ Amazon EventBridge

**Purpose:**  
Serverless **event bus** service that routes events between AWS services, SaaS apps, and custom apps for **automation and response**.

---

## 🔑 What It Does
- Captures events from **AWS services** (e.g., GuardDuty, Inspector, Security Hub).  
- Uses **rules** to match events and trigger **targets** like Lambda, SNS, Step Functions, etc.  
- Enables **automated incident response** and **workflow orchestration**.

---

## ⚙️ Key Use Cases
| Scenario | Example |
|-----------|----------|
| Automated remediation | Trigger Lambda when GuardDuty finds a compromised EC2 |
| Security alerts | Send Inspector or Macie findings to an SNS topic |
| Compliance automation | Invoke Step Function to patch or quarantine instances |
| Cross-account events | Centralize security events into a main monitoring account |

---

## 🧭 Integrations
- **GuardDuty / Inspector / Macie / Security Hub:** Emit findings as events  
- **Lambda / Step Functions / SNS / SQS:** Common remediation targets  
- **CloudWatch / Systems Manager:** Trigger runbooks or alarms  
- **Organizations:** Aggregate security events centrally  

---

## 💡 Exam Tips
- **EventBridge = Event-driven automation.**  
- Supports **schema discovery** and **custom event buses.**  
- Focus on **response** (not detection).  
- *Exam trigger:* “Automatically respond to GuardDuty or Security Hub findings.” → ✅ **EventBridge**

---

**1-Line Summary:**  
> ⚙️ *EventBridge = Serverless event bus that automates security responses across AWS services.*
