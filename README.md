# isotope-geographic-authentication

Isotope Geographic Authentication (Lactoferrin)

Executive Summary: 
- This project applies multivariate stable isotope analysis (δ¹³C, δ¹⁵N, δ³⁴S) to determine whether lactoferrin samples can be differentiated by country of origin.
- Using Principal Component Analysis (PCA), clear country-level clustering was observed. A pilot sample labelled as Australian was found to be isotopically inconsistent with confirmed Australian reference samples.

Methodology:
- Data cleaning and scaling
- Principal Component Analysis (PCA)
- Variance decomposition
- Loadings interpretation
- Confidence ellipse comparison

Key Results:

- PC1: 56% variance explained
- PC2: 28% variance explained
- Total (PC1 + PC2): 84%
Australian samples formed a tight isotopic cluster.
The pilot sample lay outside the Australian 95% confidence region.

PCA Score Plot
<img width="788" height="485" alt="pca_score_plot" src="https://github.com/user-attachments/assets/483a7fd3-88e8-41a1-9288-864b48148ac2" />


PCA Variable Plot
<img width="553" height="485" alt="pca_variable_plot" src="https://github.com/user-attachments/assets/71138398-3ebb-439c-8a8b-cf4110ce8089" />


Tech Stack:
- R
- tidyverse
- factoextra
- prcomp()

Skills Demonstrated:
- Multivariate statistical analysis
- Unsupervised learning
- Scientific data interpretation
- Forensic-style authenticity assessment
