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

<img width="1882" height="767" alt="Screenshot 2026-09-02 171450" src="https://github.com/user-attachments/assets/5030a07e-80d6-4ff1-b017-b4e074175b1a" />
<img width="1851" height="760" alt="Screenshot 2026-09-02 171652" src="https://github.com/user-attachments/assets/62240ee2-d488-4c48-a231-0d7e726e15c6" />
<img width="1875" height="678" alt="Screenshot 2026-09-02 145640" src="https://github.com/user-attachments/assets/5eba8f7e-872b-4199-b498-09feadb2636c" />



### Workflow


![Workflow]<img width="1873" height="721" alt="Screenshot 2026-09-02 171613" src="https://github.com/user-attachments/assets/4d75c2a0-788b-42e9-8edb-efb8f3714482" />


---

### AI Assistant

> Add assistant screenshot here.

![Assistant]<img width="1875" height="678" alt="Screenshot 2026-09-02 145640" src="https://github.com/user-attachments/assets/8cd1ad37-55c0-4a53-9d8b-5be67881d361" />


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
<img width="1756" height="632" alt="Screenshot 2026-09-02 171533" src="https://github.com/user-attachments/assets/0d92bef4-e98f-4555-866a-668b6b3def15" />

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
