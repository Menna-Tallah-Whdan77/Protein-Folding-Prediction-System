# Protein Folding Prediction System for Alzheimer's Disease

A computational bioinformatics project that leverages state-of-the-art deep learning to predict, visualize, and analyze the 3D structures of Amyloid-Beta and Tau proteins, which are central to Alzheimer's Disease pathology.

![Bioinformatics](https://img.shields.io/badge/Bioinformatics-Protein%20Folding-blue) ![Python](https://img.shields.io/badge/Python-Biopython%20%7C%20ESMFold-green) ![License](https://img.shields.io/badge/License-MIT-lightgrey)

## 📖 Overview

This project implements an end-to-end pipeline for protein structure analysis. It automates the retrieval of protein sequences, uses the revolutionary **ESM Fold** language model to predict their 3D structures, and provides tools for visualization and comparative analysis. The system is applied to key Alzheimer's Disease proteins—**Amyloid-Beta (Aβ)** and **Tau**—to investigate their misfolding and aggregation propensities.

## 🧬 Featured Proteins & Disease Relevance

- **Amyloid-Beta (Aβ):** A peptide that aggregates into oligomers and plaques, a primary hallmark of Alzheimer's. We analyze its sequence to understand its high aggregation tendency.
- **Tau Protein:** A microtubule-associated protein that forms neurofibrillary tangles in Alzheimer's brains. We explore its intrinsically disordered regions and their role in pathology.

## 🛠️ Tools & Technologies

*   **Programming Language:** Python
*   **Core Libraries:** Biopython, Pandas, NumPy
*   **Structure Prediction:** **ESM Fold** by Meta AI
*   **Visualization:** Py3Dmol, Matplotlib
*   **Data Sources:** UniProt, RCSB PDB

## 🚀 How It Works

The system workflow is as follows:

1.  **Sequence Retrieval:** Automatically fetches protein sequences from the UniProt database using their accession IDs.
2.  **Structure Prediction:** Sends the protein sequence to the ESM Fold model to generate a predicted 3D structure in PDB format.
3.  **Visualization:** Renders an interactive 3D model of the protein, highlighting secondary structures like alpha-helices and beta-sheets.
4.  **Analysis:** Analyzes the predicted structure, focusing on confidence scores (pLDDT) and identifying key structural motifs related to disease (e.g., exposed beta-strands in Aβ).

## 📊 Key Features & Demonstrations

This project provides detailed analysis for both proteins:

### Amyloid-Beta (Aβ)
*   **Visualization:** 3D model showing its predominantly beta-sheet structure.
*   **Prediction:** High-confidence prediction of the hydrophobic core that drives aggregation.
*   **Analysis:** Identification of "sticky" beta-strands that facilitate the formation of toxic oligomers and fibrils.

### Tau Protein
*   **Visualization:** 3D model highlighting its largely intrinsically disordered nature.
*   **Prediction:** Mapping of low-confidence regions that are flexible and prone to abnormal post-translational modifications.
*   **Analysis:** Correlation between structural disorder and susceptibility to forming pathological tangles.
