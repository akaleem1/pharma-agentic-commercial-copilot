# pharma-agentic-commercial-copilot
Multi-agent, retrieval-augmented AI system simulating commercial intelligence workflows in regulated pharmaceutical environments. Built with Python, LangChain, and vector search to demonstrate enterprise-ready agent orchestration and responsible AI design.
## Current Status

### ✅ RAG Ingestion Pipeline Implemented
The following components are fully functional and tested:

- **Document loading** (text ingestion from `data/`)
- **Chunking strategy** using `RecursiveCharacterTextSplitter`
- **OpenAI embeddings** via `langchain-openai`
- **FAISS vector database** for fast similarity search
- **Retriever interface** using LangChain’s unified `.invoke()` API

This establishes a clean, modular foundation for retrieval‑augmented generation.

### 🔜 Next Step: Multi‑Agent Orchestration Layer
Upcoming work includes:

- Agent routing logic  
- Tool‑using agents for analytics, summarization, and commercial insights  
- Memory + context management  
- Evaluation harness for agent behavior  
