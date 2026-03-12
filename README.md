# Pharma Agentic Commercial Copilot

Multi-agent, retrieval-augmented AI system simulating commercial intelligence workflows in regulated pharmaceutical environments. Built with Python, LangChain, and vector search to demonstrate enterprise-ready agent orchestration and responsible AI design.

---

## Current Status

### ✅ RAG Ingestion Pipeline Implemented
The following components are fully functional and tested:

- **Document loading** (text ingestion from `data/`)
- **Chunking strategy** using `RecursiveCharacterTextSplitter`
- **OpenAI embeddings** via `langchain-openai`
- **FAISS vector database** for fast similarity search
- **Retriever interface** using LangChain’s unified `.invoke()` API


Business Problem
Commercial organizations in pharma require rapid synthesis of clinical evidence, market dynamics, and regulatory risks. Manual workflows delay decision-making and reduce the ability to respond to emerging safety signals or competitive threats.

Architecture Overview
User → Streamlit UI → FastAPI → Orchestrator → Agents
→ RAG Retriever → FAISS Vector Store → OpenAI Models → Response

Tech Stack

- LangChain (agents, prompts, orchestration)
- FAISS (vector DB)
- OpenAI embeddings + chat models
- FastAPI (backend API)
- Streamlit (frontend UI)
- Modular multi-agent design (research, commercial, risk)


Responsible AI & Governance

This system incorporates:

- Audit logging for traceability  
- Human-in-the-loop review  
- Data privacy controls  
- Prompt role separation  
- Structured outputs for compliance workflows  

Future Enhancements

- Azure deployment with managed identity  
- Pinecone or Azure AI Search integration  
- Async parallel agent execution  
- Monitoring with Prometheus / Grafana  
- CI/CD integration  
