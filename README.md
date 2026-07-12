# 📧 AI Email Assistant with n8n & Google Gemini

An AI-powered email assistant built with **n8n**, **Google Gemini**, **Gmail**, **Google Sheets**, **Google Calendar**, and **Telegram**.

## 🚀 Features

- 📥 Automatically detects new Gmail messages.
- 🤖 Analyzes emails using Google Gemini AI.
- 📝 Generates a concise email summary.
- 🏷️ Classifies the email category.
- ⭐ Detects priority (High, Medium, Low).
- 💬 Suggests a professional reply.
- 📅 Detects meeting date and time.
- 📋 Extracts action items.
- 📊 Stores email analysis in Google Sheets.
- 📆 Creates Google Calendar events for meetings.
- 📲 Sends Telegram notifications with email details.

---

## 🛠️ Technologies Used

- n8n
- Google Gemini AI
- Gmail API
- Google Sheets API
- Google Calendar API
- Telegram Bot API
- Docker

---

## 🔄 Workflow

Gmail Trigger
↓
Get Email
↓
AI Agent (Google Gemini)
↓
Structured Output Parser
↓
Google Sheets
↓
IF (Meeting Detected?)
├── Yes → Google Calendar → Telegram
└── No → End

---

## 📂 AI Output

The AI extracts:

- Summary
- Category
- Priority
- Suggested Reply
- Needs Reply
- Action Items
- Meeting Date
- Meeting Time

---

## 📌 Future Improvements

- Auto-create Gmail Draft replies.
- Email sentiment analysis.
- Spam detection.
- Multi-language support.
- Dashboard for analytics.
- Slack & Discord notifications.

---

## 👨‍💻 Author

## Screenshots

### Workflow
![Workflow](screenshots/workflow.png)

### AI Agent
![AI Agent](screenshots/ai-agent.png)

### Google Sheet
![Google Sheet](screenshots/google-sheet.png)

### Google Calendar
![Calendar](screenshots/calendar-event.png)

### Telegram Notification
![Telegram](screenshots/telegram-message.png)

**Omar Mohammed**

Computer Engineering Student

Interested in AI Automation, Cybersecurity, and Python.

GitHub:
https://github.com/om01158946425-bit
