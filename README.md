# ☁️ CloudSentinel360

**CloudSentinel360** is a cross-cloud integration and observability platform built for modern hybrid enterprises. It unifies deployment, security, and operational metrics across **AWS** and **Azure**, delivering real-time dashboards, compliance tracking, and automated remediation alerts.

Designed for cloud architects, DevOps teams, and compliance officers needing a single pane of glass.

## 📌 Features

- 🔎 **Unified Multi-Cloud Monitoring**:
  - Pulls metrics from AWS CloudWatch and Azure Monitor
  - Real-time visualization via Grafana and Kibana

- 🛡️ **Security & Compliance Checks**:
  - CIS benchmark scanning and anomaly detection
  - Automated alerts and incident response via Lambda/Logic Apps

- 📊 **Centralized Dashboards**:
  - Customizable views per team or service
  - Supports tagging, filtering, and drill-downs

- 🔁 **Auto Remediation**:
  - Event-driven workflows for threat response
  - Auto-scaling, shutdown, or quarantine based on rules

## 🛠️ Tech Stack

- **Monitoring**: AWS CloudWatch, Azure Monitor, Grafana
- **Security**: AWS Config, Azure Defender
- **Automation**: Lambda, Logic Apps
- **Storage**: S3, Azure Blob
- **Orchestration**: Terraform, Bicep

## 🚀 Getting Started

```bash
git clone https://github.com/your-username/cloudsentinel360.git
cd cloudsentinel360
terraform apply -var="env=prod"
