# 🤖 AI-Powered Consulting Presentation Automation Tool

An enterprise-grade automation solution built to transform raw consulting workshop data into fully formatted, client-ready PowerPoint presentations. Features automated data processing, notification workflows, cloud integration, and modular VBA script execution.

---

## 📌 Project Overview

In consulting workflows, manually transferring insights from data sheets to slides is time-consuming and error-prone. This project automates the entire lifecycle:
1. **Trigger & Notification**: Uploading raw data to cloud storage automatically notifies key stakeholders via email.
2. **Data Extraction & Structuring**: Parses structured workshop inputs (findings, recommendations, priority matrices, next steps).
3. **Slide Generation**: Executes VBA automation in PowerPoint to programmatically build slides, format headers, create dynamically styled tables, and purge raw layout placeholders.

---

## ⚙️ Automation Workflow

[ Raw Workshop Data Uploaded ]
│
▼
[ Cloud Folder (Drive/SharePoint) ]
│
▼ (Webhook / Watcher Trigger)
[ Automated Notification Workflow ] ──► (Generates Action-Required Email)
│
▼
[ Excel Data Ingestion (.xlsm) ]
│
▼
[ VBA Presentation Engine ] ──► (Builds & Formats PPT Slides Dynamically)


---

## 📁 Repository Structure

├── src/
│   └── Sheet3.cls                        # Core VBA Automation Module
├── Data/
│   └── WorkshopData1.xlsm               # Macro-Enabled Data Source
├── Docs/
│   ├── workflow_scenario.png            # Automation Scenario Architecture
│   └── email_notification.png           # Automated Email Notification Trigger
└── README.md                            # Technical Documentation


---

## ✨ Key Features

- **Dynamic Table & Slide Generation**: Programmatically calculates rows and columns from Excel sheets and builds formatted tables inside PowerPoint slides.
- **Automatic Layout Sanitization**: Purges default layout placeholders prior to populating slide elements for clean formatting.
- **Workflow Automation**: Integrated cloud triggers to dispatch instant notifications (`New Workshop Data Received - Action Required`) to operational teams upon new file uploads.
- **Modular VBA Architecture**: Separate subroutines for layout handling, slide assembly, and text formatting.

---

## 🛠️ Tech Stack

- **Programming/Scripting**: VBA (Visual Basic for Applications)
- **Applications**: Microsoft Excel, Microsoft PowerPoint
- **Cloud Automation**: Make.com / Microsoft Power Automate, Google Drive, Gmail
- **Version Control**: Git & GitHub

---

## 👤 Author

**Rojeh Fady (Roger Fady)**
