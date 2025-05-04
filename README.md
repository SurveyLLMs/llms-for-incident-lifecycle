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
## Research Quality

This repository includes high-quality research from some of the most prestigious conferences and journals in the field of software engineering, cloud computing, and distributed systems. The following sources have been surveyed and referenced: **ICSE**, **FSE**, **CLOUD**, **TSE**, **IEEE**, **arXiv**. These high-quality sources are key references for the methodologies, models, and experimental designs employed in this repository.

---

## 📂 Repository Structure

This repository is organized to facilitate research and experiments related to the evaluation of **Large Language Models (LLMs)** in the context of **Root Cause Analysis (RCA)**, **Mitigation Plan generation**, and **Auto-remediation**. The repository contains the following key directories:

## Directory Structure

```bash
.
├── Figures/                     # Contains figures for the evaluation of LLMs
│   ├── RCA_metrics.png          
│   ├── Mitigation_Plan_metrics.png  
│   └── Auto-remediation_metrics
│
├── Papers/                      # Contains papers categorized by research topics
│   ├── RCA/                     # Root Cause Analysis papers
│   │   ├── Adaptibility/        # Adaptibility-related papers
│   │   │   ├── LLMs_RCA_Adaptibility.xlsx
│   │   └── Dataset/             # Datasets for RCA research
│   │       ├── RCA_LLM_dataset.xlsx
│   │
│   ├── Mitigation Plan/         # Mitigation plan papers
│   │   ├── Adaptibility/        # Adaptibility-related papers
│   │   │   ├── LLMs_Mitigation_Plan_Adaptibility.xlsx
│   │   └── Dataset/             # Datasets for Mitigation Plan research
│   │       ├── Mitigation_Plan_LLM_dataset.xlsx
│   │
│   └── Auto-remediation/        # Auto-remediation papers
│       ├── Adaptibility/        # Adaptibility-related papers
│       │   ├── LLMs_Auto-remediation_Adaptibility.xlsx
│       └── Dataset/             # Datasets for Auto-remediation research
│           ├── Auto-remediation_LLM_dataset.xlsx
│   ├── List_survey_papers.pdf                    # list of papers surveyed

