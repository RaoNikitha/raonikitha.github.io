---
title: "Handling Class Imbalance with POISE: pAUC Optimization in Supervised Experiments"
collection: publications
permalink: /publications/preprints/2020-11-25-pAUC-Maximization
excerpt: "A preprint of this work is available."
date: 2020-11-25
venue: ''
year: '2020'
authors: '<b>Nikitha Rao</b>, Sreangsu Acharyya'
arxiv: '\files\preprints\pAUC_Maximization.pdf'
#paperurl: 'https://arxiv.org/abs/2005.08591'
#bib: 'https://ui.adsabs.harvard.edu/abs/2020arXiv200208936K'
---

Recognizing the well known deficiencies of classification accuracy as a quality metric in class imbalanced scenarios, we reaffirm the use of partial AUC (pAUC), which is an improvement over the related metric of AUC. Optimizing pAUC is formulated as a two person zero-sum game between (i) an adversary that selects a fixed fraction of negative examples and (ii) a learner that needs to assign higher scores to the positive examples, no matter the choice of the adversary. The optimal scoring function is obtained as an equilibrium of this game. This optimization is combined with an efficient, task specific vector embedding that captures the geometry induced by decision trees, thereby extending the method to datasets that are not linearly separable. We evaluate our proposed solution by comparing its performance against state of the art alternatives (such as LambdaMART, RankSVM) as well as popular alternatives such as SMOTE and make note of the superior performance obtained.

A preliminary version of this work won the <b>Best Short Paper Award </b> at MLADS-SYNAPSE 2020 (<i>Microsoft internal Conference on Machine Learning and Data Science for Asia-Pacific region.</i>) [Acceptance Rate ≈ 8%]

> Collaborators - Sreangsu Acharyya

Please find all the relevant resources below:
1. [Preprint](\files\preprints\pAUC_Maximization.pdf){:target="_blank"}
