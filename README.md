# PDF Knowledge Extraction RAG Bot

A Streamlit app that enables question answering over PDF documents using Retrieval-Augmented Generation (RAG) with embeddings and EURI's GPT API.

---

## Features

- Extract text from PDF files using `pdfplumber`.
- Split large text into chunks with overlap for better context.
- Generate embeddings for text chunks via EURI API.
- Build a FAISS vector store for fast similarity search.
- Retrieve relevant chunks based on user questions.
- Generate AI answers using EURI's GPT-4.1 Nano model.
- Maintain conversational memory for multi-turn Q&A.
- Simple, user-friendly Streamlit web interface.

---

## Demo

Upload your PDF, ask questions about its content, and get AI-generated answers instantly.
