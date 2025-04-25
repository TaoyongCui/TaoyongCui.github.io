---
title: "MSGNN: Masked Schema based Graph Neural Networks"
collection: publications
category: manuscripts
permalink: 'https://www.nature.com/articles/s41467-025-57101-4'
excerpt: 'Hao Liu, Qianwen Yang, **Taoyong Cui**, Wei Wang'
date: 2024-12-1
venue: 'Proceedings of the VLDB Endowment, 2024, 18(3): 571-584.'
paperurl: 'https://dl.acm.org/doi/10.14778/3712221.3712226'


---
Heterogeneous graph representation learning aims to extract low-dimensional node representations from complex networks with different types of entities and relationships. With the prevalence of heterogeneous information networks (HINs) in real-world scenarios, it is of vital significance for a network embedding model to handle heterogeneity and capture as much semantic information as possible. Existing works can be roughly categorized into meta-path-based and adjacent matrix-based methods depending on their definition of node neighborhoods. Meta-path-based methods aim to capture semantic similarities but require manual design. Adjacent matrix-based methods focus on structural information but may risk losing semantic context. In this work, we propose using schema instances representing node minimal complete contexts to embed HINs, aiming to integrate the advantages of both methods and avoid their deficiencies. We introduce Masked Schema based Graph Neural Networks (MSGNN), which combines schema instances with bi-level self-supervised learning and mask technique to acquire effective context representations. Furthermore, we propose a decomposition-reconstruction schema instance retrieval strategy to ensure efficient instance searching. Comprehensive experiments demonstrate that MSGNN outperforms state-of-the-art models. In the link prediction task, the F1-score has improved by up to 16.08% compared to the suboptimal method.
