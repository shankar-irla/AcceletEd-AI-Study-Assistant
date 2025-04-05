# 🤖 AcceletEd — Personalized AI Study Assistant

Welcome to **AcceletEd**, a lightweight, offline, and personalized AI study assistant built using open-source tools like **Transformers**, **FAISS**, and **RAG (Retrieval-Augmented Generation)**. This tool helps you ask questions and get intelligent answers based on your own study materials — all without needing cloud access or API keys.

---

## 🧠 What It Does

- Converts your study notes or content into **vector embeddings**
- Stores them in a **FAISS index** for fast retrieval
- Uses **Retrieval-Augmented Generation (RAG)** to answer questions
- Works **entirely offline** in a Kaggle Notebook or local environment

---

## 🚀 Live Demo on Kaggle

📘 [Click here to explore the full notebook on Kaggle](https://www.kaggle.com/code/irlagangasivashankar/acceleted-personalized-ai-study-assistant-updated/)

---

## 🛠️ Tech Stack

| Tool                   | Purpose                          |
|------------------------|----------------------------------|
| 🤗 Transformers         | Language generation              |
| 🧠 Sentence Transformers | Text embeddings                  |
| 🔍 FAISS                | Fast vector search               |
| 🔗 RAG                  | Combines retrieval + generation |
| 🧪 Kaggle               | Runs everything offline          |

---

## 📦 Features

- 💡 Works completely **offline** — no API keys needed
- 📄 Custom knowledge base (add your own notes)
- 🔎 Ask questions and get context-aware answers
- 🧪 Runs inside **Kaggle** notebooks or your local setup
- 🧰 Easy to modify, extend, and fine-tune

---

## 🧑‍💻 How to Use

1. Clone this repo or download the notebook  
2. Install required packages:
   ```bash
   pip install transformers sentence-transformers faiss-cpu
Replace the sample docs = [...] with your own text notes

Ask a question and get smart, contextual responses using RAG!

✨ What You Can Add Next
📄 Upload and parse your own PDFs

🖼️ Add a Gradio or Streamlit interface

🔁 Support multi-turn conversations

💾 Store FAISS indexes persistently

💬 Train on semester notes, PDFs, Q&A dumps

📌 Project Info
Project Title: AcceletEd — Personalized AI Study Assistant

Creator: Shankar Irla

Built With: 🤖 Transformers, 🧠 FAISS, 📚 RAG, 💬 Sentence Transformers

Capstone For: Gen AI Intensive Course – Kaggle x Google

🔗 Connect
🧑‍💻 “Active | Shine | Rise. Explore to Connect. Share Your World, Your Way.”

📌 Star ⭐ the repo
🎯 Fork it and try on your own notes
💬 Feel free to contribute or raise issues!
