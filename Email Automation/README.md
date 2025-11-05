* Gmail AI Agent Automation Workflow

# Project Overview  
This workflow automatically reads emails from Gmail, uses an **AI Agent (powered by OpenAI)** to summarize and analyze the content, Draft a mail and then stores the extracted details in **Airtable** for organized tracking.


⚙️ Workflow Steps

1. **⏰ Schedule Trigger**  
   - Triggers the workflow at a fixed interval (e.g., every hour).  
   - Ensures the system checks Gmail regularly for new messages.  

2. **📩 Gmail – Get All Mails**  
   - Connects to the Gmail API.  
   - Retrieves a list of recent emails.

3. **📧 Gmail – Get Mail Details**  
   - Extracts detailed information such as sender, subject, and body text for each email.

4. **🤖 AI Agent (OpenAI Chat Model)**  
   - Processes each email content using the **ChatGPT model**.  
   - Summarizes the message or classifies it (e.g., lead inquiry, feedback, task, etc.).  
   - Can be customized to extract structured data like name, email, purpose, etc.  

5. **📊 Airtable – Create Record**  
   - Sends the AI-processed output into Airtable.  
   - Creates a new record for every analyzed email.  
   


### 🧰 Tools Used
- **n8n** (Workflow Automation)
- **Gmail API**
- **OpenAI API (ChatGPT)**
- **Airtable**



* Use Case
  This automation is useful for:
- Businesses that receive many client emails daily.  
- Automatically classifying and storing emails in Airtable.  
- Generating summaries or extracting leads without manual work.  


* Outcome
✅ Reduced manual email checking time by 90%  
✅ Centralized data storage in Airtable  
✅ Smart, AI-based categorization of incoming messages  


* Created by  
**Akshata Dhawan**  
AI Automation Developer | Building smart workflows with n8n + ChatGPT  
