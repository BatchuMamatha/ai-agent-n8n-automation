# AI Agent for Email and Calendar Automation

🔧 Built using [n8n](https://n8n.io) + ChatGPT 4.1 mini + Google APIs

## 🚀 Features

- Natural language chat to:
  - ✉️ Send emails via Gmail
  - 📅 Create calendar events
- Uses Google Sheets as contact database
- Powered by n8n workflows + ChatGPT for intent parsing

## 📂 Files

- `ai-agent-automation-workflow.json` — Main n8n workflow

## 🧠 How It Works

1. User types a command like: "Send an email to Rahul for 2 days leave."
2. ChatGPT interprets the intent.
3. n8n:
- Pulls Rahul’s email from Google Sheets
- Sends the email through Gmail API
4. Or schedules a calendar event based on input.

## 📽 Preview

[👉 Output Video Preview](https://drive.google.com/file/d/1Qq2vSZqu2fuYzP_TYcUjwsXB2AojfYsZ/view?usp=drive_link)


---

### 🛠️ To Use

1. Import the JSON file into your local or cloud n8n instance.
2. Connect your Google services.
3. Try sending a chat command!

---

## 📧 Contact

Built by Batchu Mamatha

