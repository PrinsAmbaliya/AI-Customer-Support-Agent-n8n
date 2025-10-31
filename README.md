# AI-CustomerSupport-Agent-n8n


## Project Overview
**AI-CustomerSupport-Agent-n8n** ek intelligent automation system hai jo AI ke madhyam se customer queries ka jawab deta hai.  
Yeh project **n8n workflow automation tool** aur **Google Gemini API** ka use karta hai taaki customer support process ko smart aur automatic banaya ja sake.  

Isse aap ek 24x7 AI-based Customer Support Agent bana sakte ho jo user ke queries ko samajhta hai, unka jawab deta hai aur saare interactions ko **Google Sheet** me record karta hai.  

---

## Tech Stack Used
-  **Google Gemini API** – AI replies generate karne ke liye  
-  **n8n** – Workflow automation platform  
-  **Google Sheets** – Data storage ke liye  

---

## Key Features
✅ AI se auto customer query handling  
✅ Google Sheets me query aur response record hota hai  
✅ Real-time AI replies  
✅ Custom workflow banane ki flexibility  
✅ 24x7 available – No human support required  

---

## How It Works
1. User message → n8n webhook → triggers the workflow  
2. Gemini API → processes the message → generates AI response  
3. Response → sent back to user (Telegram / Gmail / Webhook)  
4. Query + Response → saved automatically in Google Sheets  

---

##  Setup Instructions

### 1. Clone this repository
```bash
git clone https://github.com/YourUsername/Gemini-AI-CustomerSupport-Agent-n8n.git
cd Gemini-AI-CustomerSupport-Agent-n8n
```
### 2. Import Workflow in n8n
- Open n8n dashboard
- Click Import Workflow
- Upload workflow.json

### 3. Add API Keys
- Open credentials/config-example.json
- Add your Gemini API Key
- Add your Google Sheets credentials

### 4️. Run Workflow
- Click Execute Workflow

---

## Example Flow

User sends query: “Hi, I have an issue with my order.”

n8n captures the query and sends it to Gemini API

Gemini AI generates a helpful reply

Reply goes back to the user instantly

Both query and reply get saved in Google Sheet automatically

---

## Preview

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a80c71d7-5ca0-4135-a8dc-0df8bf852c5f" />

---


## Author

Prins Ambaliya

GitHub: PrinsAmbaliya

LinkedIn: https://www.linkedin.com/in/prins-ambaliya-bb7546367
