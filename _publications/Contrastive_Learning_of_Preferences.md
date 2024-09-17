---
title: "Contrastive Learning of Preferences with a Contextual InfoNCE Loss"
date: 2024-08-07
---
A common problem in contextual preference ranking is that a single preferred action is compared against several choices, thereby blowing up the complexity and skewing the preference distribution. In this work, we show how one can solve this problem via a suitable adaptation of the CLIP framework.This adaptation is not entirely straight-forward, because although the InfoNCE loss used by CLIP has achieved great success in computer vision and multi-modal domains, its batch-construction technique requires the ability to compare arbitrary items, and is not well-defined if one item has multiple positive associations in the same batch. We empirically demonstrate the utility of our adapted version of the InfoNCE loss in the domain of collectable card games, where we aim to learn an embedding space that captures the associations between single cards and whole card pools based on human selections. Such selection data only exists for restricted choices, thus generating concrete preferences of one item over a set of other items rather than a perfect fit between the card and the pool.
Our results show that vanilla CLIP does not perform well due to the aforementioned intuitive issues. However, by adapting CLIP to the problem, we receive a model outperforming previous work trained with the triplet loss, while also alleviating problems associated with mining triplets.


[Link to PDF](https://arxiv.org/pdf/2407.05898)
