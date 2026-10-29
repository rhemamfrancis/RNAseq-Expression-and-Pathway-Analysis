# RNA-Seq Expression and Pathway Analysis

## Overview

This project investigates gene expression patterns and biological pathways associated with breast cancer using RNA-seq data from GEO dataset GSE184717.

Using R, I performed hierarchical clustering, Gene Ontology (GO) and KEGG pathway enrichment, and Gene Set Enrichment Analysis (GSEA) to identify transcriptional differences between breast tumor and normal tissue samples.


## Tools and Technologies

- **Language:** R
- **Packages:** DESeq2, clusterProfiler, org.Hs.eg.db, enrichplot, ggplot2, dplyr
- **Methods:** Hierarchical clustering, differential expression analysis, GO/KEGG enrichment, GSEA
- **Data Source:** NCBI GEO (GSE184717)

## Key Findings

- Hierarchical clustering of the 100 most variable genes primarily separated tumor and normal tissue samples.
- GO and KEGG enrichment identified pathways associated with sensory perception, keratinization, and cellular signaling.
- GSEA identified reduced expression of MHC class II antigen presentation pathways in tumor samples (NES = -3.63), suggesting potential alterations in immune recognition.
- Additional immune-related pathways, including allograft rejection and graft-versus-host disease, were enriched toward normal tissue samples.

## Limitations

The dataset contains samples from a single patient, limiting the generalizability of the findings. Results are exploratory and require validation in independent cohorts.

## Project Files

- `analysis.Rmd` - R Markdown source code
- `index.html` - Full analysis report with code, visualizations, and results

## Data Source

[GEO Dataset GSE184717](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE184717)

---

**M.S. Bioinformatics | Brandeis University | July 2026**



