# GRAND-GatedFusion: Graph-based Vulnerability Detection Experiments

This repository contains experimental notebooks for evaluating the **SG-VUL** model on multiple benchmark datasets, including **Devign**, **DiverseVul**, and **Reveal**.  
Each notebook corresponds to a specific experimental configuration.

---

## Repository Structure
| File / Folder | Description |
|----------------|-------------|
| `dataset/` | Contains preprocessed datasets and intermediate files for Devign, DiverseVul, and Reveal. |
| `grand-devign.ipynb` | Baseline experiment of SG-VUL on the Devign dataset. |
| `grand-devign-parased.ipynb` | Experiment conducted on the parsable subset of the Devign dataset (code samples that can be successfully parsed). |
| `grand-devign-max8kinput.ipynb` | Experiment with a maximum input length of 8k tokens for long-sequence evaluation. |
| `grand-devign-cut-2k-alltest.ipynb` | Implementation of the **Chunk Strategy**, segmenting large code samples into 2k-token windows for inference. |
| `grand-diversevul.ipynb` | Evaluation of SG-VUL on the Diversevul dataset.|
| `grand-reveal.ipynb` | Evaluation of SG-VUL on the Reveal dataset. |
---
