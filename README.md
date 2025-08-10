# AgentForce_Arjun
n8n worflow json
# AgentForce_Arjun — Academic Planner AI (n8n Workflow)

This project is an **AI-powered academic planner** built using **n8n** and **Google Gemini**.  
It helps students create semester-by-semester plans, stores them in Google Sheets, and sends reminders via Email and WhatsApp.

---

## 📌 Features
- Conversational intake of student goals.
- Auto-generation of:
  - Semester plan
  - Milestones
  - Skill roadmap
  - Deadlines
- Progress tracking in Google Sheets.
- Reminder system via Email & WhatsApp.
- Escalation alerts for overdue tasks.

---

## 📂 Files in this repository
- `AgentForce_Arjunprod.json` — The exported **n8n workflow**.  
  You can import this into your own n8n instance to run the project.
- `Architecture_Documentation.pdf` — Explains how the system works (components, data flow, etc.).
- PPT explaining the n8n workflow.


---

## 🚀 How to Use
1. **Download** the `AgentForce_Arjunprod.json` file from this repo.
2. **Import** it into your n8n instance:
   - In n8n, click **Import Workflow**.
   - Select the JSON file.
3. **Set up credentials** in n8n:
   - Google Sheets
   - Twilio (for WhatsApp)
   - SMTP (for Email)
   - Google Gemini API
4. Start the workflow and interact via the public chat UI.

---

