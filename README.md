# Subtype-MVCL
Code of Subtype-MVCL:The cancer subtype identification model based on multi-view contrastive learning utilizes multi-omic data. The input for the framework is mRNA, miRNA, copy number and DNA methylation. The output is the cluster subtype for each sample.
# Files
`clinical`: Clinical information from 10 cancer datasets, used for clinical enrichment analysis.
`datasets`: Four types of omics datasets from 10 cancers.
`input`: Input multi-omics data of Subtype-MVCL
`Model`: The specific implementation of Subtype-MVCL includes the loss function, model architecture, and trainer.
`R_Language`: R language code for survival analysis and clinical enrichment analysis.
`Datasets.py`: Data preprocessing
# Requirements
*numpy = 1.24.3
