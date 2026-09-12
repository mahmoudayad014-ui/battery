# 🔋 Battery Monitor with Python

A simple Python-based **Battery Monitoring and Low Battery Notification System**.

This project continuously monitors the laptop battery level and charger status. When the battery level drops to **30% or below** while the charger is disconnected, the application sends a Windows desktop notification.

---

## 🚀 Project Overview

The Battery Monitor automatically checks:

- 🔋 Current battery percentage
- 🔌 Charger connection status
- ⚠️ Low battery condition
- 🔔 Windows desktop notifications

The application is designed as a simple practical Python automation project.

---

## 🛠️ Technologies Used

- Python
- `psutil`
- `winotify`
- Windows Notifications
- Python Virtual Environment

---

## 📁 Project Structure

```text
Battery-Monitor/
│
├── battery.py
├── requirements.txt
└── README.md
