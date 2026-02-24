# Alzheimer's Disease GWAS & Polygenic Risk Score (PRS) Pipeline

This repository contains a bioinformatics pipeline for performing a **Genome-Wide Association Study (GWAS)** and developing a **Polygenic Risk Score (PRS)** using data from the Alzheimer's Disease Neuroimaging Initiative (ADNI).

## Project Overview
The goal of this project is to identify genetic variants (SNPs) associated with Alzheimer's Disease (AD) and evaluate the predictive power of these variants using a risk modeling approach.

## Pipeline Structure
- **Quality Control**: QC of PLINK genomic data for SNPs and individuals (Cell rate, MAF, HWE, heterozigosity, sex discrepancies and relatedness).

- **SNP Discovery**: Identification and functional annotation of AD-associated SNPs.

- **Risk Modeling**: Calculation of Polygenic Risk Scores (PRS) and construction of predictive models.

- **Evaluation**: Assessment of predictive performance using Receiver Operating Characteristic (ROC) curves and AUC metrics.

## Main Report
The full methodology, visualizations, and biological interpretations are documented in the final report:

📄 **[View the Full Report (GWAS_PRS.pdf)](./GWAS_PRS.pdf)**
