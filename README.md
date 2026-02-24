# Project 2: Reproducibility in Natural Language Processing

## Project Overview

This repository contains a comprehensive exploration of Natural Language Processing (NLP) techniques applied to State of the Union address texts. The project demonstrates the progression from simple text processing methods to advanced semantic analysis, with a strong emphasis on reproducibility and collaborative practices.

**Course:** Statistics 159/259 (Fall 2025)  
**Instructors:** Prof. F. Pérez, GSI J. Butler, GSI S. Andrade  
**Department:** Department of Statistics, UC Berkeley  
**Due Date:** 11/21/2025, 11:59PM PT  

**Total Points:** 70 (with 7 points extra credit)  
**Course Weight:** 20% of final course grade

---

## Learning Objectives

### 1. Implement Modern NLP Pipelines

- **Load and Prepare Data:** Ingest and clean real-world text datasets using pandas
- **Process Text Efficiently:** Implement production-grade text pre-processing using spaCy
- **Understand Core Concepts:** Distinguish between tokens, lemmas, stop words, and punctuation; understand historical context of lemmatization in pre-LLM NLP

### 2. Conduct Core Text Analysis

- **Extract Linguistic Features:** Use spaCy to efficiently extract lemmas, parts-of-speech, and named entities
- **Perform Frequency Analysis:** Compare the most frequent words across different documents
- **Analyze Text Over Time:** Compare language evolution in presidential communication

### 3. Build and Compare Topic Models

- **Vectorize Text:** Apply TF-IDF (Term Frequency-Inverse Document Frequency) vectorization
- **Implement Traditional Topic Modeling:** Build and interpret Latent Dirichlet Allocation (LDA) models using gensim
- **Implement Modern Topic Modeling:** Leverage BERTopic with transformer embeddings, clustering, and semantic similarity
- **Critically Evaluate Models:** Analyze trade-offs between bag-of-words and semantic similarity approaches

### 4. Reproducibility and Collaboration

- Work on open-ended questions involving self-learning and external resource utilization
- Coordinate on teams to complete interdependent tasks
- Describe work in accessible formats with complete reproducibility

---

## Repository Structure


## Repository Structure
```
/statistics_analysis
    ├── notebooks/         # Jupyter notebooks containing analyses
    ├── data/             # Dataset files
    ├── scripts/          # Supporting scripts for data processing
    ├── results/          # Generated results and plots
    └── README.md         # This project documentation
```

## Binder Link
You can run the Jupyter notebooks in this repository using Binder. Use the link below to launch the environment:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kxvlar/Stat-159-proj-02/main?urlpath=lab)
