# 🤖 Personal AI Assistant using n8n

An AI-powered Personal Assistant built using **n8n**, **Google Gemini**, and **Google Workspace APIs**. This assistant can search the web, manage emails, create calendar events, maintain notes, manage tasks, and track expenses using natural language.

---

## 🚀 Features

- 🌐 Web Search using SerpAPI
- 📧 Read and Send Gmail Emails
- 📅 Create & Retrieve Google Calendar Events
- ✅ Create, View & Delete Google Tasks
- 📝 Create, Update & Read Google Docs Notes
- 💰 Expense Tracking with Google Sheets
- 🧠 Conversation Memory
- 🤖 Google Gemini AI Integration
- 🔄 AI Agent with Tool Calling

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| Google Gemini | AI Model |
| SerpAPI | Web Search |
| Gmail API | Email Management |
| Google Calendar API | Calendar Events |
| Google Tasks API | Task Management |
| Google Docs API | Notes |
| Google Sheets API | Expense Tracking |

---

## 📂 Project Structure

```
Personal-AI-Assistant/
│
├── Personal_Assistant_Workflow.json
├── README.md
├── screenshots/
│   ├── workflow.png
│   ├── assistant-chat.png
│   └── features.png
└── assets/
```

---

## ⚙️ Workflow Overview

```
User
   │
   ▼
Webhook
   │
   ▼
AI Agent (Google Gemini)
   │
   ├── 🌐 SerpAPI
   ├── 📧 Gmail
   ├── 📅 Calendar
   ├── ✅ Google Tasks
   ├── 📝 Google Docs
   └── 💰 Google Sheets
   │
   ▼
Response
```

---

## 📸 Screenshots

### Workflow

> Add workflow screenshot here.

![Workflow](screenshots/workflow.png)

---

### AI Assistant

> Add assistant screenshot here.

![Assistant](screenshots/assistant-chat.png)

---

## 📥 Installation

1. Clone this repository

```
git clone https://github.com/yourusername/Personal-AI-Assistant.git
```

2. Open n8n

3. Import

```
Personal_Assistant_Workflow.json
```

4. Reconnect Credentials

- Google Gemini
- Gmail OAuth
- Google Calendar OAuth
- Google Docs OAuth
- Google Sheets OAuth
- Google Tasks OAuth
- SerpAPI

5. Activate the workflow.

---

## 💬 Example Commands

```
Show today's tasks

Read my latest emails

Create a meeting tomorrow at 6 PM

Search latest AI news

Create a note titled Interview Preparation

Add ₹500 Food Expense
```

---

## 🎯 Future Improvements

- WhatsApp Integration
- Telegram Bot
- Voice Assistant
- File Upload Support
- Weather Tool
- Stock Market Tool
- News Summarization
- PDF Question Answering
- Multi-user Authentication

---

## 📖 Learning Outcomes

This project helped me learn:

- AI Agents
- Workflow Automation
- API Integration
- Prompt Engineering
- Google Workspace APIs
- Tool Calling
- Memory Management
- n8n AI Nodes

---

## 👨‍💻 Author

**Niju Shrivastav**

B.Tech CSE Student

AI • Machine Learning • Python • Automation

GitHub: https://github.com/nijushrivastav

LinkedIn: www.linkedin.com/in/niju-shrivastav-97178b2a8

---

## ⭐ Support

If you like this project, don't forget to ⭐ the repository.
