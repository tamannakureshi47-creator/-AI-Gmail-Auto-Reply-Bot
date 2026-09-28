#  AI Gmail Auto Reply Bot

An AI-powered Gmail automation workflow built with **n8n**, **OpenAI**, **Gmail**, and **Google Sheets**.

This workflow automatically checks incoming Gmail messages, processes them using an AI Agent, generates an appropriate reply, sends the response back to the sender, and records the activity in Google Sheets.

---

##  Features

- 📩 Automatically fetch Gmail messages
- 🤖 Generate intelligent replies using an AI Agent
- 🧠 Powered by OpenAI
- 🔄 Process multiple emails using a loop
- 📤 Automatically send replies through Gmail
- 📊 Log processed emails and responses in Google Sheets
- ⏰ Run automatically using a Schedule Trigger
- ⚡ No manual intervention required after setup

---

##  Workflow Architecture

```text
Schedule Trigger
       │
       ▼
Get Gmail Threads
       │
       ▼
Get Gmail Messages
       │
       ▼
Loop Over Items
       │
       ▼
   AI Agent
       │
       ├── OpenAI Chat Model
       │
       ▼
  Send Gmail Reply
       │
       ▼
 Append Row to Google Sheets
```

<img width="2424" height="1219" alt="screencapture-tamanna2-app-n8n-cloud-workflow-sSBImsSTdcVH6Zlx-2026-09-28-20_29_05" src="https://github.com/user-attachments/assets/a9e10594-20a0-4602-802d-1fc61f3411fd" />
