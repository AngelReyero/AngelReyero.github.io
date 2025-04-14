---
title: "Measuring Variable Importance in Heterogeneous Treatment Effects with Confidence"
collection: publications
category: conferences
excerpt: 'PermuCATE is a new method for assessing variable importance in estimating heterogeneous treatment effects. It improves on existing techniques by reducing variance, making it more reliable—especially in low-data settings like biomedical applications.'
date: 2025-01-30
venue: Preprint
paperurl: 'https://arxiv.org/abs/2408.13002'
citation: 'Paillard, J., Reyero Lobo, A., Kolodyazhniy, V., Thirion, B., & Engemann, D. A. (2025). Measuring variable importance in heterogeneous treatment effects with confidence.'
---

Causal machine learning (ML) holds promise for estimating individual treatment effects from complex data. For successful real-world applications using machine learning methods, it is of paramount importance to obtain reliable insights into which variables drive heterogeneity in the response to treatment. We propose PermuCATE, an algorithm based on the Conditional Permutation Importance (CPI) method, for statistically rigorous global variable importance assessment in the estimation of the Conditional Average Treatment Effect (CATE). Theoretical analysis of the finite sample regime and empirical studies show that PermuCATE has lower variance than the Leave-One-Covariate-Out (LOCO) reference method and provides a reliable measure of variable importance. This property increases statistical power, which is crucial for causal inference in the limited-data regime common to biomedical applications. We empirically demonstrate the benefits of PermuCATE in simulated and real-world health datasets, including settings with up to hundreds of correlated variables. 
