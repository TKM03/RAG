# RAG System - Retrieval Augmented Generation

A robust implementation of a Retrieval Augmented Generation (RAG) system combining vector search with language generation capabilities.

## Overview

This project implements a RAG system that:
- Uses FAISS for efficient vector similarity search
- Employs Sentence Transformers for embedding generation
- Integrates a language model (TinyLlama) for answer generation
- Provides an interactive interface for queries and document management

## Features

- **Dynamic Document Management**: Add new documents to the knowledge base at runtime
- **Efficient Retrieval**: FAISS-based vector search for fast context retrieval
- **Quality Generation**: Enhanced text generation with top-k and top-p sampling
- **Error Handling**: Robust error checking and graceful failure recovery
- **Interactive CLI**: User-friendly command-line interface
- **GPU Support**: Automatic CUDA utilization when available

## Prerequisites

- Python 3.8+
- PyTorch with CUDA support (optional, for GPU acceleration)
- Git
