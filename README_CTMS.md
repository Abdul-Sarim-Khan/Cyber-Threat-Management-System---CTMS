
# 🔐 Cyber Threat Management System (CTMS)

A lightweight, real-time Human Intrusion Detection System (HIDS) for Windows-based personal computers.

This project helps individual users monitor and secure their systems by detecting suspicious login activity (e.g., brute force attacks, account lockouts) through real-time analysis of Windows Event Logs. It sends automated email alerts when multiple failed login attempts are detected and provides an intuitive PyQt dashboard for live log visualization.

---

## 🚀 Features
- 📜 **Log Extraction** from Windows Security Event Logs using PowerShell  
- 🗄️ **SQL Server Storage** for structured login event logging  
- 🧠 **Threshold-Based Detection** (≥5 failed logins in 10 minutes)  
- 📬 **Email Alerting** via SQL Server Database Mail  
- 📊 **PyQt Dashboard** for real-time monitoring (successful & failed logins)  
- 🔐 **Personal SIEM Alternative** – no need for expensive enterprise tools

---

## 📌 Use Case Example
> Imagine locking your laptop in a public library and stepping away. If someone attempts to break into your system, CTMS instantly detects the intrusion attempt and alerts you via email — protecting your device before damage is done.

---

## 🛠️ Tech Stack
- **Python** (PyQt5 for GUI)
- **PowerShell** (Log extraction)
- **SQL Server** (Storage & detection)
- **T-SQL** (Threat correlation)
- **Database Mail** (Email alerts)

---

## 🔮 Future Enhancements
- Network-based login monitoring (RDP, SMB)  
- Behavior-based anomaly detection  
- Threat intelligence integration  
- SMS alerting via Twilio

---

## 📄 License
MIT License
