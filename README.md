# ☕ Cafe FAQ Chatbot for Startups

> Your café’s personal AI assistant — built to answer all customer questions 24/7.

---

## 🧠 About the Project

**Cafe FAQ Chatbot** is an intelligent, open-source chatbot tailored for **newly launched or small cafés** that need a cost-effective customer support solution.

This chatbot uses state-of-the-art **language models and vector databases** to understand user queries and provide instant, accurate answers — using your own documents like **menus (PDF)**, **FAQs (TXT)**, and **offers (CSV)**.

---

## 🔍 Use Case

Whether you are:

- A café owner wanting to **automate responses**
- A startup café without a dedicated support team
- A developer looking to integrate **LangChain-based retrieval QA**

This project is your plug-and-play solution!

---

## 📂 Files Included




---

## ⚙️ Tech Stack

- 🧩 LangChain
- 🤗 HuggingFace Transformers (`FLAN-T5`)
- 📚 FAISS for vector storage
- 🧠 Sentence Transformers for embedding
- 📄 Multi-format loaders (PDF, TXT, CSV)
- 🛠 Google Colab-compatible

---

## 🚀 Setup Instructions

### 1. 📥 Upload Files

Open the notebook and upload:

- `menu.pdf`
- `faq.txt`
- `offers.csv`

These will be used to answer customer queries!

### 2. ✅ Install Dependencies (Automatically handled)

```python
!pip install -U langchain langchain-community langchainhub transformers accelerate huggingface_hub --quiet
!pip install -U sentence-transformers faiss-cpu pypdf --quiet
