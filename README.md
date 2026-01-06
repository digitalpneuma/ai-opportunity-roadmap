# ai-opportunity-roadmap
Repository for https://replit.com/@digitalpneuma/Opportunity-Canvas
# AI Opportunity Map - Frontend

Beautiful web interface for the AI-powered automation opportunity analyzer.

🔗 **Live Demo:** [Your Replit URL]
🔗 **n8n Workflow:** [Link to your n8n workflow repo]

## Features

- 🎨 Modern orange/amber design
- 📝 Simple business process input form
- ⚡ Real-time AI analysis
- 📊 Automated ROI calculations
- 📧 Email delivery of reports
- 📱 Fully responsive

## Tech Stack

- HTML5
- CSS3 (Custom animations)
- Vanilla JavaScript
- n8n webhook integration

## Setup

1. Update the webhook URL in `script.js`:
```javascript
   const WEBHOOK_URL = 'YOUR-N8N-WEBHOOK-URL';
```

2. Deploy to your hosting platform or use Replit

## How It Works

1. User describes their manual business process
2. Form submits to n8n webhook
3. AI analyzes and generates roadmap
4. Professional HTML email sent to user
5. Success message displayed

## 🔗 Related Projects

This is the frontend web interface for the AI Opportunity Map Generator.

**Backend Workflow:**
- [n8n Automation Workflow](https://github.com/digitalpneuma/ai-opportunity-map-n8n) - The AI engine that powers this app

**How They Work Together:**
1. User fills out form on this frontend
2. Form sends data to n8n webhook
3. n8n runs AI analysis
4. Beautiful email report sent to user

## 🚀 Live Demo

Try it here: https://opportunity-canvas--digitalpneuma.replit.app/
