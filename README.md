# Incident-Response-Security-Breach-Simulation
A practical cybersecurity lab project demonstrating incident response procedures including security breach simulation, log analysis, containment, threat removal, system restoration, and preventive security improvements using Linux.
# Incident Response & Security Breach Simulation

## 📌 Project Overview

This project demonstrates a complete Incident Response lifecycle through a simulated security breach scenario.  
The lab focuses on detecting, analyzing, containing, and preventing security incidents using Linux system tools.

---

## 👨‍🎓 Student Information

- **Name:** Ch Rohit Kumar  
- **University:** Aditya University  
- **Domain:** Cybersecurity  
- **Duration:** January 2026 – April 2026  

---

## 🎯 Objective

To simulate a basic security incident such as repeated failed login attempts or unauthorized access and perform a structured incident response process.

---

## 🛠 Tools & Technologies Used

- Kali Linux / Ubuntu
- SSH
- journalctl (Log Monitoring)
- UFW (Firewall)
- Fail2Ban
- Linux system utilities

---

## 🔎 Project Steps

### 1️⃣ Security Incident Simulation
- Generated repeated failed SSH login attempts
- Observed authentication logs

### 2️⃣ Log Analysis
- Analyzed system logs using:
  ```bash
  sudo journalctl | grep "Failed password"
