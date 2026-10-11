---
id: w07-nnigam2-lda-vs-qda-variance
title: "Why can LDA beat QDA when covariances differ?"
author: "Neel Nigam (nnigam2)"
---

When class covariance matrices clearly differ, why can LDA still achieve lower test error than QDA, especially when the training set is small relative to the number of predictors? Specifically, how does the number of covariance parameters each method estimates (one pooled matrix vs. one per class) drive this trade-off, and at roughly what sample size would we expect QDA’s lower bias to start outweighing its higher variance?
