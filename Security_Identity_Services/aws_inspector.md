# 🧰 Amazon Inspector

**Purpose:**  
Automated **vulnerability management** service that scans AWS workloads for **known security issues**.

---

## 🔑 What It Does
- Continuously scans **EC2**, **ECR container images**, and **Lambda functions**.  
- Detects **CVE vulnerabilities**, **missing patches**, and **insecure configurations**.  
- Prioritizes findings by **severity** (Critical → Low) using **EPSS + environmental context**.

---

## ⚙️ Key Use Cases
| Scenario | Example Finding |
|-----------|-----------------|
| Unpatched EC2 | Outdated OpenSSL package (CVE detected) |
| Container image | Vulnerable library in ECR image |
| Lambda function | Outdated dependency w/ known CVE |

---

## 🧭 Integrations
- **Security Hub:** Centralized findings  
- **EventBridge:** Automate remediation  
- **Patch Manager:** Apply missing patches  
- **KMS:** Encrypt scan data  
- **AWS Organizations:** Multi-account management  

---

## 💡 Exam Tips
- **Inspector = Vulnerabilities**, **GuardDuty = Threats**, **Macie = Sensitive Data**.  
- Runs **automatically** once enabled — no manual scans.  
- Uses **SSM Agent** on EC2 for data collection.  
- Key phrase: *“Id*
