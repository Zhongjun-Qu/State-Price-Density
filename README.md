# State-Price-Density
This R program accompanies the paper: Lu and Qu (2021), “Sieve Estimation of Option-Implied State Price Density”, Journal of Econometrics, 224 (2021), 88-112.
This is a nonparametric estimator for the state price density implied by a cross-section of European options with different strikes and a common maturity. The proposed estimator has two features: (1) It extracts information from both call and put options instead of only call options. (2) It does not require estimating any second-order derivative; instead, it solves a constrained and penalized linear regression. The procedure can work with both daily and high-frequency observations.
