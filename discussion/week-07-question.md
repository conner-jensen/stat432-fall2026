---
id: w07-connerj2-lda-pooled-cov
title: "Why does LDA pool the covariance?"
author: "Conner Jensen (connerj2)"
---

LDA uses one shared covariance $\boldsymbol\Sigma$ for every class. QDA fits a separate $\boldsymbol\Sigma_k$ in each class.

Why pool? What do we gain in variance, and what do we give up if the class covariances are not actually the same?
