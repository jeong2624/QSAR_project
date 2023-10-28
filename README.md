## Project name : QSAR (Quantitative Structure Activity Relationship) model for the relationship between PTP1B Inhibitor and IC50 value

#### Project time : 2021.11.09 - 2021.12.17

#### Description :
* The project was conducted as part of "Advanced chemoinformatics" class in the Department of Bioinformatics at Soongsil University, Korea.
* The purpose of this project is to build linear regression model by using "pyqsar" module in python
* According to this project, I want to create a model that represents the relationship between the PTP-1B inhibitor and the IC50 value.
  
#### Software & Package version
* Python 3.9
* cellranger 6.1.2
* pyqsar (version 3)

#### Our Dataset :
* GSE67835 (Healthy human brain samples, raw count matrix)
* SRR9262932 (ASD prefrontal cortex tissue, Fastq files)

#### We uploaded these files:
* control_c1.rds : The healthy brain cortex Seurat object data. (Fluidigm C1 platform)
* ASD_10x.rds : The ASD prefrontal cortex tissue Seurat object data. (10x Genomics platform)
* C1_control.R : scRNA-seq analysis code for healthy human cortex.
* 10x_ASD.R : scRNA-seq analysis code for ASD prefrontal cortex tissue.
* Integration.R : scRNA-seq analysis code for integrated data. (healthy + ASD)
* filtered_feature_bc_matrix : ASD scRNA-seq analysis raw count matrix. (using cellranger pipeline)
* control_counts.csv : Healthy brain cortex raw count matrix.
