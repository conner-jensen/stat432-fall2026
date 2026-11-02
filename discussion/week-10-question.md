---
id: w10-connerj2-bagging-trees
title: "Why does averaging trees help prediction?"
author: "Conner Jensen (connerj2)"
---

A single deep tree can change a lot if you redraw a few training rows, so its prediction at a point can jump.

Why does averaging many bootstrap trees usually reduce that variability? When would the average not help much, for example if every tree makes almost the same split?
