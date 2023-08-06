# Bioinformatics Project - Computational Drug Discovery

This repository contains Jupyter notebooks for a Bioinformatics Project focused on Computational Drug Discovery. The project involves building a machine learning model using the ChEMBL bioactivity data for inhibitors.

## Part 1: Download Bioactivity Data 

In this notebook, we perform Data Collection and Pre-Processing from the ChEMBL Database. The [*ChEMBL Database*](https://www.ebi.ac.uk/chembl/) is a curated repository of bioactivity data for over 3.5 million compounds, compiled from more than 100,000 documents, 2.4 million assays, and spanning 16,000 targets and 2,500 cells with 45,000 indications. The data is as of August 25, 2023 (ChEMBL version 33).

## Part 2: Exploratory Data Analysis

In Part 2, we perform Descriptor Calculation and Exploratory Data Analysis. We calculate Lipinski descriptors, which evaluate the druglikeness of compounds based on molecular weight, octanol-water partition coefficient (LogP), hydrogen bond donors, and hydrogen bond acceptors. We also convert IC50 data to pIC50 to facilitate uniform distribution.

## Part 3: Descriptor Calculation and Dataset Preparation

In Part 3, we calculate molecular descriptors, which provide quantitative descriptions of the compounds in the dataset. The resulting descriptors are prepared into a dataset for subsequent model building in Part 4.

## Part 4: Regression Models with Random Forest

Part 4 involves building a regression model for predicting inhibitors using the random forest algorithm.

### Important Note

The project utilizes various bioinformatics tools and data analysis techniques to aid in computational drug discovery. Each notebook is self-contained and focuses on specific aspects of the project.

Throughout the notebooks, you will find detailed instructions, comments, and markdown cells to help you understand the rationale behind each step and the significance of the results obtained. Feel free to explore, modify, and experiment with the code as you progress through the notebooks.

**Note**: Please ensure you have the necessary data files and dependencies installed before running the notebooks. Instructions for data download and setup can be found in each notebook as needed.

---


Feel free to explore the notebooks in the order mentioned above to gain a comprehensive understanding of the Computational Drug Discovery project. For any questions or feedback, please contact the project contributors.

Happy learning and drug discovery!





## References

1. ChEMBL Database. "ChEMBL Version 33 (Release date: May 2023)." Available online: [URL to ChEMBL Database](https://chembl.gitbook.io/chembl-interface-documentation)
2. Yap, C. W. "PaDEL-Descriptor: An Open-Source Software to Calculate Molecular Descriptors and Fingerprints." Journal of Computational Chemistry 32, no. 7 (2011): 1466-1474. DOI: 10.1002/jcc.21707. Available online: [URL to PaDEL-Descriptor Paper](https://doi.org/10.1002/jcc.21707)
3. Estrogen Receptor Alpha QSAR Repository. "ER_alpha_RO5 Jupyter Notebook." Available online: [URL to ER_alpha_RO5 Jupyter Notebook](https://github.com/chaninlab/estrogen-receptor-alpha-qsar/blob/master/02_ER_alpha_RO5.ipynb)
4. Machine Learning Mastery. "Nonparametric Statistical Significance Tests in Python." Available online: [URL to Nonparametric Statistical Significance Tests in Python](https://machinelearningmastery.com/nonparametric-statistical-significance-tests-in-python/)
5. Data Professor GitHub Repository. Available online: [URL to Data Professor GitHub Repository](https://github.com/dataprofessor)