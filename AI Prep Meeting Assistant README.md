# 🤖 AI Meeting Prep Assistant

## 🧭 Overview
The **AI Meeting Prep Assistant** automates meeting preparation by generating personalized summaries, key talking points, and contextual insights for sales representatives — using **AI by Zapier** integrated with Notion and communication tools.

**Outcome:** Cuts meeting prep time by ~60%  
**Stack:** Zapier, AI by Zapier (LLM), Notion, Gmail, Slack  

---

## ⚙️ Workflow

**Trigger:**  
- New meeting or deal data is added to **Notion** or **Google Sheets**  
- Optional: Triggered by a new event in **Google Calendar**

**Steps:**
1. **Fetch meeting data** → Retrieve meeting title, client name, company, and notes.  
2. **Data validation** → Check if all required fields are available.  
   - If incomplete → Trigger Slack + Gmail alerts to sales rep (“Missing meeting data”).  
3. **AI generation (AI by Zapier)** →  
   - Analyze notes and context.  
   - Generate:
     - Executive summary  
     - Key talking points  
     - Anticipated objections or goals  
4. **Deliver prep summary** →  
   - Send generated output to **Gmail** or **Slack** for quick access.  
   - Store the prep notes in a **Notion** database for later reference.  
5. **Log outcome** →  
   - Update a row in **Google Sheets** or **Notion** with “Prep Delivered” status, timestamp, and message ID.

---

## 🧠 Intelligent Logic
- **Conditional branching:**
  - **Path A:** All data available → Generate prep  
  - **Path B:** Missing fields → Notify rep & pause workflow  
- **Error handling:** Slack + email alerts prevent silent failures.  
- **Prompt control:** Uses structured templates for consistent LLM responses.

---

## 📊 Flow Summary
