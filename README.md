## Predicting Cancer Types from Gene Expression Data: A Machine Learning Approach

This study presents a machine learning-based approach to predict the primary disease type of samples,
focusing on breast cancer, lung squamous cell carcinoma, and lung adenocarcinoma. Gene expression
data from "train_data.tsv" and "train_label.tsv" were employed for model training and evaluation.
Performance metrics, including F1 score, Accuracy, AUC, Recall, Precision, Kappa, and MCC, were
utilized to gauge model performance. Leveraging AutoML and ensemble techniques, an effective
predictive model was developed. The analysis encompassed exploratory data analysis, dimensionality
reduction, and feature selection techniques to enhance the prediction process. The results underscore the
effectiveness of the model in accurately classifying cancer types, emphasizing the significance of robust
pre-processing and thoughtful model selection.
![Flowchart_of_workflow_followed](https://github.com/kiranfranklin999/TCGA-FOR-Pathway-analysis-classification/assets/47182702/3d0f7fb0-9a07-4f4e-81d8-9914a4e27061)


## Differential Gene Expression and KEGG Pathway Enrichment Analysis

The objective of this analysis is to perform a comprehensive investigation of differential gene expression
and pathway enrichment between "Tumor" and "Normal" samples. Leveraging the DESeq2 package [1],
differential gene expression analysis is conducted. Subsequently, the GAGE package [3] is employed to
perform pathway enrichment analysis using the KEGG pathway database. The gene expression data
sourced from "TCGA-BRCA.htseq_counts_gene_name.tsv" is in log2-transformed RNAseq count
format, with corresponding sample labels available in the "TCGA-BRCA.pheno.tsv" file.
Materials and Methods:
![Flowchart_of_workflow_followed](https://github.com/kiranfranklin999/TCGA-FOR-Pathway-analysis-classification/assets/47182702/49aded0a-dda8-4433-9e7b-cd284c2e8ab6)
