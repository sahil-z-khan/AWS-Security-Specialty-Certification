# 🛡️ AWS Security Specialty (SCS-002) Study Notes

A structured, concise reference for the **AWS Certified Security – Specialty (SCS-002)** exam.  
Each file summarizes what the service does, common exam triggers, integrations, and key takeaways.

---

## 📁 Directory Overview

### 🧩 Application Services
| File | Description |
|------|--------------|
| [aws_eventbridge.md](./Application_Services/aws_eventbridge.md) | Event-driven automation and remediation bus for AWS services. |

---

### ⚙️ Compute Services
| File | Description |
|------|--------------|
| [aws_lambda.md](./Compute_Services/aws_lambda.md) | Serverless compute for automation and event-based remediation. |

---

### 🧰 Management Tools
| File | Description |
|------|--------------|
| [aws_cloudtrail.md](./Management_Tools/aws_cloudtrail.md) | Logs and audits all API activity across your AWS accounts. |
| [aws_cloudwatch.md](./Management_Tools/aws_cloudwatch.md) | Monitors metrics, logs, and alarms across AWS resources. |
| [aws_config.md](./Management_Tools/aws_config.md) | Tracks configuration changes and evaluates compliance rules. |
| [aws_systems_manager.md](./Management_Tools/aws_systems_manager.md) | Securely manages, patches, and automates AWS resources. |

---

### 🔒 Security & Identity Services
| File | Description |
|------|--------------|
| [aws_guard_duty.md](./Security_Identity_Services/aws_guard_duty.md) | Detects threats using AWS logs, ML, and threat intelligence. |
| [aws_inspector.md](./Security_Identity_Services/aws_inspector.md) | Scans workloads for vulnerabilities (EC2, ECR, Lambda). |
| [aws_macie.md](./Security_Identity_Services/aws_macie.md) | Identifies and protects sensitive data in S3. |
| [aws_security_hub.md](./Security_Identity_Services/aws_security_hub.md) | Centralized security findings and compliance dashboard. |
| [aws_detective.md](./Security_Identity_Services/aws_detective.md) | Investigates and visualizes root causes of security incidents. |

---

## 🧭 How These Services Work Together

```text
GuardDuty   → Detects threats
Inspector   → Finds vulnerabilities
Macie       → Identifies sensitive data
Detective   → Investigates incidents
SecurityHub → Aggregates and scores findings
EventBridge → Automates responses
Lambda      → Executes remediation
SSM         → Manages and patches systems
CloudTrail  → Audits actions
CloudWatch  → Monitors activity
Config      → Evaluates compliance
