---
title: "Semi-knockoffs: a model-agnostic conditional independence testing method with finite-sample guarantees"
collection: publications
category: conferences
excerpt: 'We propose a conditional independence testing procedure with valid type-I error and FDR control that accommodates any pretrained model and requires no train–test split.'
date: 2026-01-30
venue: Preprint
paperurl: 'https://arxiv.org/abs/2601.23124'
citation: 'Angel Reyero-Lobo, Bertrand Thirion, and Pierre Neuvial.Semi-knockoffs: a model-agnostic conditional independence testingmethod with finite-sample guarantees, 2026'
---

Conditional independence testing (CIT) is essential for reliable scientific discovery. It prevents spurious findings and enables controlled feature selection. Recent CIT methods have used machine learning (ML) models as surrogates of the underlying distribution. However, model-agnostic approaches require a train-test split, which reduces statistical power. We introduce Semi-knockoffs, a CIT method that can accommodate any pre-trained model, avoids this split, and provides valid p-values and false discovery rate (FDR) control for high-dimensional settings. Unlike methods that rely on the model-X assumption (known input distribution), Semi-knockoffs only require conditional expectations for continuous variables. This makes the procedure less restrictive and more practical for machine learning integration. To ensure validity when these expectations are estimated, we present two new theoretical results: (i) stability for regularized models trained with a null feature and (ii) the double-robustness property.
