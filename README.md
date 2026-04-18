# scRNA-seq-Integration-and-Trajectory-Analysis-of-Malaria-Infected-Immune-Cells

## Overview

End-to-end single-cell analysis combining bioinformatics and unsupervised machine learning to uncover immune dynamics during malaria infection.

This project integrates scRNA-seq data from wild-type and malaria-infected mice using Scanpy and BBKNN, identifying cell populations, infection-driven transcriptional changes, and dynamic cellular trajectories.

### Key Results Overview:

#### UMAP & Annotation
![UMAP](figures/umap.png)

**UMAP revelas 14 immune cell clusters and key populations (e.g., Ms4a1+ B cells, progenitor-like cells).**

#### Pseudotime (PHATE Trajectory)
![PHATE Trajectory](figures/phate.png)

**PHATE-based trajectory analysis reveals dynamic immune cell transitions during malaria infection.**  
Top: 14 Leiden clusters projected onto PHATE embedding.  
Bottom: Pseudotime trajectories using two biologically relevant starting points:  
- Left: progenitor-like cells (cluster 3)  
- Right: Ms4a1+ B cells (cluster 1)  

Notably, PHATE reveals a **circular/looping trajectory**, suggesting cyclic immune state transitions rather than a simple linear progression.

## Dataset
- Platform: 10x Genomics 3' scRNA-seq
- Organism: Mouse (malaria infection model)
- Samples:
  - WT1 (control)
  - Infected1
  - Infected2
