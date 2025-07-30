# 🧠 Cortex Chat

A real-time chat application with a **RAG-powered AI assistant**. Chat with other users and ask AI questions based on your uploaded documents.

---

## ⚡ Features

- 🔁 Real-time messaging via WebSockets
- 🤖 AI Assistant powered by Retrieval-Augmented Generation (RAG)
- 📄 Upload custom documents (e.g. PDFs) for contextual AI answers
- 🚀 CI/CD with GitHub Actions & Docker
- ☁️ Deployable to Vercel, Fly.io, Railway

---

## 🧱 Tech Stack

| Layer        | Technologies                                |
| ------------ | ------------------------------------------- |
| Frontend     | React, Tailwind                             |
| Chat Backend | Node.js, Socket.IO                          |
| AI Assistant | FastAPI, LangChain, Pinecone, OpenAI/Llama3 |
| Database     | PostgreSQL (via Supabase)                   |
| Auth         | Firebase / Auth.js                          |
| CI/CD        | GitHub Actions                              |
| Containers   | Docker, Docker Compose                      |
| Deployment   | Vercel (FE), Fly.io / Railway (BE)          |

---

## 📂 Project Structure

```plaintext
/chat-app
├── backend/             # Node.js + Socket.IO backend
├── frontend/            # React + Tailwind frontend
├── assistant-api/       # FastAPI + LangChain assistant
├── .github/workflows/   # GitHub Actions CI/CD
└── docker-compose.yml   # Multi-service local setup

## 🚀 Getting Started
Clone the repository
Bash

git clone https://github.com/your-username/cortex-chat.git
cd cortex-chat
Add environment variables
Create .env files for each service (examples are provided in each folder).

Run locally with Docker Compose
Bash

docker-compose up --build
Access the app
Frontend: http://localhost:3000

Backend: http://localhost:5000

Assistant API: http://localhost:8000

## 📌 Roadmap Summary
✅ Chat UI with login & threading

✅ WebSocket backend with PostgreSQL persistence

✅ RAG-based assistant with file upload + Pinecone/FAISS

✅ Dockerized deployment & GitHub Actions for CI/CD

## 🛡️ Prerequisites
Node.js, Python 3.10+, Docker

OpenAI API Key (or Llama3 setup)

Pinecone/FAISS setup for vector DB

Basic knowledge of LangChain & FastAPI

## 📜 License
MIT License. Feel free to use, modify, and contribute!

Made with ❤️ by Sarvesh Waghmare