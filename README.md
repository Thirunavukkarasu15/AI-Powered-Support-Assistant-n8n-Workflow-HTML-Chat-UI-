# AI Support Assistant (n8n + HTML Chat UI)
*A conversational support automation system using n8n workflows and an HTML chat interface.*

## 🧩 Table of Contents
- Overview
- Motivation / Problem
- Key Features
- Architecture Diagram
- Demo Link / GIF (optional)
- Prerequisites
- Installation Steps
- Usage Examples
- Configuration
- Roadmap Items (optional)
- Contribution Guidelines
- License
- Author & Contact
- Acknowledgements

## 🎯 Overview
This project provides a fully automated, AI-driven support assistant built using n8n and a lightweight HTML chat interface. It supports text and voice inputs, performs FAQ-based responses, integrates Google Sheets, triggers escalations, and supports meeting scheduling — all in a single streamlined architecture.

## 🔥 Motivation / Problem
Traditional customer support systems struggle with slow response times, manual triage, and inconsistent answers. This project solves these challenges by:
- Providing instant AI-powered support
- Automatically detecting escalation cases
- Reducing manual workload for support teams
- Unifying voice + text input processing
- Automating meeting scheduling and email notifications

## 🚀 Key Features
- AI Support Chat (Text + Voice)
- FAQ Retrieval via Google Sheets
- Escalation Detection + Ticket Creation
- Meeting Scheduler Workflow
- Real-Time HTML Chat Interface
- Non-Blocking Workflow Execution


## 🎥 Demo Link / GIF (optional)
Coming soon…

## 🧰 Prerequisites
- n8n
- OpenAI API Key
- Google Sheets API
- Google Calendar API
- SERP API Key
- Hosting for HTML UI
- Google Sheet formatted as: Question | Answer | Category | Intent

## ⚙️ Installation Steps
1. Clone repo  
2. Import workflows into n8n  
3. Configure credentials  
4. Update webhook URL in frontend  
5. Deploy HTML UI  

## 💡 Usage Examples
**FAQ:** “How do I verify a payment?”  
**Escalation:** “I want to talk to support.”  
**Voice Input:** Upload `.m4a` file  

## 🛠 Configuration
Environment variables:
```
OPENAI_API_KEY
GOOGLE_SHEETS_CREDENTIALS
GOOGLE_CALENDAR_CREDENTIALS
SERP_API_KEY
WEBHOOK_URL
```

## 🗺 Roadmap Items
- Multilingual support  
- Analytics dashboard  


## 👤 Author & Contact
Thirunavukkarasu 
thiruashok@gmail.com

## 🙏 Acknowledgements
- n8n community  
- OpenAI  
- Google Cloud  
- SERP API  
