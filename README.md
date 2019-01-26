# propci - Proportion Confidence Interval and the Wilson Score

The formula for Edwin Bidwell Wilson's "Score Interval" (described in [his 1927 paper](https://doi.org/10.1080/01621459.1927.10502953)) provides a relatively straightforward method to estimate the confidence interval for the success rate, i.e., the proportion between successes and number of trials.
The document [https://eschen42.github.io/propci/propci.pdf](https://eschen42.github.io/propci/propci.pdf) explores how simply the Wilson Score may be applied in R using the `epitools::binom.wilson` function even for very low and very high proportions where the normal approximation is not applicable, the effect of increasing the number of trials on the width of the confidence interval, and how the Wilson Score formula may be derived.
This repository was created to maintain this document and present it using GitHub Pages.
