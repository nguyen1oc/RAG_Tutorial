# Simple RAG Pipeline with Gemini & Pinecone

This is a simple implementation of **Retrieval-Augmented Generation (RAG)** using **Gemini API** as the LLM and **Pinecone** as the vector database.

## Project Overview

- **RAG (Retrieval-Augmented Generation)** is an approach that enhances LLMs by retrieving relevant documents from a vector database before generating the final answer.
- In this project:
  - We use **Gemini API** for question-answering.
  - We store text embeddings in **Pinecone**.
  - Documents are loaded, embedded, stored in Pinecone, retrieved when a query is made, and then passed to Gemini for final answer generation.

## Features
- Document loading & preprocessing
- Embedding generation
- Indexing documents in Pinecone
- Retrieval of relevant documents
- Query answering using Gemini with retrieved context

## Tech Stack
- **Gemini API** (Google AI LLM)
- **Pinecone** (Vector Database)
- Python (OpenAI / Google Generative AI SDKs)

## Installation

```bash
git clone https://github.com/nguyen1oc/RAG_Tutorial
cd RAG_Tutorial
