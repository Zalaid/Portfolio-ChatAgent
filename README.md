# AI Website Chat Agent with Response Evaluation

This project implements a **context-aware AI chat agent** designed to answer questions on a personal website. The agent represents the website owner faithfully using their background and LinkedIn profile, and includes an **automated evaluation system** to ensure the quality and relevance of its responses.

---

## Features

- **Personalized Chat Agent**:  
  The AI acts as the website owner (`{name}`), providing professional and concise answers about career, skills, background, and experience.

- **Context-Aware Responses**:  
  Uses a detailed summary and LinkedIn profile to respond accurately to user questions.

- **Response Evaluation**:  
  Every response is evaluated for quality and relevance using a separate evaluation schema (`EvaluationSchema`). Unacceptable responses are automatically rerun with feedback to improve accuracy.

- **Concise Answers**:  
  The agent is instructed to respond **precisely** to user queries, without adding unnecessary information.

---

## Files

- `portfolio.ipynb` - Main script to handle user messages, generate responses, and evaluate them.
- `README.md` - Project documentation.

---
