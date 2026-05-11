# AI Email Automation Workflow using n8n

An intelligent AI-powered email automation workflow built with n8n.

## Features

- Bulk email sending
- Gmail reply tracking
- AI-based phone/email extraction
- Auto Google Sheet update
- Auto follow-up email sending
- Thread ID based reply verification
- Smart lead management system

## Workflow Architecture

1. Send bulk emails
2. Save threadId in Google Sheets
3. Detect customer replies
4. Match threadId
5. Extract:
   - Phone number
   - Personal email
6. Auto update Google Sheets
7. Send follow-up email automatically

## Tech Stack

- n8n
- Gmail API
- OpenAI
- Google Sheets API

## AI Agent Tasks

- Parse customer reply
- Extract structured data
- Send follow-up email
- Update CRM sheet automatically

## Workflow Screenshot

![Workflow](screenshots/workflow-main.png)

Example:
- workflow-main.png
- ai-agent.png
- gmail-trigger.png

## Future Improvements

- WhatsApp Automation
- CRM Integration
- Lead Scoring
- Dashboard Analytics

  project/
│
├── README.md
├── workflow.json
├── screenshots/
│   ├── workflow-main.png
│   ├── ai-agent.png
│   └── gmail-trigger.png

## Author

Rokonur Jaman Riyad
