---
id: w10-nnigam2-rf-mtry-correlation
title: "Why lowering mtry helps random forests"
author: "Neel Nigam (nnigam2)"
---

When mtry = p, a random forest is the same as bagging. Lowering mtry makes each individual tree worse, but it often makes the forest better. Why does this happen, in terms of the correlation between trees and the variance of their average? And can a small mtry hurt, for example when only 2 out of 100 predictors actually matter?
