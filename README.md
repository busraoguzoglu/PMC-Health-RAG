# PMC-Health-RAG

## Project Summary: Multimodal Summarization System for Health Research Papers

**Medium Article**

https://medium.com/@busra.oguzoglu/fully-open-source-rag-with-llama-cpp-and-llava-images-included-ce9b66ab21df

**Objective**:

Develop a **Retrieval-Augmented Generation (RAG)** system to summarize research papers focused on **TBD**, utilizing both textual and visual information from papers (e.g., figures, charts).

---

### Scope and Project Plan:

The project will focus specifically on PMC public access papers, narrowing down broad medical topics to areas such as:

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

CLIP was considered Multimodal functionality.

LLaVa will be used to summarize images, the summarization will be embedded as text. (This design choice is based on the number, quality and the nature of the images.)

### VectorDB:

Pgvector is used as VectorDB (can be changed to Qdrant later, or both can be tested)

---

### Data

Papers about dietary habits will be gathered from: https://www.ncbi.nlm.nih.gov/pmc (PMC Open Access Subset)

---

### Progress - Code

- preprocessing.ipynb: PDF document parsing.
- llama_basic_rag.ipynb: RAG with only Llama2, only texts are being used.
- llama_llava_rag.ipynb: RAG with Llama2 for and Llava for the image summarization.
