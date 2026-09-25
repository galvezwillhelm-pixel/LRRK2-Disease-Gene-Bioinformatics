# From Genome to Cell: Exploring LRRK2 Using the UCSC Cell Browser

## UCSC Cell Browser Activity

### 1. Assigned Gene and Disease

**Name:** Willhelm Galvez  
**Assigned Gene:** LRRK2  
**Associated Disease:** Familial Parkinson Disease

This activity uses the UCSC Cell Browser to investigate the single-cell expression of LRRK2 in a human tissue relevant to Parkinson disease.

---

## 2. Organ/Tissue Choice and Dataset Information

**Selected Dataset:** Adult Cortex Meta-Atlas

**Cell Browser Dataset ID:** adult-ctx-meta-atlas

**Organ/Tissue:** Human brain — cerebral cortex

**Organism:** Homo sapiens

**Dataset Classification:** Organs=brain,cortex,organoid; Diseases=Healthy; Organism=Human (H. sapiens); Life Stage=development,adult

**Why this dataset was selected:**

LRRK2 is associated with familial Parkinson disease, a neurological disorder. Therefore, a human brain/cortex dataset is relevant for examining the cellular expression of LRRK2 in nervous-system cell types.

**Dataset Description:**

The Adult Cortex Meta-Atlas is a single-cell transcriptomic meta-atlas of the human cortex. It combines multiple datasets to examine gene-expression patterns and cell subtypes in the developing and adult human cortex.

**Laboratory:** Bhaduri Lab, University of California, Los Angeles (UCLA)

**Cell Browser Dataset URL:**  
https://cells.ucsc.edu/?ds=adult-ctx-meta-atlas

**Original Publication:** Nano et al. (2025), “Integrated analysis of molecular atlases unveils modules driving developmental cell subtype specification in the human cortex,” Nature Neuroscience.

---

## 3. Understanding the Cell Map

**Visualization Type:** Full UMAP

**What does one dot represent?**

Each dot normally represents an individual measured cell or nucleus, depending on the study.

**What do the clusters represent?**

Clusters are groups of nearby cells with similar overall molecular profiles. In this dataset, the clusters are associated with different cell types or neuronal subtypes.

**Examples of visible cell-type/cluster labels:**

- Oligodendrocyte
- Astrocyte
- Microglia
- OPC
- VIP
- SST
- PVALB
- LAMP5
- Endothelial

The UMAP is a reduced representation of high-dimensional molecular data. The axes do not represent physical locations in the brain.

---

## 4. Assigned Gene Expression

**Gene searched:** LRRK2

**Dataset used:** Adult Cortex Meta-Atlas

LRRK2 expression was detected across multiple cell clusters in the human cortex dataset. The expression level varied among cells and cell types rather than being uniform across the entire map.

The LRRK2 expression legend showed that **58.9% of cells had an expression value of 0**, while the remaining cells showed varying levels of detectable expression up to 3.76.

Higher expression values were visible in several clusters, while other clusters contained many cells with little or no detectable LRRK2 expression.

---

## 5. Cell Types and Clusters

LRRK2 expression was detectable across multiple cell types and clusters in the Adult Cortex Meta-Atlas.

**Examples of cell types with detectable LRRK2 expression:**

- Oligodendrocyte
- Astrocyte
- Microglia
- OPC
- Several neuronal clusters

**Relatively low/undetected expression:**

The LRRK2 expression map showed many cells with an expression value of 0. However, the available overview did not allow a specific named cluster to be identified confidently as the lowest-expression cluster. Therefore, no specific cell type was assigned as the lowest-expressing group without additional quantitative analysis.

**Expression pattern:**

LRRK2 showed a broad expression pattern across multiple cell populations rather than being restricted to a single cell type. The level of detectable expression varied among cells and clusters.

**Possible biological interpretation:**

The broad distribution suggests that LRRK2 is expressed in multiple cell populations within the selected human cortex dataset rather than functioning exclusively as a marker of one cell type. However, this observation is limited to the Adult Cortex Meta-Atlas and does not by itself establish a disease mechanism or causation.

---

## 6. Expression Plot

**Selected cell group:** Oligodendrocytes

**Number of selected cells:** 90,334

**Other cells:** 429,679

The Oligodendrocyte cluster was selected using the cell-selection tool. The expression plot compared LRRK2 expression in the selected Oligodendrocyte cells with the remaining cells in the dataset.

The violin plot provides a clearer view of the distribution of LRRK2 expression between the selected cells and the background population rather than showing expression only by cell position on the UMAP.

---

## 7. Marker Genes

**Selected cluster:** Oligodendrocyte

Three marker genes shown in the Oligodendrocyte cluster marker table were:

1. **ST18** — avg. logFC = 6.774
2. **ENPP2** — avg. logFC = 6.167
3. **C10orf90** — avg. logFC = 5.366

The displayed adjusted p-values for these marker genes were 0.

These genes were identified by the Cell Browser marker-gene table as markers associated with the selected Oligodendrocyte cluster.

---

## 8. Disease Gene vs. Marker Gene

**Disease-associated gene:** LRRK2

**Marker gene:** ST18

**Selected cluster:** Oligodendrocyte

