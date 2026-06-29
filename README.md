# Breast Cancer Molecular Subtype Classification using Machine Learning

![Python](https://img.shields.io/badge/Python-3.12-blue)

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--learn-orange)

![Bioinformatics](https://img.shields.io/badge/Bioinformatics-Gene%20Expression-green)

![License](https://img.shields.io/badge/License-MIT-success)

A machine learning and bioinformatics project for classifying breast cancer molecular subtypes using gene expression data from the GSE45827 dataset. The project compares multiple machine learning models, performs feature selection, cross-validation, gene annotation, and functional enrichment analysis using GO and KEGG pathways.

## Overview

Breast cancer is one of the most common cancers worldwide, and it consists of several molecular subtypes that differ in their biological characteristics and treatment responses. Accurate identification of these subtypes is important for diagnosis and personalized medicine.

This project applies machine learning techniques to classify breast cancer molecular subtypes using gene expression data from the **GSE45827** dataset available in the NCBI Gene Expression Omnibus (GEO). In addition to comparing different classification models, the project also explores the biological significance of the selected genes through Gene Ontology (GO) and KEGG pathway enrichment analysis.

This project was developed as part of my undergraduate research work in Bioinformatics and Machine Learning.

---

## Project Highlights

- Gene expression-based breast cancer subtype classification
- Comparison of four supervised machine learning models
- ANOVA F-test for feature selection
- PCA for dimensionality reduction and visualization
- 10-fold stratified cross-validation
- Gene annotation using GPL570 platform
- Functional enrichment analysis using GO and KEGG
- End-to-end machine learning and bioinformatics workflow

## Dataset

- **Dataset:** GSE45827
- **Source:** NCBI Gene Expression Omnibus (GEO)
- **Platform:** GPL570 (Affymetrix Human Genome U133 Plus 2.0 Array)

The processed dataset contains **141 tissue samples** from five breast cancer molecular subtypes:

- Basal
- HER2-positive
- Luminal A
- Luminal B
- Normal

---

## Project Workflow

The project follows a complete machine learning and bioinformatics pipeline:

- Data preprocessing
- Metadata cleaning
- Label extraction
- Feature selection using ANOVA F-test
- Principal Component Analysis (PCA)
- Machine Learning model training
- Model evaluation
- 10-fold Stratified Cross-Validation
- Confusion Matrix
- ROC Curve and AUC Analysis
- Gene Annotation
- Heatmap Visualization
- Gene Ontology (GO) Enrichment Analysis
- KEGG Pathway Analysis

---

## Machine Learning Models

The following supervised machine learning algorithms were evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- XGBoost

---

## Results

The performance of four supervised machine learning models was compared using both an independent test set and 10-fold stratified cross-validation.

| Model | Test Accuracy |
|--------|--------------|
| Logistic Regression | 100% |
| Support Vector Machine | 100% |
| Random Forest | 96.55% |
| XGBoost | 96.55% |

Among all models, the Support Vector Machine achieved the most consistent performance during cross-validation, indicating better generalization across different data splits.

## Project Figures

### PCA Visualization

![PCA](figures/pca_plot.png)

### ROC Curve

![ROC](figures/roc_curve.png)

### Heatmap

![Heatmap](figures/heatmap.png)

### GO Enrichment Analysis

![GO](figures/go_barplot.png)

### KEGG Pathway Analysis

![KEGG](figures/kegg_barplot.png)

## Functional Enrichment

The selected genes were further analyzed using:

- Gene Ontology (GO)
- KEGG Pathway Analysis

The enrichment analysis showed that many of the selected genes are involved in:

- Cell Cycle
- DNA Replication
- p53 Signaling Pathway
- Mitotic Spindle Organization
- Chromosome Segregation
- Cytokinesis

These findings indicate that the selected genes are biologically relevant and closely associated with breast cancer progression.

---

## Project Structure

```
Breast_Cancer_Subtype_Classification/

│── data/
│── results/
│── figures/
│── paper/

│── 01_Data_Preprocessing_and_Exploration.ipynb
│── 02_Feature_Selection_and_Model_Training.ipynb
│── 03_Model_Evaluation_and_Visualization.ipynb
│── 04_Gene_Annotation_and_Functional_Analysis.ipynb
│── 05_Final_Results_and_Export.ipynb

│── README.md
│── requirements.txt
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- GSEApy
- GEOparse

---

## Future Improvements

Some possible extensions of this project include:

- Validation using external GEO or TCGA datasets
- RNA-Seq data analysis
- Deep learning models for subtype classification
- Multi-omics integration
- Deployment as a web application

---

## Author

**Iqra Shaikh**

B.Sc. Chemistry | Aspiring Bioinformatician & Data Scientist

Interested in Machine Learning, Bioinformatics, Cancer Genomics, and Artificial Intelligence.

---
## License

This project is intended for educational and research purposes.
---
## License

This project is licensed under the MIT License. See the LICENSE file for more details.s project is intended for educational and research purposes. 

## Citation

If you use this project or its code in your research or academic work, please cite the associated research paper or acknowledge this repository.

Author: **Iqra Shaikh**

Project: *Breast Cancer Molecular Subtype Classification using Machine Learning and Functional Enrichment Analysis*










