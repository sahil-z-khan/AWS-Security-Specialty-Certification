# 🛡️ AWS Security Specialty (SCS-002) Study Notes

A structured collection of concise, exam-focused summaries for key AWS Security services.  
Each file covers what the service does, common exam triggers, and integrations — designed for fast review.

---

## 📁 Directory Overview

### 🧩 Application Services
| File | Description |
|------|--------------|
| [aws_eventbridge.md](./Application_Services/aws_eventbridge.md) | Event-driven automation and security response bus. |

---

### ⚙️ Management Tools
| File | Description |
|------|--------------|
| [aws_systems_manager.md](./Management_Tools/aws_systems_manager.md) | Secure management, patching, and automation for AWS systems. |

---

### 🔒 Security & Identity Services
| File | Description |
|------|--------------|
| [aws_guard_duty.md](./Security_Identity_Services/aws_guard_duty.md) | Continuous threat detection using AWS logs and ML. |
| [aws_inspector.md](./Security_Identity_Services/aws_inspector.md) | Automated vulnerability scanning for EC2, ECR, and Lambda. |
| [aws_macie.md](./Security_Identity_Services/aws_macie.md) | Sensitive data discovery and protection for S3. |
| [aws_security_hub.md](./Security_Identity_Services/aws_security_hub.md) | Centralized dashboard for security findings and compliance. |
| [aws_detective.md](./Security_Identity_Services/aws_detective.md) | Investigate and visualize root causes of security incidents. |

---

## 🧠 How These Services Relate

```text
GuardDuty  → Detects threats
Inspector  → Finds vulnerabilities
Macie      → Identifies sensitive data
Detective  → Investigates incidents
SecurityHub→ Aggregates and scores findings
EventBridge→ Automates security responses
SSM        → Manages, patches, and remediates systems
