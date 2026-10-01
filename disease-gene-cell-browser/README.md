# UCSC Cell Browser Activity
**Name:** Rhealyn F. Alama

**Assigned gene:** TP53

**Associated disease:** Li-Fraumeni syndrome

**Activity:** From Genome to Cell: Exploring Disease Gene Using the UCSC Cell Browser

## Part B. Dataset
- Dataset name: Single-cell atlas of human leptomeningeal metastasis - Patient C with Breast Primary Tumor
- Organ/tissue: Cerebrospinal fluid (CSF) cells from a patient with a breast primary tumor and leptomeningeal metastasis
- Publication/study: Speir et al. 2021
- Dataset URL: (paste from address bar; dataset ID lepto-metastasis/patient-c)
- Why this tissue is relevant: Breast cancer is one of the most common cancers in Li-Fraumeni syndrome, which is caused by germline TP53 variants. This dataset comes from a patient with a breast primary tumor, so it contains breast cancer cells and the immune cells around them. The cells were taken from CSF, not from the breast itself, which limits how directly it represents breast tissue.

**Screenshot 1: Selected dataset**
![Dataset](Images/01_dataset.png)
![Dataset information](Images/01b_dataset_info.png)

## Part C. Understanding the Cell Map
- a. Type of visualization: (check the Layout tab: UMAP or t-SNE)
- b. One dot represents: one cell
- c. Clusters represent: cell types, here immune cell types and tumor cell populations
- d. Labels visible: CD4 T cells, CD8 T cells, Monocyte 1, Monocyte 2, NK cells, Macrophage, Cancer 3, Cancer 4, Cancer 5, cDCs

## Part D. Searching for TP53
- a. Gene: TP53
- b. Dataset: Patient C with Breast Primary Tumor (leptomeningeal metastasis atlas)
- c. Pattern: TP53 expression is low and widespread but sparse. It is detected in a minority of cells scattered across most clusters.
- d. Stronger expression: scattered cells in CD4 T cells, CD8 T cells, NK cells, monocytes, and macrophages, plus a few cancer cells.
- e. Little or no expression: most cells in every cluster, and the few cDCs.

**Screenshot 2: TP53 expression**
![TP53 expression](Images/02_gene_expression.png)

## Part E. Cell Types Expressing TP53
- a. Strongest visible expression: (confirm with the dot plot in Part F)
- b. Another cluster with detectable expression: (e.g., NK cells or monocytes)
- c. Low or undetected: cDCs and the majority of cells in each cluster
- d. Pattern: broad, not restricted to one cell type
- e. Interpretation (based on this dataset only): TP53 is a tumor suppressor involved in the DNA damage response, and most cell types use it at low levels, so a broad, sparse pattern fits. Single-cell methods also miss many low-level transcripts, so undetected cells may still express TP53.

**Screenshot 3: TP53 with cell-type labels**
![Cell types](Images/03_cell_types.png)
