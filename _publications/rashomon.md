---
title: "Aggregate Models, Not Explanations: Improving Feature Importance Estimation"
collection: publications
category: conferences
excerpt: "We show that model-level ensembling improves the stability and accuracy of feature-importance estimates for expressive machine-learning models, providing theoretical guarantees and empirical validation on benchmarks and UK Biobank proteomic data."
date: 2026-02-12
venue: "International Conference on Machine Learning (ICML 2026)"
paperurl: "https://arxiv.org/abs/2602.11760"
citation: "Joseph Paillard, Angel Reyero Lobo, Denis A. Engemann, Bertrand Thirion. Aggregate Models, Not Explanations: Improving Feature Importance Estimation. In Proceedings of the International Conference on Machine Learning (ICML), 2026."
---

Feature-importance methods show promise in transforming machine learning models from predictive engines into tools for scientific discovery. However, due to data sampling and algorithmic stochasticity, expressive models can be unstable, leading to inaccurate variable importance estimates and undermining their utility in critical biomedical applications. Although ensembling offers a solution, deciding whether to explain a single ensemble model or aggregate individual model explanations is difficult due to the nonlinearity of importance measures and remains largely understudied. Our theoretical analysis, developed under assumptions accommodating complex state-of-the-art ML models, reveals that this choice is primarily driven by the model's excess risk. In contrast to prior literature, we show that ensembling at the model level provides more accurate variable-importance estimates, particularly for expressive models, by reducing this leading error term. We validate these findings on classical benchmarks and a large-scale proteomic study from the UK Biobank. 
