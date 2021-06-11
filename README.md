# sobol_sensitivity

Demo of variance-based sensitivity analysis.

[Variance-based sensitivity analysis](https://en.wikipedia.org/wiki/Variance-based_sensitivity_analysis) decomposes the variance of a model output into fractions that can be attributed to model inputs.
Here we use [SALib](https://salib.readthedocs.io/en/latest/) a sensitivity analysis package to explore which parameters matter most for the impact. Here, we will explore the sensitivity of the momentum enhancehment factor beta to various parameters related to [DART](https://dart.jhuapl.edu/).

