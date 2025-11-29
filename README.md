# AI Chat Agent with Response Evaluation (Gradio App)

This project implements a **context-aware AI chat agent** using **Gradio**, designed to answer questions about a person’s career, skills, and background. The agent represents the user faithfully using their summary and LinkedIn profile, and includes an **automated evaluation system** to ensure the quality and relevance of its responses.

---

## Features

- **Gradio-based Chat Interface**:  
  Users can interact with the AI agent through a web-based interface powered by Gradio.

- **Personalized AI Agent**:  
  The AI acts as the user (`{name}`), providing professional and concise answers about career, skills, and experience.

- **Context-Aware Responses**:  
  Uses a detailed summary and LinkedIn profile to answer questions accurately.

- **Response Evaluation**:  
  Every response is evaluated for quality using a separate evaluation model (`gpt-4o-mini`). Responses that fail evaluation are automatically rerun with feedback for improvement.

- **Concise Answers**:  
  The agent responds precisely to user queries without adding unnecessary information.

---

## Files

- `portfolio.ipynb` - Main script to handle user messages, generate responses, and evaluate them.
- `README.md` - Project documentation.
- Add a .env file with the api key of whatever llm u like i am using OPENAI


---
