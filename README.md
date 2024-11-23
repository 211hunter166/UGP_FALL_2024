# Enhancing Multimodal Spatial Omics Analysis with ContraGEM

Welcome to the official repository for our research project, *"Enhancing Multimodal Spatial Omics Analysis with Contrastive Learning."* This project focuses on advancing computational methods in spatial and multi-omics data integration through the development of **ContraGEM**, an improved version of GEM-VAE using contrastive learning.

## Project Overview

Spatial omics integrates molecular profiling and spatial context to analyze cell-cell communication, tissue organization, and disease markers. This project tackles challenges in spatial and multi-omics data integration, including scalability, spatial resolution, and alignment accuracy, by introducing innovative methodologies and benchmarking them against state-of-the-art models.

### Key Contributions
1. **Model Development**: Enhanced GEM-VAE into **ContraGEM** by integrating Info-NCE contrastive learning, improving spatial structure preservation and cluster accuracy.
2. **Dataset Simulation**: Generated realistic spatial multi-omics datasets using nonnegative spatial factorization, incorporating spatial transcriptomics and proteomics with ground truth.
3. **Comprehensive Benchmarking**: Compared ContraGEM with leading models, including SpatialGlue, STAGATE, GEM-VAE, and TotalVI, across datasets such as DLPFC Brain, Mouse Breast Cancer, and Human Lymph Node.
4. **Metrics Evaluation**: Demonstrated up to 10% improvements in clustering accuracy using metrics such as:
   - Adjusted Mutual Information (AMI): 0.33
   - Normalized Mutual Information (NMI): 0.34
   - Adjusted Rand Index (ARI): 0.19

---

## Features

- **ContraGEM**:
  - Utilizes Info-NCE contrastive learning to align multi-modal gene-protein embeddings.
  - Preserves spatial structures and improves cluster accuracy for complex datasets.
- **Synthetic Datasets**:
  - Simulated multi-omics data using nonnegative spatial factorization, incorporating known ground truth for rigorous benchmarking.
- **Benchmarking**:
  - Evaluated models on both simulated and real-world datasets, including:
    - **DLPFC Brain**: High granularity gene expression data.
    - **Mouse Breast Cancer**: Heterogeneous spatial domains with cancerous and non-cancerous regions.
    - **Human Lymph Node**: Rich spatial transcriptomics and proteomics data.

---

