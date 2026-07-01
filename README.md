# 🧬 An Evidence-Centric AI Pipeline for Protein–Disease Regulation Identification

> An interpretable computational framework for identifying protein–disease regulatory relationships through evidence-centric literature mining and natural language processing.

---

## Overview

Understanding whether a protein promotes or suppresses disease is fundamental for target identification, biomarker discovery, and therapeutic development.

This project presents an evidence-centric computational framework that systematically integrates experimentally validated information from biomedical literature to infer protein–disease regulatory roles.

Unlike predictive or black-box AI models, this framework emphasizes **interpretability**, **traceability**, and **biological evidence**, enabling every regulatory inference to be linked back to supporting scientific literature.

> **Note:** This repository documents the methodology, workflow, and project outcomes presented at **SYMBIOT'26**. The implementation code is intentionally withheld as the work is part of ongoing research intended for future publication.

---

## Objectives

- Retrieve protein–disease evidence from biomedical literature
- Extract regulatory statements using domain-specific NLP
- Classify regulatory direction
- Filter experimentally validated evidence
- Aggregate weighted evidence
- Infer consensus regulatory roles
- Produce interpretable and traceable outputs

---

## Workflow

```
PubMed Literature Retrieval
            │
            ▼
Sentence Extraction (BioBERT)
            │
            ▼
Regulatory Classification
Positive | Negative | Neutral
            │
            ▼
Experimental Evidence Filtering
            │
            ▼
Weighted Evidence Scoring
            │
            ▼
Consensus Regulatory Role
            │
            ▼
Traceable Results
```

A graphical representation of the complete workflow is available in the **figures** directory.

---

## Key Features

- Evidence-centric AI framework
- Domain-specific NLP
- BioBERT-assisted sentence extraction
- Experimental evidence filtering
- Weighted evidence aggregation
- Direction-aware regulatory inference
- Literature traceability through PubMed IDs
- Transparent computational workflow

---

## Technologies & Resources

### Programming

- Python

### Natural Language Processing

- BioBERT

### Literature Sources

- PubMed

### Biological Databases

- NCBI
- UniProt
- Protein Data Bank (PDB)

---

## Case Study

The framework was demonstrated using **BRCA1** in breast cancer.

Example outputs included:

- Evidence sentence extraction
- Regulatory direction classification
- Weighted evidence aggregation
- Consensus regulatory role inference

The inferred regulatory role was consistent with BRCA1's established tumour suppressor function.

---

## Preliminary Evaluation

The initial evaluation demonstrated encouraging performance for regulatory direction classification.

Highlights include:

- Direction-aware sentence classification
- Balanced precision and recall
- Biological consistency with established literature

Detailed figures are available in the repository.

---

## Repository Structure

```
protein-disease-ai-pipeline/

├── documentation/
├── datasets/
├── figures/
├── presentation/
├── references/
└── README.md
```

---

## Presentation

This work was presented at:

**SYMBIOT'26**
3rd International Conference on Medicine, Biological Sciences & Omics Technologies

Manipal Institute of Technology

March 2026

---

## Future Directions

- Full-text biomedical literature mining
- Context-aware regulatory reasoning
- Multi-omics integration
- Pathway-level validation
- Large-scale regulatory network reconstruction

---

## Research Status

🚧 Ongoing academic research.

The computational implementation and source code are intentionally not included because the project forms part of ongoing research intended for future publication.

---

## Author

**Krithika V**

M.Sc. Computational Molecular Sciences

Manipal Institute of Technology

Computational Biology • Bioinformatics • Drug Discovery Informatics
