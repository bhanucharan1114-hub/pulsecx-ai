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

(Add images from `/assets` here if needed)
<img width="1920" height="1140" alt="ui png" src="https://github.com/user-attachments/assets/50cf4ad0-91d3-4f02-afdf-1393e03065a2" />


---

## Impact

PulseCX AI helps small teams act faster on customer feedback by turning raw responses into structured insights.
