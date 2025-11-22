##Link of accessing chatbot
https://anarthrously-unsated-claud.ngrok-free.dev/

---

## 📌 Task 4: General Health Query Chatbot

### Objective
To develop an AI-powered chatbot capable of responding to general health-related questions while ensuring strict safety guidelines.  
The chatbot is designed to provide **non-diagnostic, non-prescriptive**, and **safe** medical information.

### Dataset Used
No dataset was required for this task.  
Instead, the chatbot relies on:
- OpenAI's GPT-based language model
- Task-specific system prompts that enforce safety rules and behavior constraints

### Models Applied
- **OpenAI GPT-3.5 Turbo**  
  Used via Chat Completion API to generate human-like responses based on user queries.

### Key Features and Safety Rules
- Responds **only** to health and medical-related questions.
- Rejects all non-medical questions with a preset message:
  _“I can only answer medical or health-related questions. Please ask a medical question.”_
- Avoids unsafe practices:
  - No medical diagnosis  
  - No medication names or doses  
  - No emergency instructions  
- Advises users to seek professional help for serious issues:
  _“I am not able to give medical advice. Please consult a doctor.”_

### Key Results and Findings
- Successfully built a safe, rule-based medical chatbot using system prompts.
- Ensured the model consistently avoids unsafe outputs.
- Developed a **fully responsive frontend UI** with:
  - Mobile-friendly design  
  - Clean chat bubble interface  
  - Smooth scrolling and message animations  
- Flask backend endpoint (`/chat`) handles user messages and model responses.
- Verified safety compliance through multiple test prompts.

---

## 📁 Repository Contents
- `app.py` — Flask backend and OpenAI API integration  
- `README.md` — Project documentation  
- `static/` or embedded HTML — Chatbot frontend interface  
- `requirements.txt` — Dependencies for running the project  

---

## 🔧 Tools & Libraries Used
- Python  
- Flask  
- OpenAI API  
- HTML, CSS, JavaScript  
- pyngrok (optional for Colab deployment)  
- Jupyter Notebook / Google Colab (optional)

---
