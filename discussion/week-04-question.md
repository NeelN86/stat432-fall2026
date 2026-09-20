---
id: w04-nnigam2-lasso-ridge-sparsity
title: "Why lasso, but not ridge, gives exact zeros"
author: "Neel Nigam (nnigam2)"
---

Consider a single standardized predictor $x$ (so $\sum_i x_i^2 = 1$) and response $y$, with ordinary least-squares coefficient $\hat\beta_{LS} = \sum_i x_i y_i$. The lasso estimate of the slope minimizes

$$\frac{1}{2}\sum_i (y_i - \beta x_i)^2 + \lambda|\beta|, \quad \lambda \geq 0,$$

with closed-form solution $\hat\beta_{lasso}(\lambda) = \text{sign}(\hat\beta_{LS})(|\hat\beta_{LS}| - \lambda)_+$, while the corresponding ridge solution is $\hat\beta_{ridge}(\lambda) = \hat\beta_{LS}/(1+\lambda)$.

Using these two formulas directly, explain why there is an entire range of $\lambda$ values (not just a single critical value) for which $\hat\beta_{lasso} = 0$ exactly, while $\hat\beta_{ridge}$ never equals zero for any finite $\lambda > 0$.
