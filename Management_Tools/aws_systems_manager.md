# 🧰 AWS Systems Manager (SSM) – SCS-002 Quick Reference

**Purpose:**  
Centrally manage, patch, and secure EC2/on-prem resources **without SSH or open ports**.

---

## 🔑 Core Features & Exam Focus

| Feature | What It Does | Security Focus / Exam Tip |
|----------|---------------|----------------------------|
| **Session Manager** | Secure EC2 access via console/CLI | No SSH keys, IAM-controlled, CloudTrail/CloudWatch logs |
| **Patch Manager** | Auto patch EC2s | Maintains compliance, integrates w/ Security Hub |
| **Parameter Store** | Store secrets/configs | Use `SecureString + KMS`, no hardcoded creds |
| **Run Command** | Run shell/PowerShell remotely | No manual login, all actions logged |
| **Inventory / State Manager** | Track + enforce configs | Ensures compliance, detects drift |
| **Fleet Manager** | GUI for EC2 mgmt | Web-based mgmt, same IAM/logging controls |
| **Automation** | Runbooks/workflows | Auto-remediate noncompliance (e.g. patching) |

---

## 🧭 Integrations

- **CloudTrail:** Audit SSM actions  
- **CloudWatch Logs:** Store command/session logs  
- **KMS:** Encrypt SecureStrings + sessions  
- **Security Hub:** Patch compliance findings  
- **IAM:** Fine-grained access control  

---

## 🧠 Common Exam Scenarios

| Scenario | Feature |
|-----------|----------|
| Secure EC2 access (no SSH) | **Session Manager** |
| Store encrypted DB password | **Parameter Store (SecureString + KMS)** |
| Auto patch all EC2s | **Patch Manager** |
| Detect unpatched software | **Inventory + State Manager** |
| Auto fix noncompliant instances | **Automation Runbook** |

---

### 💡 Key Tips
- No SSH/RDP → **Session Manager**  
- No plaintext creds → **Parameter Store + KMS**  
- Patch regularly → **Patch Manager**  
- Audit everything → **CloudTrail + CloudWatch**  
- Compliance → **State Manager + Security Hub**

---

**1-Line Summary:**  
> 🔒 *SSM = Secure, automated, auditable management for AWS resources — replaces SSH & manual ops.*
