# Lab 5 - Large Language Models

## Overview

This laboratory explored Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) systems for question answering over external knowledge bases.

The project focused on understanding the limitations of standalone language models and improving factual accuracy through semantic retrieval and document grounding techniques.

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

1. Explore the limitations of pretrained language models
2. Build a Retrieval-Augmented Generation (RAG) pipeline
3. Create a vector-based document retrieval system
4. Generate embeddings for semantic search
5. Experiment with chunking strategies
6. Improve factual accuracy using external knowledge bases

---

## Large Language Models

The laboratory explored the behaviour of modern transformer-based language models when answering factual questions without external retrieval systems.

A recent topic related to the 2024 music industry was used to evaluate:
- factual consistency
- hallucination behaviour
- pretrained knowledge limitations

The experiments demonstrated that standalone language models may produce:
- confident but incorrect answers
- outdated information
- hallucinated facts

This motivated the integration of retrieval mechanisms.

---

## Retrieval-Augmented Generation (RAG)

A Retrieval-Augmented Generation pipeline was implemented to combine:
- semantic retrieval
- vector search
- language generation

The workflow included:
1. document collection
2. PDF loading
3. document chunking
4. embedding generation
5. FAISS vector indexing
6. semantic retrieval
7. answer generation using retrieved context

This architecture allowed the model to ground its answers on external documents instead of relying exclusively on pretrained parameters.

---

## Document Processing

External documents were converted into PDF format and processed using:

```text
PyPDFLoader
```
---

## Repository Structure

```text id="2o1q5n"
lab_5_large_language_models/
├── notebook/
├── results/
└── README.md

