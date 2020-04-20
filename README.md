# Domain_adaptation
Domain Adaptation for Digits

This is technique for end-to-end domain adaptation with neural networks, the task of inferring class labels for an unlabeled target domain based on the statistical properties of a labeled source domain. My training scheme follows the paradigm that in order to effectively derive class labels for the target domain, a network should produce statistically domain invariant embeddings, while minimizing the classification error on the labeled source domain. I accomplish this by reinforcing associations between source and target data directly in embedding space.
