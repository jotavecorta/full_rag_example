# 🔍 Modular RAG System with Haystack, OpenAI, and FAISS

A clean, extensible, and production-grade Retrieval-Augmented Generation (RAG) pipeline built with Haystack, OpenAI, and FAISS. Designed with OOP and SOLID principles to support scientific and enterprise search use cases.

---

## Features

-  Fully modular architecture (Retriever, Generator, Vector Store)
-  PDF ingestion with contextual chunking (text + scientific content)
-  Supports OpenAI or HuggingFace for embeddings and LLMs
-  Embeddable and extensible with clean class interfaces (Strategy Pattern)
-  Streamlit frontend for interactive querying and visualization
-  Production-ready design with testable components

---

## Project Structure
```
rag_system/
├── app/                # Streamlit frontend
├── generator/          # Generator strategies (OpenAI, Azure)
├── models/             # Document builders, summarizers
├── pipeline/           # RAGPipeline (Facade)
├── retriever/          # Retriever and vector store logic
└── main.py             # Console test interface
```

---

## Installation

```bash
git clone https://github.com/jotavecorta/full_rag_example.git
cd full_rag_example
pip install -r requirements.txt
```

