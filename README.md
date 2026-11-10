# DeutschMentor
Agentic AI and RAG Based Chatbot for learning German, created using Python, MySQL, Neo4j, LangGraph, ChromaDB and Streamlit.

## Overview
DeutschMentor is a Python-based learning assistant designed to help A1-level German learners practise vocabulary, grammatical gender, plural forms, and foundational grammar.

The project explores how retrieval-augmented generation (RAG), agentic workflows, and knowledge graphs can support accurate, structured, and interactive language learning.

## Objectives
- Retrieve relevant vocabulary and grammar information from a curated learning dataset.
- Generate explanations grounded in retrieved learning material.
- Route learner requests through structured workflows.
- Represent relationships between vocabulary, articles, and grammar concepts.
- Provide vocabulary quizzes, mistake review, and learning progress tracking.
- Evaluate retrieval quality, answer correctness, and workflow reliability.

## Technology Stack

- **Language:** Python
- **Development:** Google Colab, GitHub
- **Retrieval:** ChromaDB, sentence embeddings
- **Agent orchestration:** LangGraph
- **Knowledge graph:** Neo4j
- **Interface:** Streamlit
- **Persistence:** SQLite
- **Testing and evaluation:** Pytest, retrieval metrics, curated evaluation questions

## Planned Architecture

1. Curated vocabulary and grammar data
2. Data validation and ingestion
3. Vector-based retrieval
4. Context-grounded answer generation
5. LangGraph-based workflow routing
6. Neo4j knowledge graph integration
7. Quiz history and mistake review
8. Streamlit interface
9. Automated testing and evaluation

## Development Status

- [x] Project concept and initial scope
- [x] GitHub repository and development setup
- [ ] Vocabulary dataset
- [ ] Initial retrieval pipeline
- [ ] AI tutor
- [ ] LangGraph workflow
- [ ] Neo4j knowledge graph
- [ ] Quiz and progress tracking
- [ ] Streamlit interface
- [ ] Evaluation and testing

## Evaluation Plan

The project will evaluate retrieval quality, answer correctness, source grounding, intent routing, quiz grading, and handling of insufficient evidence.

## Disclaimer

This is a learning and portfolio project. German vocabulary and grammar data will be curated and validated, and model-generated explanations will be evaluated against trusted learning references.
