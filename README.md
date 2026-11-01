# 🛡️ Windows Successful Login Monitoring Using Wazuh SIEM

## 📌 Project Overview
This is my third hands-on SOC Analyst lab. In this project, I used Wazuh SIEM to monitor and investigate successful Windows login events.

The main objective was to understand how SOC Analysts monitor user authentication activities and investigate login events.

## 🎯 Project Objectives
- Monitor successful Windows login activities.
- Understand Windows Security Event ID 4624.
- Investigate user authentication details.
- Learn basic security event analysis.

## 🛠️ Tools & Technologies
- Wazuh SIEM
- Windows
- Ubuntu Linux
- Oracle VirtualBox

## ⚙️ Lab Implementation
1. Started the Wazuh Server on Ubuntu.
2. Started the Windows virtual machine.
3. Verified the Windows Agent connection.
4. Generated a successful Windows login.
5. Opened Wazuh Threat Hunting.
6. Searched for Event ID 4624.
7. Investigated the available event details.

## 🔍 Detection Query

```text
data.win.system.eventID:4624
```

## 📖 Important Windows Event IDs

| Event ID | Description |
|---|---|
| 4624 | Successful Login |
| 4625 | Failed Login |

## 📸 Screenshots
Add your own screenshots:
- Wazuh Dashboard
- Active Windows Agent
- Event ID 4624 Search Results
- Successful Login Event Details

## 📚 Key Learnings
- Understanding Windows authentication events.
- Monitoring successful login activity.
- Using Wazuh Threat Hunting.
- Investigating login details.
- Understanding the difference between successful and failed logins.

## 📝 Conclusion
This hands-on lab helped me understand Windows authentication monitoring and basic security event investigation using Wazuh SIEM.

**Project Level:** Beginner  
**Project Type:** SOC Analyst Home Lab  
**Status:** Practical lab steps completed
