
---

### 📁 Project 2: **PII Data RAG Pipeline**

```markdown
# 🔐 PII Data RAG Pipeline

A Retrieval-Augmented Generation (RAG) pipeline designed for querying high-volume, classified datasets with personally identifiable information (PII). Built to simulate private enterprise LLM use-cases on secure data using LangChain and Pinecone.

---

## 💡 Overview

Processes and indexes over 5TB of synthetic PII data into vector databases for fast, relevant LLM-based document QA. Designed with privacy, scale, and modularity in mind.

---

## 🔧 Tech Stack

- **Languages**: Python
- **Libraries**: NumPy, LangChain, Pinecone, OpenAI, HuggingFace, Groq
- **Data Sources**: Synthetic Kaggle datasets

---

## ⚙️ Features

- 📄 Document chunking and embedding via LangChain + OpenAI
- 🧠 Vector store retrieval with Pinecone
- 🔄 LLM-backed summarization + query resolution
- 🚀 Groq acceleration for high-throughput inference

---

## 🚀 Getting Started

```bash
git clone https://github.com/kylekapoor/pii-rag-pipeline
cd pii-rag-pipeline
pip install -r requirements.txt
python pipeline.py
