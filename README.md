
🤖 Client Onboarding Automation Workflow (n8n)

This project is a fully automated client onboarding system built using n8n during my summer internship at IIT Jammu.

It streamlines the entire onboarding journey — from lead capture to payment confirmation — using APIs, AI, and real-time integrations. No manual work required.

---

⚙️ Tech Stack

- n8n – Workflow Automation Tool
- Google Forms + Sheets – Lead & document intake
- Airtable – Central client database
- OpenAI (GPT-3.5) – Client scoring & data parsing
- UltraMsg API – WhatsApp messaging
- Gmail – Automated email replies
- Razorpay API – Payment link generation & webhook

---

📁 Files

- Client Onboarding Project(Major Project).json – The full n8n workflow.  
Import this file directly into your n8n instance.

---

🚀 How to Use

1. Install or Access n8n
You can use n8n Cloud (https://n8n.io) or run locally:
    npx n8n

2. Import Workflow
- Go to n8n → "Import Workflow"
- Upload the provided .json file

3. Set Up Credentials
Configure these under n8n > Credentials:
- Google Sheets OAuth2
- Gmail OAuth2
- OpenAI API Key
- Airtable Personal Access Token
- Razorpay API (Basic Auth)
- UltraMsg WhatsApp API

4. Update Identifiers
Replace placeholder IDs in the workflow:
- Google Sheet/Form IDs
- Airtable Base/Table IDs
- Your Razorpay payment details
- Team member names in WhatsApp messages

5. Enable the Workflow
Once configured, turn on the workflow.  
It will trigger on form/email/WhatsApp submissions and process everything automatically.

---

🔑 Features

- 🤖 AI-based lead scoring using GPT-3.5
- 🔔 WhatsApp alerts with priority-based assignments
- 💳 Razorpay payment link generation & confirmation
- 📎 Document submission and verification
- 📬 Email autoresponder via Gmail
- 🧠 Decision logic for client prioritization
- 📊 All client data stored and updated in Airtable

---

📌 Example Use Cases

- Marketing or service agencies handling client inquiries
- Startups wanting to automate onboarding
- Freelancers managing project leads efficiently
- Any business using WhatsApp, forms, and Razorpay for client management


---

🤝 Connect With Me

Have questions or want to collaborate?

Shubham Sharma  
📬 LinkedIn: https://www.linkedin.com/in/shubham-sharma-42544734a/ 

---

⭐️ Star this repo if it helped you — and feel free to fork or open issues!
