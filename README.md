# Offline_Session_1

# 📄 PDF Analyzer RAG Agent

A professional-grade **Retrieval-Augmented Generation (RAG)** application built with **Streamlit**, **LangChain**, and **FAISS**. This tool allows you to upload PDF documents, index them into a local vector store, and have a conversational chat with the document using OpenAI's GPT models.

## ✨ Features
* **Persistent Storage**: Indexes your PDF into a local `FAISS` database so you only process it once.
* **Context-Aware Chat**: Remembers previous questions in the conversation.
* **Efficient Retrieval**: Uses `RecursiveCharacterTextSplitter` for high-quality context window management.
* **Source Tracking**: Capable of identifying which part of the PDF the information came from.
* **Easy Reset**: One-click button to clear local storage and start fresh.

---

## 🛠️ Installation

### 1. Clone the repository
```bash
git clone [https://github.com/your-username/pdf-analyzer-rag.git](https://github.com/your-username/pdf-analyzer-rag.git)
cd pdf-analyzer-rag
