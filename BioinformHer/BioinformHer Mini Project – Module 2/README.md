# Tracking the Evolution of the Hemoglobin Beta (HBB) Gene Across Species

## Overview

This project explores the evolutionary conservation of the Hemoglobin Beta (HBB) gene across six selected species: **Human, Chimpanzee, Cow, Horse, Mouse, Chicken, and Zebrafish**. It demonstrates the application of bioinformatics tools to analyze protein sequence similarity, conservation, and phylogenetic relationships, showcasing the power of comparative genomics in understanding molecular evolution.

---

## Project Goals

- Retrieve HBB protein sequences from NCBI for six different species
- Perform pairwise and multiple sequence alignments
- Visualize conserved residues using a sequence logo
- Construct a phylogenetic tree to infer evolutionary relationships
- Interpret the functional and evolutionary significance of observed patterns

---

## Tools Used

| Task                          | Tool/Platform           |
|-------------------------------|--------------------------|
| Sequence Retrieval & BLAST    | NCBI GenBank & BLASTP    |
| Pairwise Alignment            | EMBOSS Needle            |
| Multiple Sequence Alignment   | Clustal Omega            |
| Sequence Logo Visualization   | Skylign                  |
| Phylogenetic Tree Construction| MEGA X                   |

---

## Methodology

### 1. Sequence Retrieval & BLAST Search
- Retrieved the **human HBB protein sequence** from NCBI.
- Used **BLASTP** to identify HBB homologs in:
  - Chimpanzee
  - Cow
  - Horse
  - Mouse
  - Chicken
  - Zebrafish
- Downloaded the sequences in **FASTA format**.
- Tabulated **accession numbers** and **% identity** with the human HBB.

### 2. Pairwise Sequence Alignment
- Aligned:
  - **Human vs Chimpanzee** (closely related)
  - **Human vs Zebrafish** (distantly related)
- Tools used: **EMBOSS Needle**
- Reported:
  - % Identity
  - % Similarity
  - Number of Gaps
  - Interpretation on evolutionary conservation

### 3. Multiple Sequence Alignment (MSA)
- Performed MSA using **Clustal Omega** on all six HBB sequences.
- Saved the alignment and identified **highly conserved motifs** and **variable regions**.

### 4. Sequence Logo Generation
- Uploaded MSA to **Skylign** to generate a sequence logo.
- Analyzed:
  - Degree of conservation at each position
  - Presence of functionally important amino acids
  - Patterns of divergence among species

### 5. Phylogenetic Tree Construction
- Imported MSA into **MEGA X**.
- Constructed a phylogenetic tree using a suitable method (e.g., Neighbor-Joining).
- Interpreted species clustering in the context of known evolutionary relationships.

---

## Key Observations

- **Mammalian sequences (human, chimpanzee, cow, horse, and mouse)** are highly conserved.
- **Chimpanzee HBB** is nearly identical to human, reflecting close evolutionary proximity.
- **Zebrafish and chicken** show significant divergence, especially in variable regions.
- **Conserved residues** are associated with heme-binding and oxygen transport.
- The **phylogenetic tree** topology agrees with established evolutionary history.


## Biological Significance

The HBB gene is a classic example of a highly conserved protein across vertebrates due to its essential role in oxygen transport. Despite evolutionary divergence:
- Core **functional domains** are retained.
- Changes in **non-critical regions** reflect species-specific adaptation.
- The project highlights the **importance of sequence analysis** in understanding evolutionary biology.


## References

- [NCBI GenBank](https://www.ncbi.nlm.nih.gov/)
- [BLASTP](https://blast.ncbi.nlm.nih.gov/)
- [EMBOSS Needle](https://www.ebi.ac.uk/Tools/psa/emboss_needle/)
- [Clustal Omega](https://www.ebi.ac.uk/Tools/msa/clustalo/)
- [Skylign](https://skylign.org/)
- [MEGA X Software](https://www.megasoftware.net/)

