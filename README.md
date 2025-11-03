# 🧠 ClauseWise

ClauseWise is an **AI-powered legal document analyzer** that helps you **summarize, evaluate, and chat** with your uploaded contracts or PDFs.

It uses **Google Gemini** for generating clause-wise summaries, **GROQ** for intelligent question answering and contextual chat, and **MongoDB** for storing previous chat sessions — ensuring a seamless conversation experience even after page reloads.

---

## ✨ Features

- 📄 **Document Upload** – Supports PDF and DOCX files for analysis.  
- 🧩 **Clause-wise Summarization** – Uses Gemini API to generate concise clause-level summaries.  
- 💬 **Interactive Chat** – Ask questions about your document and get AI-generated responses using GROQ.  
- 💾 **Persistent Chat History** – Previous chat context is stored in MongoDB for continuity.  
- ⚡ **Fast & Intuitive UI** – Built with Streamlit for a simple, responsive interface.  
- 🔐 **Secure Environment Variables** – API keys and credentials stored safely in `.env`.

---

## 🛠️ Tech Stack

- **Frontend/UI:** Streamlit  
- **Backend:** Python  
- **AI Models:** Google Gemini (for summaries), GROQ (for text responses)  
- **Database:** MongoDB (for chat history)  
- **Frameworks & Tools:** LangChain, PyMuPDF / PDFPlumber, python-dotenv  

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/ManishPoudel-7/ClauseWise.git
cd ClauseWise
