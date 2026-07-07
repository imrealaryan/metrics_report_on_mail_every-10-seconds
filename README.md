# ☁️ Multi-Cloud Resource Monitoring & Alerting Tool

<p align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&pause=1000&color=00C7FF&center=true&vCenter=true&width=850&lines=Python+Cloud+Monitoring+Tool;AWS+%7C+Azure+%7C+Google+Cloud+%7C+Local;CPU+%7C+Memory+%7C+Disk+%7C+Network+Monitoring;Email+%7C+Slack+%7C+Microsoft+Teams+Alerts" />

</p>

<p align="center">

<img src="https://img.shields.io/badge/Python-3.9+-blue?logo=python">
<img src="https://img.shields.io/badge/AWS-Supported-orange?logo=amazonaws">
<img src="https://img.shields.io/badge/Azure-Supported-blue?logo=microsoftazure">
<img src="https://img.shields.io/badge/GCP-Supported-red?logo=googlecloud">
<img src="https://img.shields.io/badge/License-MIT-success">

</p>

---

## 📖 Overview

This project is a **Unified Multi-Cloud Monitoring Tool** built in Python that automatically detects whether it is running on:

- ☁ AWS EC2
- ☁ Microsoft Azure VM
- ☁ Google Cloud Platform VM
- 💻 Local Machine

It continuously monitors system resources and instantly sends alerts whenever configured thresholds are exceeded.

---

# ✨ Features

✅ Automatic Cloud Detection

✅ CPU Monitoring

✅ RAM Monitoring

✅ Disk Usage Monitoring

✅ Network Traffic Monitoring

✅ Network Error Detection

✅ Email Notifications

✅ Slack Notifications

✅ Microsoft Teams Notifications

✅ Rotating Log Files

✅ Cross Platform

✅ Environment Variable Configuration

---

# 🏗 Architecture

```text
              +----------------------+
              |  Python Monitoring   |
              +----------+-----------+
                         |
        +----------------+----------------+
        |                |                |
     AWS EC2         Azure VM         GCP VM
        |                |                |
        +----------------+----------------+
                         |
                 Collect System Metrics
                         |
              CPU | RAM | Disk | Network
                         |
             Threshold Evaluation Engine
                         |
        +-----------+------------+-------------+
        |           |            |
      Email      Slack       MS Teams
```

---

# 🎥 Workflow

<p align="center">

<img src="https://media.giphy.com/media/coxQHKASG60HrHtvkt/giphy.gif" width="750">

</p>

---

# 📊 Monitored Metrics

| Metric | Supported |
|---------|-----------|
| CPU Usage | ✅ |
| Memory Usage | ✅ |
| Disk Usage | ✅ |
| Network Traffic | ✅ |
| Network Errors | ✅ |
| Hostname | ✅ |
| Cloud Provider | ✅ |

---

# 🌍 Supported Platforms

| Platform | Status |
|----------|--------|
| Local Machine | ✅ |
| AWS EC2 | ✅ |
| Azure VM | ✅ |
| Google Cloud VM | ✅ |

---

# 🚀 Installation

Clone repository

```bash
git clone https://github.com/yourusername/cloud-monitor.git

cd cloud-monitor
```

Install dependencies

```bash
pip install psutil requests boto3 azure-identity azure-mgmt-compute google-cloud-compute
```

---

# ▶ Usage

Run once

```bash
python cloud_monitor.py --once
```

Continuous monitoring

```bash
python cloud_monitor.py
```

Custom interval

```bash
python cloud_monitor.py --interval 20
```

---

# ⚙ Environment Variables

```bash
CPU_THRESHOLD=80
RAM_THRESHOLD=80
DISK_THRESHOLD=85

CHECK_INTERVAL=10

SMTP_SERVER=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=your_email
SMTP_PASSWORD=your_password

ALERT_EMAIL_TO=admin@example.com

SLACK_WEBHOOK_URL=https://hooks.slack.com/...
TEAMS_WEBHOOK_URL=https://...
```

---

# 📁 Project Structure

```
cloud-monitor/
│
├── cloud_monitor.py
├── README.md
├── requirements.txt
└── logs/
```

---

# 📜 Logging

The application maintains

- Console Logs
- Rotating Log Files
- Alert Logs

---

# 📨 Alert Channels

- Email
- Slack
- Microsoft Teams

---

# 🔐 Security

Never hardcode credentials.

Always use:

- Environment Variables
- Secret Manager
- GitHub Secrets
- Azure Key Vault
- AWS Secrets Manager

---

# 🛠 Tech Stack

- Python
- psutil
- requests
- boto3
- Azure SDK
- Google Cloud SDK
- SMTP
- Slack Webhooks
- Microsoft Teams Webhooks

---

# 📈 Future Enhancements

- Docker Support

- Kubernetes Monitoring

- Prometheus Integration

- Grafana Dashboard

- REST API

- Web Dashboard

- SMS Alerts

- Telegram Alerts

- WhatsApp Alerts

- AI-Based Predictive Monitoring

---

# 🤝 Contributing

Contributions are welcome!

Fork the repository

Create a feature branch

Commit your changes

Push your branch

Create a Pull Request

---

# 📄 License

MIT License

---

# 👨‍💻 Author

**Aryan Jain**

Cloud Support Associate

AWS • Azure • GCP • Python • Cloud Automation

⭐ If you found this project useful, don't forget to star the repository!
