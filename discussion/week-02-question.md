---
id: w02-nnigam2-cv-selection-bias
title: "Why full-data selection biases CV error"
author: "Neel Nigam (nnigam2)"
---

When we perform model selection, such as choosing hyperparameters or a variable subset, using the entire dataset and then report the cross-validated error computed on that same data as an estimate of test performance, why does this systematically understate the true test error? Discuss how information from the validation folds leaks into the selection process during this reuse, and what practices, such as nested cross-validation or a genuinely held-out test set, would give an honest estimate instead.
