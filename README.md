# RNA-Seq Analysis Pipeline

This repository contains an RNA-Seq analysis pipeline used during my undergraduate research at Wake Forest University. This project also highlights my skills in RNA-Seq data analysis and statistical modeling.

**Note**: The original datasets are unavailable, so this code is for reference only.

## Overview
The pipeline includes:
- **Data Preprocessing**: Import and filter raw counts.
- **Normalization**: TMM adjustment for library size differences.
- **Differential Expression Analysis**: Linear modeling with `edgeR` and `limma`.
- **Visualization**: Volcano plots and MDS plots.
- **Two-Factor Analysis**: Explore treatment and timepoint interactions.

## Requirements
- R packages: `edgeR`, `limma`, `dplyr`

## Usage
1. Replace `setwd()` with your working directory.
2. Provide a raw counts file in CSV format.
3. Follow the script steps for analysis.

