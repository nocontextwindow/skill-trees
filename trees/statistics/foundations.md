# Statistics — Foundations

[← Back to index](./index.md)

---

## Probability Theory (`STAT_PROB`)

The mathematics of uncertainty: random variables, distributions, expectation
and variance, independence, conditional probability, and the two limit
theorems that make statistics possible at all — the Law of Large Numbers
(averages converge to the true mean) and the Central Limit Theorem (sums of
many independent random variables look Gaussian, regardless of the
underlying distribution). Bayes' theorem lives here too, and it's worth
sitting with until it's intuitive rather than just memorized, since it's
the hinge between "prior belief" and "evidence" that all of Bayesian
statistics and rational updating depend on. This is real math (it rests on
measure theory at the rigorous end) but almost all practical work only
needs the discrete/continuous distribution toolkit and a solid feel for
what "expected value" and "variance" actually mean.

**Status:** [ ]

**Resources:**
- Sheldon Ross, *A First Course in Probability*
- Joseph Blitzstein & Jessica Hwang, *Introduction to Probability*
- Blitzstein's Harvard Stat 110 lectures (free, YouTube)

---

## Descriptive Statistics (`STAT_DESC`)

Summarizing data before you try to infer anything from it: measures of
central tendency (mean, median, mode) and spread (variance, standard
deviation, interquartile range), distribution shape (skewness, kurtosis,
outliers), and honest visualization (histograms, box plots, scatter plots)
that doesn't mislead. The unglamorous skill here — actually looking at your
data before modeling it — is disproportionately valuable; Anscombe's
quartet (four datasets with identical summary statistics but wildly
different shapes) is the canonical demonstration of why summary numbers
alone can lie. This is also where correlation gets introduced, along with
the immediate caveat that correlation is not causation, which sets up
everything the inference and causal-inference sections have to say about
actually establishing causal claims.

**Status:** [ ]

**Resources:**
- John Tukey, *Exploratory Data Analysis*
- Edward Tufte, *The Visual Display of Quantitative Information*
- Darrell Huff, *How to Lie with Statistics* (short, old, still the best intro to the pitfalls)
