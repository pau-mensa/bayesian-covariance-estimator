# Bayesian covariance estimator
A simple experiment that tries to estimate a covariance matrix based on probabilistic programming and compares the goodness of fit to the most popular methods.

## Results
If you check the notebook you'll see the probabilistic method is consistently superior to the other methods, without needing any tuning. It is much more computationally expensive, so for some cases the tradeoff is probably not worth it.

Much more testing is needed to see what hyperparameters are best and how this performs in multiple scenarios.
