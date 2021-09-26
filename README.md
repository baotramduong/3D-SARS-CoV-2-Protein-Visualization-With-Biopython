# 3D SARS-CoV-2 Protein Visualization With Biopython

## Blog

[Medium Blog](https://baotramduong.medium.com/3d-sars-cov-2-protein-visualization-with-biopython-7c4f1955b1db)

## Introduction

We will use Biopython to handle biological sequence data stored in FASTA & PDB (Protein Data Bank) and XML format. Using this sequence data, we will explore and create an interactive three-dimensional (3D) representation of SARS-CoV-2 (Coronavirus) protein structures.

## Data Source

Data contains the genetic information in FASTA file format, downloaded from from [NCBI (National Center for Biotechnology Information)](https://www.ncbi.nlm.nih.gov/nuccore/MN908947.3?report=fasta).

## Modeling

<img src = '../main/Data & Images/1.png'>

<img src = '../main/Data & Images/2.png'>

<img src = '../main/Data & Images/3.png'>

<img src = '../main/Data & Images/5.png'>

<img src = '../main/Data & Images/6.png'>

## Summary of Findings

* Sequence length: 29,903 base pairs
* GC content: 37.97%
* Protein content has high Leucine L and Serine S.
* The largest protein is of length 2,701 amino acid.
* Largest protein BLAST results corresponds to SARS-CoV-19 6YYT.
* Protein 6YYT has 8 chains & a RNA binding domain.

## Reference

Hillen, H.S., Kokic, G., Farnung, L. et al. Structure of replicating SARS-CoV-2 polymerase. Nature 584, 154–156 (2020). https://doi.org/10.1038/s41586-020-2368-8.

Huang, Y., Yang, C., Xu, Xf. et al. Structural and functional properties of SARS-CoV-2 spike protein: potential antivirus drug development for COVID-19. Acta Pharmacol Sin 41, 1141–1149 (2020). https://doi.org/10.1038/s41401-020-0485-4.

Hunakunti, B. (n.d.). 3D SARS-CoV-19 Protein Visualization With Biopython [MOOC]. Coursera. https://www.coursera.org/projects/3d-sars-cov-19-protein-visualization-with-biopython.

O'Donoghue, S. I. (2021, June 17). Grand challenges in bioinformatics data visualization. Frontiers. Retrieved September 26, 2021, from https://www.frontiersin.org/articles/10.3389/fbinf.2021.669186/full.

Wang, C., Horby, P. W., Hayden, F. G. & Gao, G. F. A novel coronavirus outbreak of global health concern. Lancet 395, 470–473 (2020). https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7135038/.
