🧠 AI-Powered Mental Health Check-In Agent

An automated mental health check-in system using **n8n**, **Telegram**, **Azure OpenAI**, and **Google Sheets** to help users monitor and improve emotional well-being.

🎯 Project Purpose

In response to the growing need for proactive mental wellness support, this system empowers users to:
- Regularly assess emotional well-being
- Receive empathetic, AI-generated support
- Track mood trends automatically
- Gain weekly summaries via email

🧩 Tech Stack

- n8n – Workflow Automation  
- Telegram Bot – For daily check-ins  
- Azure OpenAI – To generate supportive, personalized messages  
- Google Sheets – To log and analyze mood trends  
- Email (SMTP) – For weekly summary reports  

⚙️ How It Works

Daily Check-In Flow:
1. Triggers a daily Telegram message: "How are you feeling (1–5)?
2. Captures response and sends it to Azure OpenAI.
3. AI replies with supportive feedback.
4. Logs user’s mood score in Google Sheets.

 Weekly Summary:
1. Every 7 days, reads past week’s mood data.
2. Compiles and emails a summary to the user or admin.

 📷 Workflow Diagram

![Mental Health Workflow](images/mental-health-diagram.png)

---

 📈 Features

- Automated daily mood check-ins  
- Empathetic AI-generated responses  
- Secure data logging with Google Sheets  
- Weekly email insights and reports  
- Privacy-first, non-intrusive design  

 🔮 Future Scope

- Integration with WhatsApp, Slack, Discord  
- Voice-based emotional check-ins  
- Advanced NLP sentiment detection  
- Therapist alert escalation for critical trends  
- Mood dashboard and gamified self-care  


🙏 Thank You

Your support helps promote better mental health awareness and accessible well-being solutions.


 📂 File Overview

- workflow.json – Exported n8n workflow  
- images/ – Flowchart and illustrations  
- docs/ – Presentations and documentation  
