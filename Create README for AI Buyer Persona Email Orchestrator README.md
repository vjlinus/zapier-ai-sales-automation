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
- Automated Gmail delivery  
- Real-time logging into Zapier Tables  
- Scalable for multi-persona outreach automation

---

## 📊 Architecture
