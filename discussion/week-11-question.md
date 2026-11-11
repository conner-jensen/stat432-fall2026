---
id: w11-connerj2-wcss-more-clusters
title: "Why isn't a smaller WCSS enough to pick K?"
author: "Conner Jensen (connerj2)"
---

K-means within-cluster sum of squares can only go down, or stay the same, if you add another cluster. You can always split a group and put a new mean on the leftover points.

Why is that not a good reason to keep increasing $K$? What else would you look at before you trust a clustering?
