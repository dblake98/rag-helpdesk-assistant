# rag-helpdesk-assistant

Portfolio project for hands-on experience with Amazon Bedrock using Python.

## Goal
Build a RAG helpdesk assistant that can answer questions over custom documents.

## Scope
Supported document types:
- PDF
- Markdown
- DOCX

## Architecture
- Next.js (frontend)
- FastAPI (backend)
- Amazon Bedrock (LLM + embeddings)
- Python (RAG pipeline)

## Features
- Document upload to trigger ingestion
- Chat interface for Q&A
- Refuse to answer when retrieval confidence is low
- Citations to consulted documents
