# 🕵️ Amazon Detective

**Purpose:**  
Helps **analyze, investigate, and identify root causes** of potential security incidents.

---

## 🔑 What It Does
- Automatically collects and correlates data from **CloudTrail**, **VPC Flow Logs**, and **GuardDuty findings**.  
- Builds **graph-based visualizations** showing relationships between users, IPs, and resources.  
- Simplifies **incident investigation** after a GuardDuty alert.

---

## ⚙️ Key Use Cases
| Scenario | Example |
|-----------|----------|
| Investigate GuardDuty finding | Trace EC2’s network activity and IAM user actions |
| Analyze unusual API calls | Visualize CloudTrail history by user or IP |
| Correlate suspicious behavior | Identify patterns across accounts and regions |

---

## 🧭 Integrations
- **GuardDuty:** Launch detailed investigation from a finding  
- **Security Hub:** Open findings in Detective  
- **CloudTrail + VPC Flow Logs:** Source data  
- **EventBridge:** Automate alert-to-investigation workflows  

---

## 💡 Exam Tips
- **Detective = Investigation**, **GuardDuty = Detection**.  
- No agents or manual setup — data collected automatically.  
- Graphical console for deep dives — not real-time alerts.  
- *Exam trigger:* “Which service helps analyze the cause of a GuardDuty alert?” → ✅ **Detective**

---

**1-Line Summary:**  
> 🧩 *Detective = Visual investigation tool to find the root cause of suspicious activity detected by GuardDuty.*
