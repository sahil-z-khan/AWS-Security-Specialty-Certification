# 📊 Amazon CloudWatch

**Purpose:**  
Centralized **monitoring and observability** service for metrics, logs, and alarms across AWS resources and applications.

---

## 🔑 What It Does
- Collects **metrics**, **logs**, and **events** from AWS services and custom applications.  
- Creates **alarms** to trigger actions (SNS, Lambda, EventBridge).  
- Provides **dashboards** for real-time visibility and performance tracking.  
- Supports **anomaly detection** and **metric math** for smarter alerting.

---

## ⚙️ Key Security Use Cases
| Scenario | Example |
|-----------|----------|
| Security alerting | Alarm when GuardDuty or SSM reports a high-severity finding. |
| Log monitoring | Analyze CloudTrail or VPC Flow Logs via CloudWatch Logs. |
| Compliance | Track metrics like API failures or unauthorized access attempts. |
| Automated response | Trigger Lambda or EventBridge workflow from an alarm. |

---

## 🧭 Integrations
- **CloudTrail:** Sends API logs for monitoring unusual activity.  
- **GuardDuty / Inspector / Macie:** Send findings to CloudWatch for alerting.  
- **EventBridge:** Routes alarms to automated remediation workflows.  
- **Systems Manager:** Stores and forwards command/session logs.  
- **SNS:** Sends notifications on alarm conditions.

---

## 💡 Exam Tips
- **CloudWatch = Monitoring**, not data auditing (that’s **CloudTrail**).  
- Use **metric filters** on CloudWatch Logs to detect security events.  
- All **Session Manager** and **Run Command** logs can be stored here.  
- *Exam trigger:* “Detect or alert on specific API or system behavior.” → ✅ **CloudWatch**

---

**1-Line Summary:**  
> 📈 *CloudWatch = Central monitoring, logging, and alerting system for AWS resources and security events.*
