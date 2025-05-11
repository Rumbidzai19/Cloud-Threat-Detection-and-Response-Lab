# Cloud-Threat-Detection-and-Response-Lab
cloud-threat-detection-lab/
├── README.md
├── architecture-diagram.png
├── incident-playbooks/
│   ├── s3-public-access.md
│   ├── brute-force-login.md
│   └── exposed-ssh-port.md
├── logs-samples/
│   ├── cloudtrail-log-sample.json
│   └── guardduty-finding-sample.json
├── alerting-setup/
│   └── cloudwatch-sns-setup.md
├── setup-guide/
│   ├── aws-setup.md
│   ├── enable-guardduty.md
│   ├── enable-cloudtrail.md
│   └── simulate-threats.md
└── LICENSE


# ☁️ Cloud Threat Detection & Response Lab (AWS Free Tier)

This project simulates real-world SOC analyst activities in a cloud environment using AWS Free Tier. It demonstrates cloud log monitoring, threat detection, alerting, and incident response using Amazon GuardDuty, CloudTrail, and SNS.

## 🔍 Features

- AWS GuardDuty threat detection (unauthorized access, vulnerable ports)
- CloudTrail log analysis for user activities
- CloudWatch alerting with Amazon SNS
- Hands-on simulation of common cloud security incidents
- Markdown-based Incident Response Playbooks

## 🛠️ Tech Stack

- **AWS Services**: EC2, S3, IAM, CloudTrail, GuardDuty, CloudWatch, SNS
- **Languages**: Markdown (documentation), JSON (logs)
- **Tools**: AWS Console, CLI, draw.io (diagram), VS Code

## 📁 Folder Overview

| Folder | Description |
|--------|-------------|
| `incident-playbooks/` | Response plans for detected threats |
| `logs-samples/` | Example CloudTrail and GuardDuty logs |
| `setup-guide/` | Step-by-step instructions to recreate the lab |
| `alerting-setup/` | Configuring CloudWatch to send SNS alerts |
| `architecture-diagram.png` | Visual overview of the lab setup |

## Simulated Threats

- Public S3 bucket exposure
-  Multiple failed login attempts (IAM)
-  Open SSH ports on EC2

##  Alerting

Configured CloudWatch Alarms trigger SNS notifications (email/SMS) upon detecting suspicious activities.

##  How to Use

1. Clone the repo
2. Follow the `setup-guide/` to deploy the lab in AWS
3. Simulate threats manually or using automated scripts
4. Review `incident-playbooks/` to analyze and respond

##  Screenshot

![Architecture Diagram](architecture-diagram.png)

##  License

MIT License
