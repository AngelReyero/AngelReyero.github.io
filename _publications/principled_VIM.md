---
title: "A principled approach for comparing Variable Importance"
collection: publications
category: conferences
excerpt: 'The paper introduces an axiomatic framework and a principled approach to create and evaluate variable importance measures (VIMs), ensuring they avoid spurious correlations and enable fair comparisons. It also offers examples to help practitioners choose and estimate suitable VIMs for their goals and data.'
date: 2025-07-23
venue: Preprint
paperurl: 'https://arxiv.org/abs/2507.17306'
citation: 'Reyero-Lobo, A., Neuvial, P. , & Thirion, B. (2025). A principled approach for comparing Variable Importance.'
---

Variable importance measures (VIMs) aim to quantify the contribution of each input covariate to the predictability of a given output. With the growing interest in explainable AI, numerous VIMs have been proposed, many of which are heuristic in nature. This is often justified by the inherent subjectivity of the notion of importance. This raises important questions regarding usage: What makes a good VIM? How can we compare different VIMs?

In this paper, we address these questions by: (1) proposing an axiomatic framework that bridges the gap between variable importance and variable selection. This framework formalizes the intuitive principle that features providing no additional information should not be assigned importance. It helps avoid false positives due to spurious correlations, which can arise with popular methods such as Shapley values; and (2) introducing a general pipeline for constructing VIMs, which clarifies the objective of various VIMs and thus facilitates meaningful comparisons. This approach is natural in statistics, but the literature has diverged from it.

Finally, we provide an extensive set of examples to guide practitioners in selecting and estimating appropriate indices aligned with their specific goals and data.
