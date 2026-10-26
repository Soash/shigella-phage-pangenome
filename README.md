# Comparative Pan-Genomic and Functional Analysis of *Shigella* Bacteriophages Reveals a Fragmented, Genome Size-Linked Population Structure

Md Abu Sadat Soash  
Department of Genetic Engineering and Biotechnology
Shahjalal University of Science and Technology, Sylhet, Bangladesh  

---

## Abstract

*Shigella* species are a major cause of bacterial dysentery, with substantial disease burden in Bangladesh and other low- and middle-income countries. Rising antibiotic resistance has renewed interest in bacteriophages as alternative therapeutic agents. However, the genomic diversity and gene content of known *Shigella* phages have not been systematically characterized, limiting understanding of their suitability for therapeutic development. This study aimed to characterize the pan-genome, functional gene content, and genomic clustering of publicly available complete *Shigella* phage genomes.

Fifty-four complete *Shigella* phage genomes were retrieved from the NCBI RefSeq database. Genes were annotated with Pharokka, which assigned functional categories and screened for virulence factors (VFDB) and antimicrobial resistance genes (CARD). Pan-genome composition was determined with Roary, and genomes were grouped by proteomic similarity using PhamClust.

Pan-genome analysis identified 4,321 gene clusters with no core genes shared across all 54 genomes, 206 shell genes, and 4,115 cloud genes. Of 9,040 predicted coding sequences, the largest annotated categories were DNA/RNA metabolism (13.9%) and tail proteins (9.0%), while 54.6% remained unannotated. Two genomes carried *gtrA/gtrB/gtr*-type serotype-converting genes; no antimicrobial resistance genes were detected. PhamClust grouped genomes into 11 clusters and 13 singletons, with the two largest clusters corresponding to genome size: large phages (165–194 kb, 12 genomes) and small phages (~50 kb, 7 genomes).

*Shigella* phages form multiple distinct, size-linked lineages rather than one uniform population. The serotype-converting genes reflect known lysogenic conversion mechanisms in *Shigella flexneri* phages, while the absence of resistance genes supports their suitability for therapeutic exploration. This fragmentation indicates the *Shigella* phage population lacks a shared core genome, a baseline finding relevant to future cocktail-based phage therapy strategies against *Shigella*.

## Keywords

*Shigella* bacteriophages; pan-genome analysis; comparative genomics; phage therapy; genome clustering

---

## Research Objectives

- Characterize the pan-genome composition of complete *Shigella* bacteriophage genomes.
- Annotate predicted genes and summarize their functional categories.
- Screen predicted gene content for known virulence factors and antimicrobial resistance genes.
- Investigate proteomic similarity and population structure among the sampled phage genomes.
- Identify genomic patterns relevant to future investigation of bacteriophage-based therapeutic strategies.

## Methodology Overview

1. **Genome retrieval:** Fifty-four complete *Shigella* phage genomes were retrieved from the NCBI RefSeq database.
2. **Genome annotation:** Pharokka was used for phage genome annotation and functional categorization.
3. **Gene screening:** Annotated gene content was screened against the Virulence Factor Database (VFDB) and the Comprehensive Antibiotic Resistance Database (CARD).
4. **Pan-genome analysis:** Roary was used to analyze gene-cluster distribution across the genome set.
5. **Proteomic clustering:** PhamClust was used to group genomes according to proteomic similarity.
6. **Comparative interpretation:** Pan-genome composition, functional annotations, screening results, and clustering patterns were interpreted together.

## Key Findings

| Analysis | Result |
|---|---|
| Complete phage genomes | 54 |
| Pan-genome gene clusters | 4,321 |
| Core gene clusters | 0 |
| Shell gene clusters | 206 |
| Cloud gene clusters | 4,115 |
| Predicted coding sequences | 9,040 |
| Unannotated coding sequences | 54.6% |
| Largest annotated functional category | DNA/RNA metabolism (13.9%) |
| Tail proteins | 9.0% |
| Genomes with *gtrA/gtrB/gtr*-type genes | 2 |
| Antimicrobial resistance genes detected | None detected in this analysis |
| PhamClust output | 11 clusters and 13 singletons |
| Large-genome cluster | 12 phages, 165–194 kb |
| Small-genome cluster | 7 phages, approximately 50 kb |

## Tools and Resources

- **NCBI RefSeq** — retrieval of complete phage genomes
- **Pharokka** — bacteriophage genome annotation
- **VFDB** — virulence-factor database screening
- **CARD** — antimicrobial-resistance gene screening
- **Roary** — pan-genome analysis
- **PhamClust** — proteomic similarity clustering

## Research Significance

This study provides a comparative genomic baseline for understanding the diversity of publicly available *Shigella* bacteriophages. The absence of a universally shared core gene cluster and the predominance of cloud gene clusters indicate substantial variation in gene content across the sampled genomes. Genome size-associated clustering further suggests that the sampled phages comprise multiple genomic groups rather than one uniform population.

These findings may help guide future studies of phage diversity and the design of phage cocktails. However, genomic screening alone does not establish therapeutic efficacy or safety. Candidate phages require further biological characterization and experimental validation before therapeutic use can be assessed.

## Repository Contents

The repository can be organized as follows as project files become available:

```text
shigella-phage-pangenome/
├── README.md
├── data/
│   └── README.md
├── scripts/
│   └── README.md
├── results/
│   └── README.md
├── figures/
│   └── README.md
└── docs/
    └── README.md
```

Only add directories and files that actually exist in the repository. Do not upload copyrighted database records or large raw datasets without checking the relevant database terms and repository limits.

## Reproducibility and Data Availability

The study used complete *Shigella* bacteriophage genomes retrieved from NCBI RefSeq. For reproducibility, the repository should include the accession numbers of all 54 genomes, software versions, analysis commands or scripts, and the processed result tables and figures where available.

**Genome accession list:** To be added.  
**Software versions and commands:** To be added.  
**Processed data and figures:** To be added as files are prepared.

## Citation

If you use or discuss this work, please cite the associated manuscript or preprint once a formal citation is available.

**Manuscript status:** Add the current status here (for example, ongoing project, preprint, submitted, or published).

## Contact

**Md Abu Sadat Soash**  
Department of Genetic Engineering and Biotechnology  
Shahjalal University of Science and Technology  
Sylhet-3114, Bangladesh  
Email: [mdabu13@student.sust.edu](mailto:mdabu13@student.sust.edu)

---

*This repository documents a comparative bioinformatics research project. Findings are based on the sampled public genomes and computational analyses described above; they should not be interpreted as clinical evidence of phage safety or efficacy.*
