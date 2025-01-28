---
title: "HER2 and FISH Status Prediction in Breast Biopsy H&E-Stained Images Using Deep Learning"
collection: publications
permalink: /publication/HER2_FISH_status
excerpt: 'In this work, we employed a customized weak supervision classification technique combined with MoCov2 contrastive learning for self-supervised feature extraction training to predict HER2 status.'
date: 2024-11-23
venue: '2024 IEEE 24th International Conference on Bioinformatics and Bioengineering (BIBE), Kragujevac, Serbia'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10820489'

---

The current standard for detecting human epidermal growth factor receptor 2 (HER2) status in breast cancer patients relies on HER2 expression identified through immunohistochemistry (IHC) or amplification identified through fluorescence in situ hybridization (FISH). However, hematoxylin and eosin (H&E) tumor stains are more widely available, and accurately predicting HER2 status using H&E could reduce costs and expedite treatment selection. Deep Learning algorithms for H&E have shown effectiveness in predicting various cancer features and clinical outcomes, including moderate success in HER2 status prediction. In this work, we employed a customized weak supervision classification technique combined with MoCov2 contrastive learning for self-supervised feature extraction training to predict HER2 status. We trained our pipeline on 182 publicly available H&E whole slide images (WSIs) from The Cancer Genome Atlas (TCGA), for which annotations by the pathology team at Yale School of Medicine are publicly available. Our pipeline achieved an Area Under the Curve (AUC) of 0.85 ±0.02 across four different test folds. Additionally, we tested our model on 44 H&E slides from the TCGA-BRCA dataset, which had an HER2 score of 2+ and included corresponding HER2 status and FISH test results. These cases are considered equivocal for IHC, requiring an expensive FISH test on their IHC slides for disambiguation. Our pipeline demonstrated an AUC of 0.81 on these challenging H & E slides. Reducing the need for FISH test can have significant implications in cancer treatment equity for underserved populations.

