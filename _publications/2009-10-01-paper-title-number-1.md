---
title: Adversarial Transport Terms for Unsupervised Domain Adaptation"
collection: publications
permalink: /publication/chatty
excerpt: 'The new technique, ATT, enhances unsupervised domain adaptation by introducing a novel transport loss that displaces classifier outputs to reduce class confusion and improve domain-invariant representations, leading to superior UDA results on benchmark datasets.'
date: 2024-12-02
venue: 'Proceedings of the 27th International Conference on Pattern Recognition, Kolkata, India'

---
We propose a new technique called ATT: Adversarial Transport Terms for Unsupervised Domain Adaptation. Adversarial training is commonly used for learning domain-invariant representations by reversing the gradients from a domain discriminator head to train the feature extractor layers of a neural network. We propose significant modifications to the adversarial head, its training objective, and the classifier head. With the aim of reducing class confusion, we introduce a sub-network which displaces the classifier outputs of the source and target domain samples in a learnable manner. We control this movement using a novel transport loss that spreads class clusters away from each other and makes it easier for the classifier to find the decision boundaries for both the source and target domains. The results of adding this new loss to a careful selection of previously proposed losses leads to improvement in UDA results compared to the previous state-of-the-art methods on benchmark datasets. We show the importance of the proposed loss term using ablation studies and visualization of the movement of target domain sample in representation space.

[Paper Link](https://link.springer.com/chapter/10.1007/978-3-031-78166-7_1)

Recommended citation: Chirag, P., Wagle, M., Gupta, R.K., Pranav, J.P., Sethi, A. (2025). Adversarial Transport Terms for Unsupervised Domain Adaptation. In: Antonacopoulos, A., Chaudhuri, S., Chellappa, R., Liu, CL., Bhattacharya, S., Pal, U. (eds) Pattern Recognition. ICPR 2024. Lecture Notes in Computer Science, vol 15302. Springer, Cham. https://doi.org/10.1007/978-3-031-78166-7_1
