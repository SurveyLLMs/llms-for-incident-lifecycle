# Survey on Large Language Models for Incident Lifecycle Automation in Cloud-Native Systems

This repository accompanies our comprehensive **Systematic Literature Review (SLR)** on the use of **Large Language Models (LLMs)** in automating the **incident management lifecycle** in cloud-native and autonomic computing environments. The survey analyzes 48 peer-reviewed publications, industrial tools, and open-source frameworks that leverage LLMs to improve reliability and reduce human effort in microservice-based systems. Recent advances in **Artificial Intelligence for IT Operations (AIOps)**, particularly the emergence of **LLMs**, have shown promise in automating core tasks such as:

- 🔍 Detection  
- ⚠️ Triaging  
- 🔧 Root Cause Diagnosis  
- 🛠️ Mitigation Planning  
- 🤖 Auto-remediation  
- 📝 Postmortem Analysis

This survey focuses on Root Cause Diagnosis, Mitigation Planning, Auto-remediation stages where LLMs demonstrate significant advantages, particularly in interpreting multimodal, unstructured observability data—logs, metrics, traces, and alerts (LMT+A).

---
## High Quality Research

This repository includes high-quality research from some of the most prestigious conferences and journals in the field of software engineering, cloud computing, and distributed systems. The following sources have been surveyed and referenced: **ICSE**, **FSE**, **CLOUD**, **TSE**, **IEEE**, **arXiv**. These high-quality sources are key references for the methodologies, models, and experimental designs employed in this repository.

---

## 📂 Repository Structure

```bash
.
├── paper/
│   ├── survey.pdf               # Final survey paper
│   └── references.bib           # BibTeX file with cited works
├── data/
│   ├── llm_models.csv           # List of LLMs used across studies
│   ├── tasks_mapping.csv        # Task ↔ LLM mapping (diagnosis, mitigation, etc.)
│   └── datasets_summary.csv     # Overview of datasets used
├── figures/
│   └── taxonomy_overview.png    # High-level figure from the paper
├── README.md                    # This file
└── LICENSE                      # License file
