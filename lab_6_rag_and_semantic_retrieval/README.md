# Lab 6 - RAG and Semantic Retrieval

## Overview

This laboratory explored Retrieval-Augmented Generation (RAG) systems and semantic retrieval techniques for improving question answering capabilities in Large Language Models.

The project focused on integrating semantic search and vector-based retrieval mechanisms with transformer language models in order to generate more reliable, contextualized, and factually grounded responses.

The implementation was developed using:
- LangChain
- HuggingFace Transformers
- Sentence Transformers
- FAISS
- PyTorch
- Python

---

## Objectives

The main goals of the laboratory were:

1. Understand semantic retrieval systems
2. Build a Retrieval-Augmented Generation (RAG) pipeline
3. Generate embeddings for semantic search
4. Create a vector database for document retrieval
5. Experiment with chunking strategies
6. Improve factual grounding in language generation

---

## Semantic Retrieval

The laboratory explored how semantic embeddings can be used to retrieve relevant information from external documents.

Unlike keyword-based retrieval systems, semantic retrieval allows the model to:
- capture contextual meaning
- retrieve semantically related passages
- improve information relevance
- support natural language queries

The workflow included:
- document preprocessing
- chunk generation
- embedding computation
- vector indexing
- similarity-based retrieval

---

## Embedding Generation

The project used transformer-based embedding models to generate vector representations of textual chunks.

The embeddings enabled:
- semantic similarity search
- contextual retrieval
- vector comparison
- nearest-neighbour search

These vector representations were stored inside a FAISS vector database for efficient retrieval.

---

## Vector Database

The laboratory used:

```text
FAISS
```

---

## Repository Structure

```text id="2o1q5n"
lab_6_rag_and_semantic_retrieval/
├── notebook/
├── results/
└── README.md


