---
title: "Unsupervised Domain Adaptation for Medical Images with an Improved Combination of Losses"
collection: publications
permalink: /publication/Dom_ADA
excerpt: 'In this paper we propose a tailored loss function to address the challenges specific to medical images. This loss
combination not only makes the model accurate and robust but also faster in terms of training convergence.'
date: 2024-02-19
venue: 'Proceedings of the 17th International Joint Conference on Biomedical Engineering Systems and Technologies - BIOIMAGING, Rome, Italy'
paperurl: 'https://www.scitepress.org/Papers/2024/123281/123281.pdf'

---

This paper presents a novel approach for unsupervised domain adaptation that is tested on H&E stained his-
tology and retinal fundus images. Existing adversarial domain adaptation methods may not effectively align
different domains of multimodal distributions associated with classification problems. Since our objective is to
enhance domain alignment and reduce domain shifts between these domains by leveraging their unique char-
acteristics, we propose a tailored loss function to address the challenges specific to medical images. This loss
combination not only makes the model accurate and robust but also faster in terms of training convergence.
We specifically focus on leveraging texture-specific features, such as tissue structure and cell morphology, to
enhance adaptation performance in the histology domain. The proposed method – Domain Adaptive Learning
(DAL) – was extensively evaluated for accuracy, robustness, and generalization. We conducted experiments
on the FHIST and a retina dataset and the results show that DAL significantly surpasses the ViT-based and
CNN-based state-of-the-art methods by 1.41% and 6.56% respectively for FHIST dataset while also showing
improved results for the retina dataset.
