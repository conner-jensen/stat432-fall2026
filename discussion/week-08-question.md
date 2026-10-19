---
id: w08-connerj2-svm-cost-cv
title: "Why not pick C from training accuracy?"
author: "Conner Jensen (connerj2)"
---

A linear SVM with a very large cost $C$ can classify every training point correctly when the data are close to separable.

Why is that training accuracy a bad way to choose $C$? What can go wrong on new data, compared with picking $C$ by cross-validation?
