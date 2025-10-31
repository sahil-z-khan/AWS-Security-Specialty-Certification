# ⚙️ AWS Lambda

**Purpose:**  
Run code **without managing servers** — event-driven, scalable, and pay-per-use compute service.

---

## 🔑 What It Does
- Executes code in response to **events** (e.g., S3 upload, API Gateway call, EventBridge rule).  
- Scales automatically; no provisioning required.  
- Supports **fine-grained IAM roles**, **VPC access**, and **environment variable encryption** with **KMS**.

---

## ⚙️ Key Security Use Cases
| Scenario | Example |
|-----------|----------|
| Automated remediation | Trigger Lambda from **EventBridge** when GuardDuty finds a threat. |
| Data security | Use **KMS** to encrypt environment variables. |
| Least privilege | Each Lambda function should have its own **IAM execution role**. |
| Network control | Run functions inside a **VPC** to limit outbound traffic. |

---

## 🧭 Integrations
- **EventBridge / CloudWatch / S3 / DynamoDB:** Common event sources.  
- **KMS:** Encrypts environment variables and secrets.  
- **Systems Manager Parameter Store / Secrets Manager:** Secure secret retrieval.  
- **Security Hub / GuardDuty:** Automate remediation actions.  

---

## 💡 Exam Tips
- Lambda is **stateless** and **ephemeral** — no data stored between invocations.  
- Enforce **least privilege** on the execution role (`lambda.amazonaws.com`).  
- Use **VPC + SGs + NACLs** to restrict network exposure.  
- *Exam trigger:* “Run code automatically when a threat is detected.” → ✅ **Lambda + EventBridge**

---

**1-Line Summary:**  
> ⚡ *Lambda = Event-driven, serverless compute for automated and secure remediation tasks.*
