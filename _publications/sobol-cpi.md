---
title: "Conditional Feature Importance revisited: Double Robustness, Efficiency and Inference"
collection: publications
category: conferences
excerpt: 'Theoretical study of CFI, establishing a double-robust estimation property, clarifying its target estimand and bias, and proposing a procedure with valid type-I error control.'
date: 2025-01-30
venue: Preprint
paperurl: 'https://arxiv.org/abs/2501.17520'
citation: 'Reyero Lobo, A., Neuvial, P., and Thirion, B. Sobol-cpi: a doubly robust conditional permutation importance statistic. 2025'
---

Conditional Feature Importance (CFI) was introduced long ago to account for the relationship between the studied feature and the rest of the input. However, CFI has not yet been studied from a theoretical perspective because the conditional sampling step has in general been exclusively practical. In this article, we demonstrate that the recent Conditional Permutation Importance (CPI) is indeed a valid implementation of this concept. Under the conditional null hypothesis, we then establish a double robustness property that can be leveraged for variable selection: with either a valid model or a valid conditional sampler, the method correctly identifies null coordinates.

Under the alternative hypothesis, we study the theoretical target and link it to the popular Total Sobol Index (TSI). We introduce the Sobol-CPI, which generalizes CPI/CFI, prove that it is nonparametrically efficient, and provide a bias correction. Finally, we propose a consistent and valid type-I error test and present numerical experiments that illustrate our findings.

