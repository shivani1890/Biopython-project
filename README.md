# Biopython-project
Functional_Sequence_Characterization

# Project Overview
This project aims to characterize a hypothetical protein sequence using a stepwise bioinformatics pipeline implemented in Python with Biopython. Sequence quality analysis, homology search, and functional annotation were performed to predict the biological role of the protein.

---

## Step 1: Sequence Selection
A hypothetical protein (GenBank accession: KAI4296569.1) from *Bauhinia variegata* consisting of 481 amino acids was selected for analysis.

---

## Step 2: Sequence Quality Analysis
The protein sequence was analyzed for length and amino acid composition using Biopython. The sequence showed a valid amino acid distribution with no missing or invalid residues.

---

## Step 3: Sequence Filtering and Validation
The sequence was checked for ambiguous amino acids (X, B, Z, J), internal stop codons, and terminal residues. No ambiguous residues or internal stop codons were detected. The sequence passed all quality checks and was suitable for downstream analysis.

---

## Step 4: Homology Search
BLASTp analysis was performed against the RefSeq protein database. A total of 50 homologous protein sequences were identified. The closest homologs were G-type lectin S-receptor-like serine/threonine-protein kinases with extremely low E-values and conserved query regions.

---

## Step 5: Functional Annotation
Functional annotation was carried out using homology-based inference supported by UniProt annotations of the top BLAST hits. Based on the conserved domains and known functions of homologous proteins, the query protein was predicted to function as a receptor-like serine/threonine kinase involved in signal transduction.

---

## Step 6: Biological Interpretation
The protein is likely involved in receptor-mediated signaling pathways that regulate plant development and responses to environmental stimuli. This conclusion is supported by strong sequence similarity, conserved regions across multiple species, and UniProt annotations of closely related proteins.

---

## Tools Used
- Python 3
- Biopython
- NCBI BLAST
- UniProt

---

## Conclusion
This study demonstrates how computational approaches and homology-based analysis can be used to functionally annotate hypothetical proteins in the absence of experimental data.
