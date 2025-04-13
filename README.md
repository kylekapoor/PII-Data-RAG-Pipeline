# 🔐 PII Data RAG Pipeline

A Retrieval-Augmented Generation (RAG) pipeline designed for querying high-volume, classified datasets containing personally identifiable information (PII). Built for secure and scalable enterprise-level document QA using LangChain, Pinecone, and OpenAI.

---

## 💡 Overview

Processes and indexes over **5TB** of synthetic PII data into vector databases to enable fast, relevant, and accurate document-specific query resolution using LLMs.

---

## 🛠️ Tech Stack

- **Languages:** Python  
- **Libraries:** NumPy, LangChain, Pinecone, OpenAI, HuggingFace, Groq  
- **Data Sources:** Synthetic Kaggle datasets  

---

## ⚙️ Features

- 📄 Document chunking and embedding via LangChain + OpenAI  
- 📦 Vector store retrieval with Pinecone  
- 🧠 LLM-backed summarization and query resolution  
- ⚡ Groq acceleration for high-throughput inference  

---

## 🚀 Getting Started

```bash
git clone https://github.com/kylekapoor/pii-rag-pipeline
cd pii-rag-pipeline
pip install -r requirements.txt
python pipeline.py
