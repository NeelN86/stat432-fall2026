---
id: w11-nnigam2-kmeans-scaling
title: "Why k-means splits by income without scaling"
author: "Neel Nigam (nnigam2)"
---

Suppose I run k-means on customer data with two variables, annual income (in dollars, ranging from about 20,000 to 200,000) and age (in years, ranging from about 18 to 80). If I don't standardize the variables, why do the clusters end up separating customers almost entirely by income? And is standardizing both variables to unit variance always the right fix, or can it sometimes give one variable more influence than it deserves?
