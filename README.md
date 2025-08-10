# ☕ Cafe FAQ Chatbot for Startups

> **Your café’s personal AI assistant** — answering all customer questions 24/7 ☕🤖

---

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![LangChain](https://img.shields.io/badge/LangChain-Framework-green?style=for-the-badge)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FLAN--T5-orange?style=for-the-badge&logo=huggingface)
![FAISS](https://img.shields.io/badge/FAISS-Vector%20DB-blueviolet?style=for-the-badge)
![GoogleColab](https://img.shields.io/badge/Google%20Colab-Compatible-yellow?style=for-the-badge&logo=googlecolab)

---

## 🧠 About the Project

**Cafe FAQ Chatbot** is an **intelligent, open-source chatbot** designed specifically for **newly launched or small cafés** that want a **cost-effective customer support solution**.  

It uses **state-of-the-art language models** + **vector databases** to understand queries and provide **instant, accurate answers** using your own café documents — such as:
- 📄 **Menus** (PDF)
- 📝 **FAQs** (TXT)
- 📊 **Offers & Deals** (CSV)

---

## 🔍 Use Case

Perfect for:
- 🏪 **Café owners** looking to automate customer responses
- 🚀 **Startup cafés** without a dedicated support team
- 👨‍💻 **Developers** who want to integrate **LangChain-based retrieval QA**

> ⚡ Just plug in your data and start answering customer questions instantly!

---

## ⚙️ Tech Stack

- 🧩 **LangChain** — orchestration & document loaders  
- 🤗 **HuggingFace Transformers** (`FLAN-T5`) — question answering model  
- 📚 **FAISS** — vector storage for fast search  
- 📄 **Multi-format Loaders** — PDF, TXT, CSV  
- 💻 **Google Colab-compatible** — easy to run without local setup

---

## 🚀 How It Works

1. 📥 Extracts content from PDF, TXT, and CSV files using **LangChain loaders**  
2. ✂️ Splits text into manageable chunks for processing  
3. 🧠 Generates embeddings using HuggingFace **Sentence Transformers**  
4. 📦 Stores embeddings in a **FAISS** vector database  
5. 💬 Uses **FLAN-T5** for natural and accurate Q&A responses  
6. 🔄 Runs in a **chat loop** to keep the conversation going

---

## 🛠 Setup Instructions

### 1️⃣ Upload Files
In the notebook, upload:
- `menu.pdf`
- `faq.txt`
- `offers.csv`

These files will be used as the chatbot’s **knowledge base**.
