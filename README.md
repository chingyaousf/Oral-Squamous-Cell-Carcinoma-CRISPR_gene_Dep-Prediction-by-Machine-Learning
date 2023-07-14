# Oral-Squamous-Cell-Carcinoma-CRISPR_gene_Dep-Prediction-by-ML

## Project Overview:

In this project, we build upon our previous analysis on the CCLE dataset, focusing on the connection between Oral Cavity Squamous Cell Carcinoma (OCSCC) and CRISPR gene dependency. Specifically, we employ the K Nearest Neighbor (KNN) algorithm to predict CRISPR gene dependency based on CCLE gene expression data for OCSCC cell lines. By leveraging KNN, which classifies samples based on feature similarity, we aim to uncover meaningful relationships between gene expression patterns and gene dependency in OCSCC. This machine learning approach allows us to gain insights into the essentiality of specific genes and predict gene dependency based on gene expression data, contributing to our understanding of OCSCC behavior.

### KNN models using five target genes:

EIF2AK3 (9451) Dep![](https://github.com/chingyaousf/Oral-Squamous-Cell-Carcinoma-CRISPR_gene_Dep-Prediction-by-ML/blob/main/plots/KNN_EIF2AK3_Oral_Squamous.png?raw=true)

MYC (4609) Dep![](https://github.com/chingyaousf/Oral-Squamous-Cell-Carcinoma-CRISPR_gene_Dep-Prediction-by-ML/blob/main/plots/KNN_MYC_Oral_Squamous.png?raw=true)

NQO1 (1728) Dep![](https://github.com/chingyaousf/Oral-Squamous-Cell-Carcinoma-CRISPR_gene_Dep-Prediction-by-ML/blob/main/plots/KNN_NQO1_Oral_Squamous.png?raw=true)

SF3B1 (23451) Dep![](https://github.com/chingyaousf/Oral-Squamous-Cell-Carcinoma-CRISPR_gene_Dep-Prediction-by-ML/blob/main/plots/KNN_SF3B1_Oral_Squamous.png?raw=true)

SQSTM1 (8878) Dep![](https://github.com/chingyaousf/Oral-Squamous-Cell-Carcinoma-CRISPR_gene_Dep-Prediction-by-ML/blob/main/plots/KNN_SQSTM1_Oral_Squamous.png?raw=true)

### KNN models prediction error values using five target genes:

![](https://github.com/chingyaousf/Oral-Squamous-Cell-Carcinoma-CRISPR_gene_Dep-Prediction-by-ML/blob/main/plots/KNN_5Genes_by_Features_Filtering_Squamous.png?raw=true)

**MSE comparison??using five target genes**:

![](https://github.com/chingyaousf/Oral-Squamous-Cell-Carcinoma-CRISPR_gene_Dep-Prediction-by-ML/blob/main/plots/KNN_MSE_by_Gene_Squamous.png?raw=true)

**MAE comparison??using five target genes**:

![](https://github.com/chingyaousf/Oral-Squamous-Cell-Carcinoma-CRISPR_gene_Dep-Prediction-by-ML/blob/main/plots/KNN_MAE_by_Gene_Squamous.png?raw=true)

**R2 comparison??using five target genes**:

![](https://github.com/chingyaousf/Oral-Squamous-Cell-Carcinoma-CRISPR_gene_Dep-Prediction-by-ML/blob/main/plots/KNN_R2_by_Gene_Squamous.png?raw=true)

## Blog:

<https://ssidmarine.wordpress.com/2023/07/13/oral-squamous-cell-carcinoma-crispr_gene_dep-prediction-by-ml/>

## Access data:

DepMap Public 22Q2 Primary Files

<https://depmap.org/portal/download/all/>

22Q2 CRISPR_gene_effect

CRISPR_gene_dependency.csv

CCLE_expression.csv

**testing data available in the data folder**
