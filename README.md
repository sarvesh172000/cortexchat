# 🧠 Cortex Chat

A real-time chat application with RAG-powered AI assistant, built using React, FastAPI, LangChain, Pinecone/FAISS, and Dockerized microservices.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/cortex-chat.git
cd cortex-chat
2. Add environment variables
Create .env files for each service. Examples are provided in their respective folders.

3. Run locally with Docker Compose
bash
Copy
Edit
docker-compose up --build
4. Access the app
Frontend: http://localhost:3000

Backend: http://localhost:5000

Assistant API: http://localhost:8000

📌 Roadmap Summary
✅ Chat UI with login & threading

✅ WebSocket backend with PostgreSQL persistence

✅ RAG-based assistant with file upload + Pinecone/FAISS

✅ Dockerized deployment & GitHub Actions for CI/CD

🛡️ Prerequisites
Node.js

Python 3.10+

Docker

OpenAI API Key (or Llama3 setup)

Pinecone/FAISS setup for vector DB

Basic knowledge of LangChain & FastAPI

📜 License
MIT License. Feel free to use, modify, and contribute!

Made with ❤️ by [Your Name]