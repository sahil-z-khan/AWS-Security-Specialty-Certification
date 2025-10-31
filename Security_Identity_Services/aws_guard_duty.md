# 🛡️ AWS GuardDuty

**Purpose:**  
Continuous **threat detection** for AWS accounts, workloads, and data — no agents required.

---

## 🔑 What It Does
- Monitors for **malicious or unauthorized activity**.  
- Analyzes **CloudTrail**, **VPC Flow Logs**, and **DNS logs**.  
- Uses **ML + threat intelligence** to detect anomalies.

---

## ⚙️ Key Use Cases
| Scenario | Example Finding |
|-----------|-----------------|
| Compromised EC2 | Instance communicating with malware IP |
| IAM misuse | Unusual API calls or privilege escalation |
| Data exfiltration | Unusual S3 or DNS activity |
| Reconnaissance | Port scanning or probing activity |

---

## 🧭 Integrations
- **Security Hub:** Centralized alert view  
- **EventBridge:** Automate remediation  
- **CloudWatch:** Monitor findings  
- **AWS Detective:** Investigate root cause  

---

## 💡 Exam Tips
- **Detection, not prevention** → GuardDuty *alerts*, doesn’t block.  
- **No setup or agents** → Just enable per region (creates a *detector*).  
- Findings classified by **severity** (Low, Medium, High).  
- **Cross-account setup** → Use *GuardDuty Administrator* account to manage others.  
- Common Q: “Which service detects unusual API or network activity?” → ✅ **GuardDuty**

---

**1-Line Summary:**  
> 🕵️ *GuardDuty = Always-on threat detection for AWS using logs, ML, and intel feeds.*