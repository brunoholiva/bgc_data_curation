# BGC Data Curation

Curating experimentally validated Biosynthetic Gene Cluster (BGC) data with known molecular products for research.

## Overview

This project documents the collection, cleaning, and analysis of experimentally validated BGC data that have known SMILES molecular structures. The work includes data filtering, deduplication, sequence alignment analysis, and visualization to ensure data quality and reproducibility.

## Approach

1. **Data Collection**: Gather experimentally validated BGC data with known SMILES products
2. **Data Cleaning**: Filter and polish data, removing inconsistencies
3. **Deduplication**: Merge datasets and remove duplicates using seqkit
4. **Similarity Analysis**: Perform all-vs-all sequence alignment using MMseqs2
5. **Visualization**: Generate plots to analyze sequence similarity and molecular fingerprints

## Data Sources so Far

### Completed
- **MIBiG JSON** - [November 14, 2024](https://mibig.secondarymetabolites.org/download)
- **PRISM Gold Standard Dataset** - [doi.org/10.1038/s41467-020-19986-1](https://doi.org/10.1038/s41467-020-19986-1), supplementary data 2