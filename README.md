# Agentic RAG Assistant

**Agentic customer support assistant** built with LangChain, pgvector, and Groq.

## Overview

This project implements a Retrieval-Augmented Generation (RAG) customer support assistant that answers user questions by retrieving relevant knowledge base entries and generating grounded responses, orchestrated as an agent rather than a single-shot RAG chain.

## Knowledge Base

Built on the Bitext Customer Support LLM Chatbot Training Dataset: 26,872 customer support Q&A pairs spanning 27 intent categories.

## Tech Stack

| Layer | Technology |
|---|---|
| Orchestration | LangChain |
| Vector store | PostgreSQL with pgvector |
| LLM inference | Groq |

## Project Structure

```
src/
app.py
requirements.txt
```

> Confirm this matches the current repo layout, and add details on the retrieval strategy and agent tool design if this README should go deeper.

## Running Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

> Confirm the exact run command matches `app.py`'s framework (Streamlit assumed here based on the entry-point filename).

## Known Limitations

- Retrieval strategy and agent architecture details are not fully documented here yet

## Author

Satryo Akbar Nurizki - [GitHub](https://github.com/srnurizki)
