# Exploring a Human Disease Gene Using UCSC Genome Browser and NCBI ClinVar
Name: Rhealyn F. Alama

Assigned gene: TP53

Associated disease: Li-Fraumeni syndrome

## 1. UCSC Gene Location
- Official gene symbol: TP53
- Full gene name: tumor protein p53
- Chromosome: 17 (17p13.1)
- Genome assembly: GRCh38/hg38
- Genomic coordinates: chr17:7,668,421-7,687,490
- Strand: minus (-)
- Approximate gene size: 19,070 bp (about 19 kb)

## 2. Exons, Introns, and Transcripts

**Selected transcript:** NM_000546.6 (ENST00000269305.9), MANE Select Plus Clinical

**a. Number of exons identified in the selected transcript:**
11 exons. UCSC's feature details for this transcript show "Exon 11 of 11". Because TP53 is on the minus strand, exon 1 is at the right end of the gene and exon 11 is at the left end.

**b. Multiple transcripts/isoforms visible:**
Yes. The GENCODE V50 track shows many horizontal rows for TP53. They differ in which exons they include and where the exons begin and end, which means TP53 produces multiple transcript isoforms.

**c. Difference between an exon and an intron:**
An exon is a part of a gene that is kept in the mature mRNA after splicing, and most exons contain the code for the protein. An intron is a stretch of sequence between exons that is copied into the pre-mRNA but cut out during splicing, so it is not in the final mRNA or the protein.

**d. Are introns generally longer or shorter than exons in TP53?**
Introns are generally longer. In the browser, the exons appear as small boxes and the introns as the long lines connecting them. Most of TP53's 19 kb span is intron, and most exons are only a few hundred base pairs or less. The exception is exon 11 (1,270 bp), which is the longest exon.

## 3. UCSC Annotation Tracks

**a. Gene annotation track used:** MANE Select Plus Clinical (NM_000546.6), with GENCODE V50 and NCBI RefSeq (curated) also displayed.

**b. Were ClinVar-related variant marks visible within or near TP53?**
Yes. The ClinVar SNVs track showed many colored marks across the gene. They were densest over the coding exons in the middle of the gene, with fewer in the introns and in the regions on either side.

**c. Were some regions more conserved than others?**
Yes. The 100 Vertebrates PhyloP track had tall peaks in some regions and low, flat signal in others.

**d. Did conserved regions correspond mainly to exons, introns, both, or another region?**
The tallest conservation peaks lined up mainly with exons in the middle of the gene. The introns and the ends of the gene showed lower conservation, with a few small peaks.

**e. Why strong conservation can suggest biological importance:**
When a DNA sequence stays nearly the same across many different species, it usually means that sequence has an important function. Changes (mutations) in such regions are likely to harm the organism, so natural selection removes them over time. This is why the highly conserved exons of TP53 are likely to encode parts of the protein that are essential for its function.

## 4. Selected ClinVar Variant

- **a. Gene:** TP53
- **b. Variant name (HGVS):** NM_000546.6(TP53):c.524G>A (p.Arg175His)
- **c. rsID / ClinVar ID:** rs28934578 / VCV000012374.87 (Variation ID 12374)
- **d. Chromosome and position (GRCh38):** chr17:7,675,088 (17p13.1)
- **e. Associated condition:** Li-Fraumeni syndrome
- **f. Clinical significance (as reported by ClinVar):** Pathogenic (germline)
- **g. Review status:** Reviewed by expert panel (3 stars); ClinGen TP53 Variant Curation Expert Panel, Sep 2024
- **h. ClinVar record URL:** (https://ncbi.nlm.nih.gov/clinvar/variation/12374/?term=%22NM_000546.6%3Ac.524G%3EA%22%5BVARNAME%5D)
