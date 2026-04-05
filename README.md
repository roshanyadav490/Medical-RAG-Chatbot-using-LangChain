#  Medical RAG Chatbot using LangChain

This project is a Retrieval-Augmented Generation (RAG) based medical chatbot built using LangChain.

It answers user queries by retrieving relevant information from a medical PDF document and generating responses using Google Generative AI.

## Features
- RAG-based question answering system
- PDF-based medical knowledge retrieval
- Context-aware responses using LLM
- Lightweight backend (no UI)

## Tech Stack
- Python
- LangChain
- Google Generative AI (LLM)
- ChromaDB (Vector Database)
- PDF Loader

## How It Works
1. Load and process medical PDF
2. Split text into smaller chunks
3. Convert chunks into embeddings
4. Store embeddings in ChromaDB
5. Retrieve relevant context based on user query
6. Generate response using Google GenAI
