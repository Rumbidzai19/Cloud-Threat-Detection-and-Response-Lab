# ☁️ Cloud Threat Detection & Response Lab (AWS Free Tier)

This hands-on lab simulates real-world SOC analyst activities in a cloud environment using **AWS Free Tier**. It demonstrates cloud log monitoring, threat detection, alerting, and incident response using **Amazon GuardDuty**, **CloudTrail**, and **SNS**.

---

## 🔍 Key Features

- ✅ AWS GuardDuty threat detection (e.g., brute-force login, vulnerable ports)
- ✅ CloudTrail log analysis for user activity monitoring
- ✅ Alerting setup with CloudWatch Alarms and Amazon SNS
- ✅ Step-by-step simulations of common cloud security incidents
- ✅ Ready-to-use incident response playbooks in Markdown format

---

## 🛠️ Tech Stack

- **Cloud Services**: EC2, S3, IAM, CloudTrail, GuardDuty, CloudWatch, SNS
- **Formats**: Markdown (documentation), JSON (log samples)
- **Tools Used**: AWS Console, AWS CLI, draw.io (architecture), VS Code

---

## 📁 Project Structure

| Folder | Description |
|--------|-------------|
| `incident-playbooks/` | Response procedures for simulated threats |
| `logs-samples/` | Sample logs from CloudTrail and GuardDuty |
| `setup-guide/` | Step-by-step deployment instructions |
| `alerting-setup/` | SNS alert configuration with CloudWatch |
| `architecture-diagram.png` | Visual representation of the lab setup |

---

## 🚨 Simulated Threat Scenarios

- 🔓 Public S3 bucket exposure
- 🔐 Multiple IAM login failures (Brute-force)
- 🔥 Open SSH port detection on EC2 instance

---

## 📣 Alerting Setup

- **CloudWatch Alarms** detect suspicious behavior
- **SNS** sends real-time alerts via email or SMS
- Simulated threats trigger alerts that mimic real SOC workflows

---

## ▶️ How to Use

1. **Clone the repository**
2. Navigate to the `setup-guide/` and follow the instructions
3. Deploy cloud resources and simulate threats
4. Use `incident-playbooks/` to walk through detection and response steps

---

## 🖼 Architecture Diagram

![Architecture Diagram](architecture-diagram.png)

---

## 📄 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and share.

---

> 🔐 Perfect for SOC Analyst beginners and cybersecurity students looking to understand cloud-based detection and response!

