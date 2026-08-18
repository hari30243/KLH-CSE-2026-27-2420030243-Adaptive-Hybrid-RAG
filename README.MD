# Adaptive Hybrid RAG Framework for Context-Aware Document Intelligence

> AI Driven Language Technologies (ADLT) Course Repository  
> Department of Computer Science & Engineering | KLH University

---

# 📌 Course Project Information

**Course:** AI Driven Language Technologies (ADLT)

**Mini Project Title:**  
Hybrid RAG Framework for Intelligent Document Question Answering

**Major Project Title:**  
Adaptive Hybrid RAG Framework for Context-Aware Document Intelligence

This repository contains all project-related work, including documentation, literature survey, implementation, reports, presentations, evaluation results, and future enhancements developed as part of the AI Driven Language Technologies course.

---

# 👨‍💻 Team Members

| Name | Roll Number |
|------|-------------|
| Agastya Singh | 2420030690 |
| M HariHaran | 2420030243 |
| Challa Saketh Kumar | 2420030618 |
| Sanchay Krishna G | 2420090039 |

---

# 👨‍🏫 Faculty 

**Dr. K. Swanthana**

Department of Computer Science & Engineering

KLH University

---

# 📖 Project Abstract

The proposed project focuses on developing an **Adaptive Hybrid Retrieval-Augmented Generation (RAG) Framework** for intelligent document understanding.

The framework enables users to upload multiple documents (PDF, DOCX, TXT), retrieve relevant information using **Hybrid Retrieval (BM25 + Semantic Search with FAISS)**, and generate accurate context-aware answers using a Large Language Model (LLM).

The major project extends the basic Hybrid RAG pipeline by incorporating adaptive retrieval strategies, cross-document reasoning, contradiction detection, evidence strength estimation, explainable evidence navigation, and document summarization to improve transparency, reliability, and enterprise knowledge management.

---

# 🎯 Project Objectives

- Upload and process multiple documents
- Extract and preprocess document text
- Perform intelligent document chunking
- Generate semantic embeddings
- Store embeddings using FAISS
- Create BM25 keyword index
- Implement Hybrid Retrieval
- Extend to Adaptive Hybrid Retrieval
- Generate context-aware answers using an LLM
- Display source citations
- Highlight supporting evidence
- Support conversational document interaction
- Generate document summaries
- Detect contradictions across documents
- Estimate evidence strength

---

# 🛠️ Technologies Used

- Python
- LangChain
- FAISS
- BM25
- Sentence Transformers (BGE)
- Hugging Face Transformers
- Llama 3 / Mistral
- FastAPI
- Streamlit
- Git
- GitHub

---

# 📂 Repository Structure

```
.
├── src/
├── docs/
├── data/
├── results/
├── reports/
├── README.md
├── requirements.txt
└── .gitignore
```

### Folder Description

**src/**  
Source code including backend, frontend, document processing, retrieval, embeddings, and utility modules.

**docs/**  
Architecture diagrams, literature survey, research notes, design documents, and technical documentation.

**data/**  
Sample datasets, document references, and dataset descriptions.

**results/**  
Experimental results, screenshots, benchmark evaluations, and demo outputs.

**reports/**  
Presentation slides, review submissions, and project reports.

---

# ⚙️ Getting Started

Clone the repository

```bash
git clone https://github.com/<username>/<repository-name>.git
```

Navigate to the repository

```bash
cd <repository-name>
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

> The setup instructions will be updated as development progresses.

---

# 📅 Development Status

| Phase | Status |
|--------|--------|
| Project Planning | ✅ Completed |
| Literature Survey | ✅ Completed |
| Research Gap Identification | ✅ Completed |
| System Architecture | 🔄 In Progress |
| Implementation | ⏳ Upcoming |
| Testing & Evaluation | ⏳ Upcoming |

---

# 📊 Expected Outcomes

- Hybrid document retrieval using BM25 and FAISS
- Context-aware document question answering
- Explainable AI with source highlighting
- Adaptive retrieval strategy
- Cross-document reasoning
- Contradiction detection
- Evidence strength estimation
- Intelligent enterprise document analysis

---

# 📌 Repository Guidelines

- Follow weekly commits with meaningful commit messages.
- Each team member contributes using their own GitHub account.
- Maintain documentation for every development phase.
- Tag important milestones (Review-1, Review-2, Final).
- Do not upload API keys, credentials, or confidential datasets.

---

# 📄 Acknowledgement

This repository is maintained as part of the **AI Driven Language Technologies (ADLT)** course offered by the Department of Computer Science & Engineering, KLH University.

The repository serves as the central workspace for tracking project progress, documentation, implementation, evaluation, and deliverables throughout the course.