LRRK2 showed a broader expression pattern across multiple cell types and clusters in the Adult Cortex Meta-Atlas. In contrast, ST18 showed a more restricted pattern, with strong expression particularly associated with the Oligodendrocyte cluster.

This comparison demonstrates that a disease-associated gene does not necessarily have the same expression pattern as a cell-type marker. LRRK2 can be detected across several cell populations, while ST18 is more closely associated with the selected Oligodendrocyte cluster in this dataset.

---

## 9. Connection to Genome Browser and ClinVar

The previous activity examined LRRK2 at the genome and variant levels, while the UCSC Cell Browser activity examined its expression at the cellular level.

**Chromosome location:**

LRRK2 is located on chromosome 12 on the negative strand. In the previous UCSC Genome Browser activity, LRRK2 was examined using the GRCh38/hg38 reference genome.

**Gene structure:**

The selected transcript was **NM_198578.4**. The transcript contains **51 exons**.

**Disease-associated variant:**

The selected ClinVar variant was:

**NM_198578.4:c.6055G>A, p.Gly2019Ser (G2019S)**

This is a missense variant associated with familial Parkinson disease.

**Gene expression:**

In the Adult Cortex Meta-Atlas, LRRK2 expression was detected across multiple cell types and clusters, although the expression level varied among cells.

**Cellular context:**

LRRK2 expression was observed in several cell populations in the human cortex, including neuronal and glial cell clusters. This provides cellular context for where LRRK2 is expressed in the selected dataset.

### Overall Connection

The activities connect information at different biological levels:

**Genome → Gene structure → Disease variant → Gene expression → Cell type**

The Genome Browser showed where LRRK2 is located and its gene structure. ClinVar provided information about the disease-associated G2019S variant. The Cell Browser then showed how LRRK2 is expressed across different cell populations in the human cortex.

The observed expression in brain/cortical cells is relevant to studying a gene associated with a neurological disease. However, expression in a cell type alone does not demonstrate that the gene or a particular cell type causes the disease. A single Cell Browser dataset cannot establish causation.

---

## 10. Reflection

### 1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?

The UCSC Cell Browser showed where LRRK2 is expressed among different cell types and clusters in the human cortex. The UCSC Genome Browser mainly showed the gene's genomic location, structure, and sequence context, while the Cell Browser provided a cellular expression view.

### 2. Why can the same gene have different expression levels among different cell types?

Different cell types have different functions and therefore use different sets of genes. As a result, the same gene can have different expression levels among different cell types.

### 3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?

Zero or very low expression in single-cell data does not necessarily mean that the gene is completely inactive. Detection can depend on the tissue, biological samples, experimental method, and data processing used in the study.

### 4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?

Combining these types of information provides a more complete view of a disease-associated gene. Genomic information shows where the gene is located, genetic-variant information identifies changes associated with disease, and cell-specific expression shows which cell populations express the gene.

### 5. What was the most interesting observation you made about your assigned gene?

The most interesting observation was that LRRK2 expression was not limited to one cell type in the Adult Cortex Meta-Atlas. It was detectable across multiple cell clusters, while the amount of expression varied among cells. The comparison with ST18 also showed that a disease-associated gene can have a broader expression pattern than a cell-type marker.

---

## 11. References and Links

### UCSC Cell Browser

UCSC Cell Browser:  
https://cells.ucsc.edu/

Selected dataset: Adult Cortex Meta-Atlas  
https://cells.ucsc.edu/?ds=adult-ctx-meta-atlas

UCSC Cell Browser Getting Started Guide:  
https://cellbrowser.readthedocs.io/en/master/ui/getting_started.html

UCSC Cell Browser Visualization Guide:  
https://cellbrowser.readthedocs.io/en/master/ui/visualization.html

UCSC Cell Browser Analysis Guide:  
https://cellbrowser.readthedocs.io/en/master/ui/analysis.html

### Previous Genome and Variant Analysis

UCSC Genome Browser:  
https://genome.ucsc.edu/

NCBI ClinVar:  
https://www.ncbi.nlm.nih.gov/clinvar/

### Original Dataset Publication

Nano, P. R. et al. (2025). Integrated analysis of molecular atlases unveils modules driving developmental cell subtype specification in the human cortex. *Nature Neuroscience*.

https://doi.org/10.1038/s41593-025-01933-2

### UCSC Cell Browser Software Reference

Speir, M. L. et al. (2021). UCSC Cell Browser: visualize your single-cell data. *Bioinformatics*, 37, 4578–4580.

**LRRK2 reference transcript:** NM_198578.4

**LRRK2 reference protein:** NP_940980.4

**Selected disease-associated variant:** NM_198578.4:c.6055G>A, p.Gly2019Ser (G2019S)

---

## Screenshots

The following screenshots document the UCSC Cell Browser activity:

- `00_dataset.png` — Cell Browser dataset overview
- `01_dataset.png` — Dataset Information
- `02_gene_expression.png` — LRRK2 expression across the cell map
- `03_cell_types.png` — Cell types/clusters with LRRK2 expression
- `04_expression_plot.png` — LRRK2 expression comparison between selected Oligodendrocytes and other cells
- `05_marker_genes.png` — Oligodendrocyte cluster marker genes
