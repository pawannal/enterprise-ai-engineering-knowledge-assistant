# Enterprise AI Engineering Knowledge Assistant (EAIKA)

## Overview

Enterprise AI Engineering Knowledge Assistant (EAIKA) is a production-oriented Retrieval-Augmented Generation (RAG) platform designed to help users discover, retrieve, and reason over organization-specific knowledge.

The platform combines Azure AI Foundry, Azure OpenAI, Azure AI Search, Hybrid Retrieval, and modern GenAI engineering practices to deliver grounded and explainable answers from trusted knowledge sources.

This project is being built incrementally following production-grade engineering principles rather than tutorial-style development.

---

## Problem Statement

Organizations store knowledge across multiple documents, guides, policies, architecture documents, and technical references.

Traditional search often returns too many results and requires users to manually review documents.

Large Language Models alone cannot reliably answer organization-specific questions because they do not have access to private enterprise knowledge.

EAIKA solves this problem by combining retrieval and generation to provide accurate, contextual, and source-grounded answers.

---

## Goals

* Build a production-grade Enterprise Knowledge Assistant
* Learn modern GenAI engineering practices
* Implement Retrieval-Augmented Generation (RAG)
* Support Hybrid Search (Keyword + Vector)
* Provide citations and source transparency
* Introduce evaluation and observability
* Evolve toward Agentic AI capabilities

---

## Technology Stack

### AI & Retrieval

* Azure AI Foundry
* Azure OpenAI
* GPT-4.1-mini
* Azure OpenAI Embeddings
* Azure AI Search

### Backend

* Python
* FastAPI

### Infrastructure

* Azure Blob Storage
* Docker

### Future Enhancements

* Microsoft Entra ID
* React Frontend
* Agentic Retrieval
* Evaluation Frameworks
* Observability & Tracing

---

## Architecture

### Indexing Pipeline

Documents
→ Blob Storage
→ Chunking
→ Embeddings
→ Azure AI Search Index

### Query Pipeline

User Question
→ Embedding Generation
→ Hybrid Search
→ Context Retrieval
→ Prompt Builder
→ GPT-4.1-mini
→ Answer with Citations

---

## Repository Structure

docs/

* architecture
* decisions
* diagrams

infrastructure/

ingestion/

backend/

frontend/

evaluation/

tests/

notebooks/

---

## Roadmap

### Phase 1

* Foundation Chat Application
* Azure OpenAI Integration
* Responses API

### Phase 2

* Production RAG Foundation
* Document Ingestion
* Embeddings
* Azure AI Search
* Hybrid Search

### Phase 3

* Evaluation Framework
* Observability
* Tracing
* Quality Metrics

### Phase 4

* Agentic Knowledge Assistant
* Tool Calling
* Multi-Step Retrieval
* Memory

---

## Learning Objectives

This project focuses on understanding:

* Why RAG is needed
* How embeddings work
* Chunking strategies
* Hybrid retrieval
* Prompt construction
* Evaluation methodologies
* Production GenAI architecture
* Agentic AI systems

---

## Status

🚧 Active Development

