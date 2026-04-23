# pulsecx-ai
AI agent that turns customer feedback into actionable insights for startups

PulseCX AI is an AI-powered system that helps student startups and small businesses turn customer feedback into clear, actionable insights without needing a data team.

---

 ##Problem

Small teams collect customer feedback but struggle to extract meaningful insights from it. Without dedicated analytics resources, they are forced to manually read responses, making it difficult to identify recurring issues and take timely action.

---

##Solution

PulseCX AI automates the entire feedback analysis pipeline:

- Collects feedback through forms
- Processes and aggregates responses
- Analyzes sentiment and identifies key themes
- Detects the most common issues
- Generates clear, actionable recommendations

Instead of reading 100 responses, founders get 5 clear actions.

---

## Architecture

UI → Webhook → Campaign Trigger  
Feedback Form → Data Storage  
Scheduled Processing → Aggregation → LLM Analysis  
Insights → UI / Email Delivery  

---

## Tech Stack

- n8n (workflow automation)
- Groq API (LLaMA 3.3 70B)
- Google Forms & Google Sheets
- HTML, CSS, JavaScript

---

## Project Structure

pulsecx-ai/
│
├── ui/ # Frontend interface
├── workflows/ # n8n workflow exports
├── assets/ # Screenshots and visuals
├── docs/ # Documentation


---

## How to Run

1. Import workflows into n8n  
2. Configure:
   - Groq API key  
   - Google Sheets  
   - Email credentials  
3. Run workflows  
4. Open UI  
5. Start campaign and generate insights  

---

## Note

This project uses n8n for workflow automation.  
Due to free-tier limitations, the live instance may not always be available.

All workflows are provided in the `/workflows` folder and can be imported into any n8n instance to reproduce the system.

---

## Demo

(Add your demo video link here)

---

## Screenshots
<img width="1292" height="314" alt="workflow1" src="https://github.com/user-attachments/assets/68a8282f-2928-446d-a779-4a165ec21a82" />
<img width="1569" height="360" alt="workflow2" src="https://github.com/user-attachments/assets/f9cc74cc-3afb-472b-b9d7-7965f74a0fdf" />
<img width="1594" height="451" alt="workflow3" src="https://github.com/user-attachments/assets/21ca7e13-63d2-4ddc-aa1a-0a67b2f3c15d" />
<img width="1920" height="1140" alt="ui" src="https://github.com/user-attachments/assets/fb0208d9-b911-46b4-bb9e-c588fab57fef" />
<img width="1920" height="1140" alt="ui_response" src="https://github.com/user-attachments/assets/1232ca91-3cee-4710-a967-5d627b2ee0a7" />
<img width="636" height="762" alt="feedbackForm" src="https://github.com/user-attachments/assets/045615d9-b024-4f7e-9fad-ada20b37110c" />
<img width="718" height="731" alt="AI_ANALYSIS_REPORT" src="https://github.com/user-attachments/assets/60dba1fc-c2d7-45eb-a703-13e5908adc80" />
<img width="912" height="734" alt="ALERT_SYSTEM" src="https://github.com/user-attachments/assets/04621cb6-a7f8-443d-9d3a-b622b0a6a380" />

---

## Impact

PulseCX AI helps small teams act faster on customer feedback by turning raw responses into structured insights.
