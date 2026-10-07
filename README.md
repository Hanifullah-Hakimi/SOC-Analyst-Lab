# 🛡️ SOC Analyst Lab

## 📌 Overview

Hands-on SOC Analyst home lab designed to practice security monitoring, log analysis, alert investigation, threat detection, and incident response in a controlled environment.

This lab documents my progression toward becoming a SOC Analyst and includes real hands-on investigations using Windows, Linux, networking tools, and SIEM technologies.

## 🛠️ Technologies & Tools

- Splunk SIEM
- Windows 10/11
- Windows Server
- Linux / Ubuntu
- PowerShell
- Wireshark
- Nmap
- Active Directory
- VirtualBox
- GitHub

## 🔍 SOC Skills Practiced

- Security Monitoring
- Alert Triage
- Log Analysis
- Incident Investigation
- Incident Response
- IOC Investigation
- Threat Detection
- Windows Event Log Analysis
- Linux Log Analysis
- Network Traffic Analysis
- Authentication Investigation
- PowerShell Investigation
- Detection Rule Development

## 🧪 Lab Environment

```text
                    SOC Analyst Lab
                          │
            ┌─────────────┴─────────────┐
            │                           │
       Windows VM                    Linux VM
            │                           │
     Windows Event Logs             Linux Logs
            │                           │
            └─────────────┬─────────────┘
                          │
                       Splunk
                          │
                   ┌──────┴──────┐
                   │             │
                Detection     Investigation
                   │             │
                   └──────┬──────┘
                          │
                  Incident Response
