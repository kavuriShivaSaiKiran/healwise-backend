# HealWiseBackend

A **medical Q&A retrieval system** using LlamaIndex and HuggingFace embeddings, powered by OpenRouter LLMs.  
Users can query a medical knowledge base stored in CSVs, retrieve relevant documents, and generate concise answers while keeping track of source files.

---

## Features

- Retrieval-Augmented Generation (RAG) with HuggingFace medical embeddings
- Context-aware answers using OpenRouter LLMs (`meta-llama/llama-3.2`)
- Metadata tracking for CSV sources
- Compact or streaming responses
- Dynamic context selection based on query type

---

## Folder Structure
HealWiseBackend/
- data/ # CSV files with questions & answers
- vector_store/ # Persisted vector store
- .env # Environment variables (ignored in git)
- main.py # Main script for querying
- requirements.txt
- README.md
