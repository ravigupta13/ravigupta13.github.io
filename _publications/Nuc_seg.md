---
title: "Combining Datasets with Different Label Sets for Improved Nucleus Segmentation and Classification"
collection: publications
permalink: /publication/Nuc_seg
excerpt: 'We propose a method to train DNNs for instance segmentation and classification on multiple datasets where the set of classes across the
datasets are related but not the same.'
date: 2024-02-19
venue: 'Proceedings of the 17th International Joint Conference on Biomedical Engineering Systems and Technologies - BIOIMAGING, Rome, Italy'
paperurl: 'https://arxiv.org/abs/2310.03346'

---

Segmentation and classification of cell nuclei in histopathology images using deep neural networks (DNNs) can save pathologists' time for diagnosing
various diseases, including cancers, by automating cell counting and morphometric assessments. It is now well-known that the accuracy of DNNs increases
with the sizes of annotated datasets available for training. Although multiple datasets of histopathology images with nuclear annotations and class 
labels have been made publicly available, the set of class labels differ across these datasets. We propose a method to train DNNs for instance 
segmentation and classification on multiple datasets where the set of classes across the datasets are related but not the same. 
Specifically, our method is designed to utilize a coarse-to-fine class hierarchy, where the set of classes labeled and annotated in a dataset can be
at any level of the hierarchy, as long as the classes are mutually exclusive. Within a dataset, the set of classes need not even be at the same
level of the class hierarchy tree. Our results demonstrate that segmentation and classification metrics for the class set used by the test split 
of a dataset can improve by pre-training on another dataset that may even have a different set of classes due to the expansion of the training
set enabled by our method. Furthermore, generalization to previously unseen datasets also improves by combining multiple other datasets with 
different sets of classes for training. The improvement is both qualitative and quantitative. The proposed method can be adapted for various 
loss functions, DNN architectures, and application domains. 

