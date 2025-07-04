# 🧠 Wikipedia Q&A Assistant

A dynamic chatbot that retrieves Wikipedia articles on-the-fly, indexes them into Pinecone using HuggingFace embeddings, and answers your questions using Groq's LLaMA3-70B model. Built with LangChain and fully memory-aware.

---

## 🚀 Features

- 🔍 **Dynamic Retrieval**: Fetches and indexes Wikipedia articles based on your first query.
- 🧩 **Chunking + Embedding**: Splits text and embeds it using `all-MiniLM-L6-v2`.
- 📦 **Vector Search**: Stores and searches context chunks in Pinecone.
- 💬 **Conversational Memory**: Remembers past interactions using LangChain's memory.
- 🤖 **Groq LLM**: Powered by ultra-fast `llama3-70b-8192` via Groq API.
- 💡 **Custom RAG Prompt**: Manually crafted prompt template for accurate, grounded answers.

---

## 📁 Project Structure

```bash
.
├── main.py               # Main chatbot script
├── .env                  # Stores API keys securely
├── requirements.txt      # All dependencies
└── README.md             # This file
