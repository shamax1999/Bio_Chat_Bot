# 🧠 A/L Biology Chatbot
Live: https://33f9bbefa8d176a3bd.gradio.live/

RAG Architecture

<img width="2028" height="1742" alt="Bio Chat Bot drawio" src="https://github.com/user-attachments/assets/d18cbefb-aba3-4001-8c35-47a04e9fd092" />

An AI-powered chatbot that answers **Advanced Level Biology** questions by extracting knowledge from uploaded PDF textbooks.  
It uses **OCR** for scanned PDFs, **LangChain** for text processing, **FAISS** for vector search, and **Groq's LLaMA 3 model** for accurate answers.  
The chatbot runs on **Google Colab** and stores all data in **Google Drive**.  

---

## 🚀 Features
- 📄 **PDF Upload & OCR** – Extracts text from normal or scanned PDFs.
- 🗄 **Google Drive Integration** – Stores PDFs, extracted text, and vector index permanently.
- 📚 **Text Chunking** – Splits large documents into manageable parts for LLM processing.
- 🧩 **Semantic Search** – Uses FAISS vector store for fast retrieval.
- 🤖 **AI Model** – Powered by **Groq's LLaMA3-70B** via LangChain.
- 💬 **Gradio Interface** – Chat in a user-friendly web UI.
- 🔍 **Domain-Specific Knowledge** – Trained only on your provided A/L Biology materials.

---

## 🛠 Tech Stack
- **Python**
- **LangChain** – Text processing & LLM integration
- **Groq API** – LLaMA 3 large language model
- **HuggingFace Embeddings** – Sentence Transformers for vectorization
- **FAISS** – Fast similarity search
- **pytesseract** & **pdf2image** – OCR
- **Google Colab + Google Drive** – Storage & execution
- **Gradio** – Chat UI

---
## 📌 Usage

Upload one or more A/L Biology textbooks/notes PDFs.

The system extracts all content and stores it.

Ask any question related to the uploaded content in the chat interface.

Get precise, context-aware answers instantly.

---

## 🔐 Environment Variables

Create a .env file or set in Colab:

GROQ_API_KEY=your_groq_api_key_here
