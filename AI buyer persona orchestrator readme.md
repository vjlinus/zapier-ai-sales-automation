# 🤖 AI Buyer Persona Email Orchestrator

## 🧭 Overview
The **AI Buyer Persona Email Orchestrator** automates persona-based outbound email generation. Instead of relying on external signals, it uses predefined persona intelligence stored in **Zapier Tables** to personalize tone, structure, and value messaging.

**Outcome:** Reduces email drafting time by ~70%  
**Stack:** Zapier, AI by Zapier (LLM), Zapier Tables, Gmail

---

## ⚙️ Workflow

**Trigger:**  
- A new record is added in **Zapier Tables** containing:
  - Contact name  
  - Company  
  - Email  
  - Persona type  
  - Message goal  

**Actions:**  
1. **Fetch Persona Intelligence:** Retrieve persona tone, communication style, and value focus from Zapier Tables.  
2. **Generate Email Content:** Use **AI by Zapier** to create a contextual subject line and email body tailored to the persona.  
3. **Apply Conditional Paths:**  
   - **Path A:** Persona = VP of Engineering → Technical tone, efficiency-focused messaging.  
   - **Path B:** Persona = CTO → Strategic tone, innovation and scalability messaging.  
   - **Path C:** Persona = Product Manager → Empathetic tone, customer impact emphasis.  
4. **Send Email:** Deliver the generated email via **Gmail**.  
5. **Log Outcome:** Update **Zapier Tables** with the email content, send status, and timestamp for tracking.

---

## 🧩 Key Features
- Persona-specific conditional logic  
- AI-driven subject + body personalization  
- AI smart routing and messaging
- Data validation, AI failure recovery, performance analytics and human in loop 
- Real-time logging into Zapier Tables  
- Scalable for multi-persona outreach automation

---


---

## 💡 Example Output

| Persona | Email Focus | Tone | Example Snippet |
|----------|--------------|------|-----------------|
| VP of Engineering | Efficiency & Reliability | Analytical | “Your team’s focus on improving delivery pipelines stood out — here’s how we’ve helped others cut deployment times by 40%…” |
| Product Manager | Customer Value | Empathetic | “Many PMs are connecting user insights to roadmap priorities — here’s an approach that’s resonating…” |
| CTO | Strategy & Innovation | Visionary | “As technology evolves, CTOs are aligning architecture with long-term scalability — here’s how we’re enabling that shift…” |

---

## 🚀 Outcome
- Reduces email creation time from **10 minutes → 1 minute**
- Maintains tone consistency across outreach
- Creates a repeatable personalization engine for SDR and sales teams

---

## 📸 Workflow Screenshot  
[View Workflow Screenshot](https://github.com/vjlinus/zapier-ai-sales-automation/blob/main/buyer-persona-email-orchestrator/ai-buyer-persona-email-orchestrator.png)





