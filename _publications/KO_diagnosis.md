---
title: "When Knockoffs fail: diagnosing and fixing non-exchangeability of Knockoffs"
collection: publications
category: conferences
excerpt: 'This work identifies and addresses failures of the exchangeability assumption in knockoff-based inference by introducing a diagnostic test and proposing a robust alternative construction method.'
date: 2025-04-29
venue: Preprint
paperurl: 'https://arxiv.org/abs/2407.06892'
citation: 'Blain, A., Reyero Lobo, A., Linhart, J., Thirion, B., & Neuvial, P. (2025). When Knockoffs fail: Diagnosing and fixing non-exchangeability of Knockoffs.'
---

Knockoffs are a popular statistical framework that addresses the challenging problem of conditional variable selection in high-dimensional settings with statistical control. Such statistical control is essential for the reliability of inference. However, knockoff guarantees rely on an exchangeability assumption that is difficult to test in practice, and there is little discussion in the literature on how to deal with unfulfilled hypotheses. This assumption is related to the ability to generate data similar to the observed data. To maintain reliable inference, we introduce a diagnostic tool based on Classifier Two-Sample Tests. Using simulations and real data, we show that violations of this assumption occur in common settings for classical knockoff generators, especially when the data have a strong dependence structure. As a consequence, knockoff-based inference suffers from a massive inflation of false positives. We show that the diagnostic tool correctly detects such behavior. We show that an alternative knockoff construction, based on constructing a predictor of each variable based on all others, solves the issue. We also propose a computationally-efficient variant of this algorithm and show empirically that this approach restores error control on simulated data and semi-simulated experiments based on neuroimaging data. 
