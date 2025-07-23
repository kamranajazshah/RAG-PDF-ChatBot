# 🤖 RAG-PDF-ChatBot

A full-stack PDF-based Chatbot using Retrieval-Augmented Generation (RAG). Upload any PDF and ask questions — the chatbot will fetch answers grounded in the uploaded document.

---

## 🚀 Features

- 📄 Upload any PDF file
- 🔍 Ask natural language questions based on PDF content
- 🧠 Uses Retrieval-Augmented Generation (RAG)
- ⚡ FastAPI backend
- 🎨 Streamlit frontend
- 🐳 Dockerized for easy deployment
- 🔁 CI/CD pipeline with GitHub Actions

---

## 🧱 Tech Stack

| Layer        | Tool                   |
|--------------|------------------------|              |
| Frontend     | Streamlit              |
| LLM & RAG    | LangChain + OpenAI     |
| Embeddings   | OpenAI Embeddings      |
| Vector Store | FAISS                  |
| File Parsing | Py  PDF                |
| CI/CD        | GitHub Actions         |
| Deployment   | Docker                 |

---

## 📦 Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/kamranajazshah/RAG-PDF-ChatBot.git
cd RAG-PDF-ChatBot
