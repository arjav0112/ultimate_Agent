# 🤖 Ultimate AI Agent – Telegram Bot Edition

An **all-in-one AI-powered assistant** that executes real-world tasks from a single Telegram message.

With just **one prompt**, this agent can:
- 📧 Send Emails  
- 📅 Create Google Calendar Events  
- ✍️ Generate AI Content  
- 🌐 Perform Real-Time Web Search  
- 📇 Manage Contacts via Airtable  

Built using **Google Gemini, Gmail API, Google Calendar API, Tavily Search, Airtable, n8n**, and a **Telegram Bot interface**.

---

## 📽 Demo
[![Watch the demo](https://img.shields.io/badge/▶%20Watch%20Demo-blue)](#) *_(https://www.loom.com/share/050dfb731e4d4bc197cfd71ac1ef65ef?sid=c3566642-d2ff-4379-bffa-58e8aa08fb6b)_*

---

## 🚀 Features

### 🔹 Single Prompt Execution
One Telegram message can intelligently trigger multiple actions:
- Draft and send emails
- Schedule meetings
- Search the web for context
- Store or retrieve contacts
- Generate structured content

### 🔹 AI-Powered Decision Making
- Uses **Google Gemini** for intent understanding
- Automatically decides which tools to call
- Handles multi-step workflows

### 🔹 Real-World Integrations
- **Gmail API** → Send professional emails
- **Google Calendar API** → Create meeting invites
- **Tavily API** → Reliable web search
- **Airtable API** → Contact storage & lookup
- **Telegram Bot API** → User interface
- **n8n** → Workflow orchestration engine

---


The AI analyzes user intent, selects the required tools, and executes actions automatically.

---

## 🛠 Tech Stack

- **LLM**: Google Gemini  
- **Automation Engine**: n8n  
- **Messaging Interface**: Telegram Bot API  
- **Email Service**: Gmail API  
- **Calendar Service**: Google Calendar API  
- **Web Search**: Tavily API  
- **Database**: Airtable  

---

## ⚙️ Setup Instructions (n8n)

### 1️⃣ Required Credentials

You will need:

- ✅ Google Gemini API Key  
- ✅ Telegram Bot Token  
- ✅ Google OAuth Credentials (Gmail + Calendar scopes)  
- ✅ Airtable API Key & Base ID  
- ✅ Tavily API Key  

---

### 2️⃣ Setup Steps

1. Create a Telegram bot via **@BotFather**
2. Configure credentials in n8n:
   - Google Gemini
   - Gmail OAuth2
   - Google Calendar OAuth2
   - Airtable API
   - Tavily API
3. Import the workflow JSON into n8n
4. Activate the workflow
5. Start chatting with your Telegram bot 🎉

---

## 📌 Example Prompts

- "Email Arjun the project update and schedule a meeting tomorrow at 5 PM."
- "Find the latest AI news and summarize it."
- "Add Rahul to my contacts with his email rahul@email.com."
- "Draft a professional follow-up email for a job application."

---

## 🧠 What Makes This Project Unique?

- Multi-tool execution from a single prompt
- Real-world automation use case
- Production-style architecture
- Demonstrates AI Agents + Tool Calling + Workflow Orchestration
- Fully extensible

---

## 🔮 Future Improvements

- Memory & conversation history
- Role-based multi-user support
- Voice input integration
- Custom dashboard for monitoring actions
- Deployment via Docker + Cloud VM

---

## 📄 License

This project is for educational and demonstration purposes.

---

## 👤 Author

**Arjav Jain**  
AI Developer | Automation Enthusiast | Building Intelligent Systems  

If you found this project interesting, feel free to ⭐ the repository!
