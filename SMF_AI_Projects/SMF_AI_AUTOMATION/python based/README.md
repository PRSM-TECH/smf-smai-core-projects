# 📬 Ethical Email Automation Bot

This project automates Gmail email classification and response with a strong focus on **ethical decision-making**, using both:

* ✅ Python-based approach (code logic)
* ✅ UIPath-based approach (no-code RPA)

---

## 🔍 Objective

Automatically scan incoming Gmail messages, filter ethically, categorize by intent, and send a response **only when ethically valid**, while maintaining full transparency via logging.

---

## 🧱 Versions Implemented

### 1️⃣ Python Version (Manual Logic)

* Uses Gmail API (`google-api-python-client`)
* Custom ethical logic: blocklist, one-reply-per-sender
* Sends reply using `smtplib`
* Logs to `reply_log.json`

📁 File: `ethical_email_automation.py`
📄 Case Study: `Ethical_Email_Automation_Case_Study.docx`

### 2️⃣ UIPath Version (No-Code)

* Gmail + SMTP activities
* Drag-and-drop logic using `Switch`, `Regex`, `Write Line`
* Logs to Excel

📄 Case Study: `UIPath_Email_Automation_Case_Study.docx`

---

## 🛡️ Ethical Safeguards Implemented

* ❌ Avoid replies to: `noreply@`, `promo`, `marketing`, `newsletter`
* ✅ Limit replies: one per sender per session
* 📒 Maintain logs for every action (JSON or Excel)

---

## 🛠️ Tools & Libraries

| Tool       | Used For                 |
| ---------- | ------------------------ |
| Python     | Core scripting           |
| Gmail API  | Reading/writing messages |
| SMTP       | Sending replies          |
| UIPath     | No-code automation       |
| Excel/JSON | Action logs              |

---

## 🧠 Use Cases

* Ethical business automation
* Digital minimalism & mindful responses
* RPA job readiness + AI ethics alignment

---

## 📁 Folders

* `python_version/` → Python script + log file
* `uipath_version/` → XAML file (UIPath workflow) + Excel log sample
* `docs/` → Case studies, README, and audit notes

---

> Inspired by the SoulMindFusion mission — ensuring technology serves humanity with clarity, care, and consent.
