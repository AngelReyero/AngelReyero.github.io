---
title: "A primer on linear classification with missing data"
collection: publications
category: conferences
excerpt: 'Prediction in classification with missing values using linear classifiers.'
date: 2025-01-25
venue: AISTATS
paperurl: 'https://arxiv.org/abs/2405.09196'
citation: 'Reyero Lobo, A. D., Ayme, A., Boyer, C., and Scornet, E. (2025). A primer on linear classification with
missing data.'
---

Supervised learning with missing data aims at building the best prediction of a target output based on partially-observed inputs. Major approaches to address this problem can be decomposed into (i) impute-then-predict strategies, which first fill in the empty input components and then apply a unique predictor and (ii) Pattern-by-Pattern (P-b-P) approaches, where a predictor is built on each missing pattern. In this paper, we theoretically analyze how three classical linear classifiers, namely perceptron, logistic regression and linear discriminant analysis (LDA), behave with Missing Completely At Random (MCAR) data, depending on the strategy (imputation or P-b-P) used to handle missing values. We prove that both imputation and P-b-P approaches are ill-specified in a logistic regression framework, thus questioning the relevance of such approaches to handle missing data. The most favorable auspices to perform classification with missing data concern P-b-P LDA methods. We provide finite-sample bounds for the excess risk in this framework, even for high-dimensional or MNAR settings. Experiments illustrate our theoretical findings.
