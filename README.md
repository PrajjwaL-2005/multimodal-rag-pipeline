## Overview
This project implements a multi-modal Retrieval-Augmented Generation (RAG) pipeline
that retrieves relevant context from unstructured documents before generating answers
using an LLM.

## Key Concepts
- Retrieval-Augmented Generation (RAG)
- Document ingestion using Unstructured.io
- Semantic search using vector embeddings
- Context-grounded answer generation

## Tech Stack
- Python
- LangChain
- Unstructured.io
- Vector Database (Chroma / FAISS)
- OpenAI / LLM

## What I Learned
- How retrieval quality directly affects LLM output
- Why chunking and document structure matter in RAG
- How to reduce hallucination using prompt constraints

## Note
The notebook includes execution outputs to demonstrate the full RAG pipeline
running end-to-end, including retrieval and generation steps.
