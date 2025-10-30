# 🤖 AI Buyer Signal Orchestrator

The **AI Buyer Signal Orchestrator** automates personalized outreach by combining real-time buyer intent signals with persona-based insights.  
It integrates data from LinkedIn, company databases, and AI enrichment to craft relevant sales messages.

---

## 🧭 Workflow Overview
**Flow:**
1. Capture buyer signal (e.g., forms, engagement, profile visit, or keyword trigger)
2. Use AI (OpenAI / Clay / Zapier) to generate personalized email
4. Log the interaction and outcome to CRM or Google Sheets

---

## ⚙️ Tools & Stack
- Zapier (Automation Logic)
- OpenAI API (Text Generation)
- Zapier Table (Data Storage)
- Forms (input data)
- Slack or Gmail (Delivery)

---

## 🧠 Features
- Dynamic personalization using AI
- Buyer intent + persona-based segmentation
- Auto-triggered outreach & follow-up
- AI retry logic, Error handling + logging in Zapier Table

---

## 🧩 Example Use Case
> A buyer downloads a whitepaper → system identifies persona → AI crafts follow-up email tailored to role → email sent via Gmail → logged to CRM.

---

## 🧰 Repository Contents
| File | Description |
|------|--------------|
| `README.md` | Project overview |
| `<img width="16384" height="7123" alt="AI Buyer Signal Orchestrator - draft (1)" src="https://github.com/user-attachments/assets/52e5a9f1-5e16-4137-9b7f-ecb43c628e20" /> | Visual workflow map |
| `prompt.txt` | AI prompt used for personalization |
| `zapier-steps.json` | (Optional) Export of your Zap configuration |
| `notion-link.md` | Link to extended documentation |

---

## 🪄 Future Improvements
- Add Multi-Channel buyer data
- Add CRM integration
- Improve AI tone control
- Add Slack summary notification for each run

---

## 📎 Author
**Jason Linus**  
Automation & GTM Engineer  
[https://www.linkedin.com/in/jason-linus-7120a51/] | [Portfolio](https://nifty-yak-ffd.notion.site/Jason-Linus-8c81e08090a74a9ca2d20287693bebe9?pvs=74)
