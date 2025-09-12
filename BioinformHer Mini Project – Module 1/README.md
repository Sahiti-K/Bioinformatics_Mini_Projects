# Comprehensive Sequence Analysis of the Human TNF Gene

This repository contains a mini-project focused on the sequence-level bioinformatics analysis of the human TNF (Tumor Necrosis Factor) gene. The project explores various molecular biology tools and computational techniques to characterize and understand the functional elements of this gene.

### Table of Contents

1. Project Overview
2. Tools and Methods
3. Steps Performed
4. Key Results
5. Conclusion
6. References

### Project Overview

The goal of this project is to conduct a comprehensive sequence analysis of the human TNF gene using publicly available tools and databases. This includes translating the gene to its protein form, identifying key regions such as ORFs, regulatory elements, transcription factor binding sites, and more.

### Tools and Methods

NCBI GenBank – Sequence retrieval
BioEdit – Translation, ORF identification, nucleotide composition
PROMO – Transcription factor binding site prediction
MEME Suite – Motif identification
GENSCAN – Gene structure prediction (exons and introns)

### Steps Performed

1. Sequence Retrieval: Retrieved the TNF gene FASTA sequence from NCBI.
2. DNA to Protein Translation: Used BioEdit to translate DNA to the corresponding amino acid sequence.
3. Open Reading Frame (ORF) Identification: Locate ORFs using BioEdit's ORF Finder.
4. Nucleotide Composition Analysis: Calculated A, T, G, and C frequencies and GC content in the sequence.
5. Transcription Factor Binding Site Prediction: Used the PROMO tool with Homo sapiens settings to identify potential TF binding regions.
6. Functional Motif Discovery: Employed MEME Suite to discover conserved motifs within the gene.
7. Exon/Intron Structure Prediction: Used GENSCAN to differentiate coding and non-coding regions of the gene.

### Key Results

- *ORFs*: Multiple open reading frames were identified, indicating potential coding regions.
- *GC Content*: Calculated to assess sequence stability and functional relevance.
- *Motifs & TF Sites*: Revealed biologically significant motifs and transcription factor binding sites involved in immune response.
- *Gene Structure*: Predicted locations of introns, exons, and untranslated regions (UTRs) provided valuable insights into gene regulation.

### Conclusion

This project highlights the utility of basic bioinformatics tools for gene analysis. Through a series of in silico studies, the structural and regulatory features of the TNF gene were identified, contributing to a better understanding of its role in inflammation and immune function.

## References

- NCBI GenBank: https://www.ncbi.nlm.nih.gov/
- BioEdit: http://www.mbio.ncsu.edu/bioedit/
- PROMO: https://alggen.lsi.upc.es/
- MEME Suite: https://meme-suite.org/
- GENSCAN: http://hollywood.mit.edu/GENSCAN.html
