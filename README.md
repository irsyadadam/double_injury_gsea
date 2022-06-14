![hello](https://img.shields.io/badge/Author-Irsyad-blue) 
![GitHub last commit](https://img.shields.io/github/last-commit/irsyadadam/double_injury_gsea)
![GitHub](https://img.shields.io/github/license/irsyadadam/double_injury_gsea)
# Double Injury Model Multiomics Integration via GSEA

This repository contains analysis on the Double Injury Model, along with gene set enrichment analysis to integrate transcriptomics, proteomics, and genomics. The following analysis will be used to deploy the double injury model in a knowledge graph for drug discovery with unsupervised GCN.

**Project Goals:**

To integrate transcriptomics and proteomics, gene set enrichment analysis will be used to extract genes per stage of the double injury and identify relevant pathways that correspond to the respective genes. After, relevant proteins and drugs from reactome will also be extracted, creating multi-omics integration. 

**Relevant Literature:**

Double Injury Model:

GSEA Analysis:

------------

Data Used: <code> double_injury/double_injury_seurat_h5ad/double_injury.h5ad </code>

**TODO**:
1. Extract relevant genes from each stage of the double injury
    - create a list for each stage of the double injury ex) p1_genes, p2_genes, etc....
    - put this in a folder
2. Use GSEA to find pathways that correlate to each gene
    - put this in a folder
3. transform the pathways to reactome pathways
4. extract proteins from the pathways, and relevant drugs that target the proteins. 