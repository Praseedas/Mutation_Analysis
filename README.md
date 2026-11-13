# Task 1: Comparative Somatic Mutation Analysis

## Objective
Comparative analysis of somatic mutations in:
- TCGA-LUAD (Lung Adenocarcinoma)
- TCGA-LUSC (Lung Squamous Cell Carcinoma)

## Data Source
NCI Genomic Data Commons (GDC)

## Tools and Packages
- R
- TCGAbiolinks
- maftools
- dplyr
- ggplot2
- tidyr

## Analysis Performed
1. Downloaded and prepared LUAD and LUSC somatic mutation datasets.
2. Compared mutation profiles using mafCompare.
3. Identified significantly differentially mutated genes.
4. Generated forest plots and comparative oncoplots.
5. Calculated mutation frequencies.
6. Generated mutation summary and landscape plots.

## Files Included
- Mutation_analysis.ipynb: R notebook containing analysis code and saved outputs.

## Note
Original GDC mutation datasets are not included. They can be retrieved again using the queries in the notebook.
