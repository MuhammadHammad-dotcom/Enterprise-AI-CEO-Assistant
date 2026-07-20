
# Enterprise AI CEO Assistant 🚀

An end-to-end intelligent automation workflow built using **n8n** and **Google Gemini AI**. This project acts as a digital Chief of Staff, designed to seamlessly handle, categorize, and process executive-level communications without manual friction.
---
## 💡 What Problem Does This Solve?
Managing a CEO's or executive's inbox is overwhelming. Sorting sales leads, financial reports, research requests, and general queries takes up valuable hours. This automated assistant steps in to instantly analyze incoming emails, route them to the appropriate department or action, log the transaction in Google Sheets, and draft or send professional, context-aware replies.
---
## ⚙️ How It Works (Workflow Architecture)

1. **Intake & Understand:** 
   - Triggers automatically the moment an email lands in the inbox.
   - Extracts the core message body, sender details, and normalizes data for AI processing.

2. **Route & Act (AI-Powered):**
   - The **Google Gemini AI Agent** reads and evaluates the intent of the email.
   - Automatically categorizes the request (e.g., Sales Quotation, Finance Summary, Business Report, Research, or General Query).
   - Routes the request down its specific branch to execute downstream tasks (like setting up calendar events or drafting specialized summaries).

3. **Log & Reply:**
   - Consolidates all branch outputs into a unified data structure.
   - Automatically appends a clean record into **Google Sheets** for tracking.
   - Dispatches an accurate, polite, and professional response back through **Gmail**.

---

## 🛠️ Tech Stack & Tools Used
- **Workflow Automation:** n8n (Cloud/Self-hosted)
- **Artificial Intelligence:** Google Gemini AI Model (with Chat Memory and Output Parsers)
- **Google Workspace Integration:** Gmail, Google Calendar, Google Sheets

---

## 📂 Repository Contents
- `workflow.json`: The complete, exportable n8n workflow file ready to be imported into your instance.

---

## 🚀 Getting Started & Setup
1. **Clone or Download** this repository and grab the `workflow.json` file.
2. Open your **n8n dashboard**, click on options (`...`), and select **Import from File**.
3. Configure your credentials for:
   - Google Workspace (Gmail, Calendar, Sheets)
   - Google Gemini / Google AI Studio API key
4. Activate the workflow and test it out with a live email trigger!

---

## 👤 Connect With Me
If you find this project interesting or want to collaborate on advanced AI workflow automations, feel free to reach out!
