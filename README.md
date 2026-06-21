# MedRAG: Production Medical RAG System

**End-to-End Retrieval-Augmented Generation (RAG) System** for querying patient records using natural language — Built for production use.

## Overview

A robust **Medical RAG Assistant** that allows doctors and clinicians to ask natural language questions over structured patient data stored in PostgreSQL and receive accurate, context-aware answers powered by LLMs.

**Developed**: March 2025 – Present

## Key Features

- **Natural Language Querying** over structured clinical data
- **End-to-End Data Pipeline**: Extraction → Cleaning → Deduplication → Transformation into LLM-ready documents
- **Semantic Search** using embeddings for highly relevant context retrieval
- **Production-grade Architecture** with hallucination reduction techniques
- **Interactive Chatbot** interface for clinical users

## Tech Stack

- **LLM Orchestration**: LangChain
- **Vector Database**: ChromaDB
- **Embeddings**: Ollama (local) / OpenAI compatible
- **Database**: PostgreSQL
- **Frontend**: Streamlit
- **Backend**: Python + FastAPI (optional)

## Architecture

1. **Data Pipeline**
   - Extract data from PostgreSQL
   - Clean, deduplicate, and enrich clinical records
   - Convert into structured + semantic chunks with metadata

2. **Retrieval System**
   - Semantic embedding generation
   - Hybrid retrieval (vector + keyword)
   - Metadata filtering

3. **Generation**
   - Prompt engineering for medical accuracy
   - Context-grounded response generation
   - Hallucination mitigation strategies

4. **User Interface**
   - Clean Streamlit chatbot interface
   - Source citation and confidence display

## Project Structure
