---
id: w03-nnigam2-multicollinearity-ridge
title: "Multicollinearity and ridge geometry"
author: "Neel Nigam (nnigam2)"
---

Suppose two predictors in a regression are highly correlated. Explain why this correlation makes the OLS coefficient estimates for those two predictors unstable (large variance, sign flips across resamples) even though the fitted values and overall predictions may remain stable. Then explain concretely how adding a ridge penalty term changes the geometry of the optimization problem (e.g., in terms of the eigenvalues of X^T X vs. X^T X + λI) to fix this instability, and why it does so at the cost of introducing bias.
