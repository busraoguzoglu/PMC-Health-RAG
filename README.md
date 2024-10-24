# PMC-Health-RAG

## Project Summary: Multimodal Summarization System for Health Research Papers

**Objective**:

Develop a **Retrieval-Augmented Generation (RAG)** system to summarize research papers focused on **TBD**, utilizing both textual and visual information from papers (e.g., figures, charts).

---

### Scope and Project Plan:

The project will focus specifically on **TBD**, narrowing down broad medical topics to areas such as:

- Gastrointestinal health
- Healthy eating habits

**TBD**

First PoC will focus on: **TBD**

- RAG
- Q&A From the system

Second Phase:

- Recipe recommendation
- Adding multimodal functionality
- Potentially using agentic architecture

## Tech Stack

### LLM/Multimodal:

Only open source models will be used for RAG and Multimodal functionality:

https://docs.llamaindex.ai/en/stable/examples/low_level/oss_ingestion_retrieval/

CLIP can be used for Multimodal functionality.

### VectorDB:

Pgvector is used as VectorDB (can be changed to Qdrant later, or both can be tested)

---

### Data

Papers about dietary habits will be gathered from: https://www.ncbi.nlm.nih.gov/pmc (PMC Open Access Subset)

---

### Progress - Code

- preprocessing.ipynb: PDF document parsing.
- Demo RAG code with Pgvector/Llama 2 is added and tested.
