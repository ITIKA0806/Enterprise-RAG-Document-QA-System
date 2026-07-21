# Enterprise RAG Document QA System

An **Enterprise Retrieval-Augmented Generation (RAG)** system that enables intelligent question answering over PDF documents by combining **semantic search** with **OpenAI GPT**. The system retrieves the most relevant document content from a vector database before generating accurate, context-aware responses.

---

## Project Overview

Large Language Models (LLMs) are powerful, but they cannot answer questions about documents they have never seen. This project implements a complete **Retrieval-Augmented Generation (RAG)** pipeline that first retrieves relevant information from enterprise PDF documents and then uses an LLM to generate grounded answers.

The project demonstrates the complete workflow of:

- PDF document ingestion
- Document preprocessing and chunking
- Semantic embedding generation
- Vector database storage
- Semantic document retrieval
- Context-aware response generation using OpenAI GPT

---

## Features

- Load and process multiple PDF documents
- Automatic document chunking for efficient retrieval
- Generate semantic embeddings using Sentence Transformers
- Store embeddings in ChromaDB vector database
- Retrieve the most relevant document chunks using similarity search
- Generate context-aware responses with OpenAI GPT
- Modular and object-oriented implementation
- End-to-end Retrieval-Augmented Generation (RAG) pipeline

---

## Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Framework | LangChain |
| Vector Database | ChromaDB |
| Embedding Model | Sentence Transformers |
| LLM | OpenAI GPT |
| PDF Processing | PyMuPDF, PyPDF |
| Environment | Jupyter Notebook |

---

# Project Workflow

```text
                PDF Documents
                      │
                      ▼
            Document Ingestion
                      │
                      ▼
             Document Chunking
                      │
                      ▼
          Semantic Embedding Generation
                      │
                      ▼
           ChromaDB Vector Store
                      │
                      ▼
          Semantic Document Retrieval
                      │
                      ▼
             OpenAI GPT Generation
                      │
                      ▼
              Final Contextual Answer
```

---

## Repository Structure

```text
Enterprise-RAG-Document-QA-System/
│
├── Enterprise_RAG_Document_QA_System.ipynb
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/ITIKA0806/Enterprise-RAG-Document-QA-System.git
```

Move into the project directory

```bash
cd Enterprise-RAG-Document-QA-System
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## API Configuration

This project requires an OpenAI API key.

Set the following environment variable before running the notebook.

```text
OPENAI_API_KEY=your_api_key_here
```

---

## Usage

1. Install all dependencies.
2. Configure the OpenAI API key.
3. Open the notebook:

```text
Enterprise_RAG_Document_QA_System.ipynb
```

4. Run the notebook from top to bottom.
5. Ask questions about the indexed PDF documents.

---

## Sample Pipeline

- Load PDF documents
- Split documents into semantic chunks
- Generate dense vector embeddings
- Store embeddings inside ChromaDB
- Retrieve the most relevant chunks
- Pass retrieved context to OpenAI GPT
- Generate grounded answers

---

## Future Enhancements

- Hybrid Search (Keyword + Semantic Search)
- Support for DOCX and TXT documents
- Conversational memory
- Streamlit web application
- Docker deployment
- Multi-document collections
- Metadata-based filtering

---

## Skills Demonstrated

- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- Prompt Engineering
- Semantic Search
- Vector Databases
- Embedding Models
- LangChain
- OpenAI API Integration
- Object-Oriented Programming
- Python Development

---

## Author

**Itika Singh**

Senior Data Analyst | AI & Data Analytics Enthusiast

GitHub: https://github.com/ITIKA0806
