# 🧠 Retrieval-Augmented Generation (RAG) Chatbot

This project demonstrates a simple **Retrieval-Augmented Generation (RAG)** chatbot using the **LangChain** framework and **OpenAI** embeddings. It allows users to upload a custom text file and interact with it via natural language questions using a Flask-Ngrok interface in Google Colab.

---

## 🚀 Features

- Upload your own `.txt` file and ask questions about it
- Uses **OpenAI Embeddings** and **ChromaDB** for vector storage
- Built using **LangChain's RetrievalQA** chain
- Local chatbot interface via terminal input
- Google Colab compatible

---

## 🛠️ Tech Stack

- Python  
- [LangChain](https://github.com/langchain-ai/langchain)  
- OpenAI API  
- ChromaDB  
- Flask + Ngrok  
- Google Colab environment

---

## 📦 Installation

Use in Google Colab or run locally after installing dependencies:

```bash
pip install openai langchain langchain-community tiktoken chromadb flask-ngrok
