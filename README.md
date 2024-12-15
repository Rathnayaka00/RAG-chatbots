# Retrieval-Augmented Generation (RAG) Chatbots

This repository contains two implementations of Retrieval-Augmented Generation (RAG) chatbots using OpenAI's GPT-3.5 Turbo and HuggingFace's Mistral-7B models. The chatbots are designed to provide intelligent and context-aware responses by integrating retrieval mechanisms with Large Language Models (LLMs).

---

## Features

### 1. Conversational RAG Chatbot with OpenAI
- Uses OpenAI GPT-3.5 Turbo for conversational AI.
- Processes PDF documents and splits them into retrievable chunks.
- Integrates history-aware retrieval for context-rich interactions.
- Implements Chroma for efficient vector storage and retrieval.

### 2. Open-Source RAG Chatbot with HuggingFace
- Leverages HuggingFace's Mistral-7B model for open-source conversational AI.
- Uses SentenceTransformers for embedding creation.
- Builds RAG pipelines with PyPDF document loaders and Chroma retrievers.
- Fine-tuned for answering questions based on document context.

---

## Technology Stack
- **Programming Language**: Python
- **Libraries**: LangChain, Transformers, Chroma, SentenceTransformers, PyPDF
- **Model APIs**:
  - OpenAI GPT-3.5 Turbo
  - HuggingFace Mistral-7B
- **Deployment**: Google Colab environment

---

## Getting Started

### Prerequisites
- Python 3.9 or higher
- Access to OpenAI API for GPT-3.5 Turbo
- HuggingFace API token for Mistral-7B

### Installation
Clone the repository and install the required dependencies:
```bash
git clone https://github.com/<your-username>/rag-chatbots.git
cd rag-chatbots
pip install -r requirements.txt

