# MentorMind

MentorMind is an AI-powered learning mentor that uses Retrieval-Augmented Generation (RAG) to provide context-aware guidance based on user-provided learning materials.

## Features

- Processes PDF and TXT learning resources
- Splits documents into searchable text chunks
- Generates embeddings using `nomic-embed-text` via Ollama
- Stores and retrieves relevant content with ChromaDB
- Uses semantic search to return the most relevant context for each query
- Designed to support personalized, context-aware learning interactions

## Architecture

The project is organized into separate frontend, backend, and data components.  
The RAG pipeline handles document ingestion, embedding, vector storage, retrieval, and response generation.

## Tech Stack

- Python
- JavaScript
- Ollama
- nomic-embed-text
- ChromaDB
- Retrieval-Augmented Generation (RAG)


## Contributions

- **Mina Ezo Aycı** — RAG pipeline integration, vector retrieval, prompt workflow design, and overall system integration
- **Cansu Culu** — Backend development, frontend development, AI response integration, prompt handling, and UI/UX
- **Shared** — RAG architecture decisions, testing, debugging, and evaluation
