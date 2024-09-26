# RNA-Seq Differential Expression and GSEA with DESeq2
Overview

This project performs differential gene expression analysis using the DESeq2 package and gene set enrichment analysis using clusterProfiler and related tools. The pipeline is designed to analyze RNA-Seq count data, identify differentially expressed genes (DEGs), and perform functional enrichment analysis to gain biological insights.

The analysis steps:

Data Preprocessing: Loading RNA-Seq count data and metadata.
DESeq2 Analysis: Differential expression analysis using the negative binomial distribution.
Variance-Stabilizing Transformation (VST): Normalization of the data for downstream visualization.
PCA Visualization: Visualize batch effects and biological variation using principal component analysis.
Gene Set Enrichment Analysis (GSEA): Enrich for biological pathways using GSEA.

## Required Packages

### CRAN:
dplyr,
stringr,
magrittr,
tidyverse,
RColorBrewer,
pheatmap,
ggrepel,
cowplot,
ggplot2

### Bioconductor
devtools,
pachterlab/sleuth,
GenomicFeatures,
DESeq2, tximport,
RMariaDB, biomaRt,
clusterProfiler,
pathview, 
enrichplot,
msigdbr,
org.Hs.eg.db,
DOSE, 
DEGreport, 
apeglm 
