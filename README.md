# 🧠 AD_scRNAseq_GSE138852_Project

## Reproducible Single-Cell RNA-seq Analysis of Alzheimer's Disease

### Dataset
- GEO accession: **GSE138852**
- Tissue: Human entorhinal cortex
- Species: *Homo sapiens*
- Conditions:
  - Alzheimer's disease (AD)
  - Healthy control

---

## Workflow

1. Data loading
2. Quality control
3. Normalization and scaling
4. PCA and clustering
5. UMAP visualization
6. Cell-type annotation
7. Differential expression analysis
8. Volcano plot generation
9. Heatmap visualization
10. Gene Ontology enrichment
11. Figure generation

---

## Project Structure

```text
AD_scRNAseq_GSE138852_Project
│
├── Scripts
│   ├── 01_data_loading.R
│   ├── 02_quality_control.R
│   ├── 03_normalization_clustering.R
│   ├── 04_umap_annotation.R
│   ├── 05_differential_expression.R
│   ├── 06_volcano_plot.R
│   ├── 07_heatmap.R
│   ├── 08_GO_analysis_neurons.R
│   ├── 09_GO_analysis_global.R
│   └── 10_figure_reproduction.R
│
├── Figures
│   ├── UMAP_celltypes.tiff
│   ├── Volcano_neurons.tiff
│   ├── Heatmap_celltypes.tiff
│   ├── GO_neurons.tiff
│   ├── GO_global.tiff
│   └── Final_figure.tiff
│
├── Data
│   ├── GSE138852_counts.csv.gz
│   └── GSE138852_covariates.csv.gz
│
├── README.md
└── AD_scRNAseq_GSE138852.Rproj
