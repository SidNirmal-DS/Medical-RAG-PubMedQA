# Medical-RAG-PubMedQA

This project implements a Retrieval-Augmented Generation (RAG) model for medical question-answering using the PubMedQA dataset. The system retrieves relevant research papers and generates responses using a fine-tuned language model.

## Project Overview

This RAG-based system is designed to improve factual accuracy and reduce hallucinations in AI-generated answers by integrating document retrieval with text generation.

### Features

- Retrieves relevant medical contexts using FAISS for efficient similarity search.
- Utilizes a fine-tuned FLAN-T5 model for answer generation.
- Processes the PubMedQA dataset to enhance domain-specific responses.
- Efficient document retrieval using embeddings.
- Can be deployed via FastAPI for real-time inference.

## Installation and Setup

To install the required dependencies, run:

```bash
pip install -U langchain faiss-cpu transformers torch==2.5.1 torchaudio==2.5.1 torchvision==0.20.1 sentence-transformers pymupdf datasets fastapi uvicorn fsspec==2024.6.1 gcsfs==2024.6.1

# Medical-RAG-PubMedQA

This project implements a Retrieval-Augmented Generation (RAG) model for medical question-answering using the PubMedQA dataset. The system retrieves relevant research papers and generates responses using a fine-tuned language model.

## Project Overview

This RAG-based system is designed to improve factual accuracy and reduce hallucinations in AI-generated answers by integrating document retrieval with text generation.

### Features

- Retrieves relevant medical contexts using FAISS for efficient similarity search.
- Utilizes a fine-tuned FLAN-T5 model for answer generation.
- Processes the PubMedQA dataset to enhance domain-specific responses.
- Efficient document retrieval using embeddings.
- Can be deployed via FastAPI for real-time inference.

## Installation and Setup

To install the required dependencies, run:

```bash
pip install -U langchain faiss-cpu transformers torch==2.5.1 torchaudio==2.5.1 torchvision==0.20.1 sentence-transformers pymupdf datasets fastapi uvicorn fsspec==2024.6.1 gcsfs==2024.6.1
]
