# Statistics — Modeling

[← Back to index](./index.md)

---

## Regression & Modeling (`STAT_REGRESS`)

Fitting a functional relationship between predictors and an outcome —
starting with ordinary least squares linear regression and extending to
logistic regression (categorical outcomes), generalized linear models, and
regularized variants (ridge, lasso) that handle high-dimensional or
collinear predictors. The underlying assumptions (linearity, independence
of errors, homoscedasticity, no severe multicollinearity) matter more than
they get credit for — a regression that violates them can still produce a
plausible-looking coefficient with a badly wrong standard error. This is
also the node where "statistical significance" and "practical significance"
most visibly diverge: a coefficient can be significant at any sample size
if it's estimated precisely enough, even when the effect size is
substantively meaningless.

**Status:** [ ]

**Resources:**
- Gareth James et al., *An Introduction to Statistical Learning*
- Andrew Gelman & Jennifer Hill, *Data Analysis Using Regression and Multilevel/Hierarchical Models*
- Frank Harrell, *Regression Modeling Strategies*

---

## Multivariate & Time Series Methods (`STAT_MULTI`)

Extending modeling to many variables at once and to data indexed by time.
The multivariate side covers dimensionality reduction (principal component
analysis, factor analysis) and classification/clustering methods that
handle correlated predictor structure. The time-series side is its own
discipline: autocorrelation, stationarity, ARIMA models, and the specific
danger of spurious regression, where two unrelated trending series can
produce a beautiful-looking but meaningless correlation (a classic
demonstration: nearly any two macroeconomic time series trending upward
over decades will correlate strongly, without either causing the other).
This is the node that feeds most directly into both machine learning
(feature engineering, forecasting) and applied macroeconomics, where almost
all the interesting data comes indexed by time.

**Status:** [ ]

**Resources:**
- Robert Shumway & David Stoffer, *Time Series Analysis and Its Applications*
- James Hamilton, *Time Series Analysis*
- Rob Hyndman & George Athanasopoulos, *Forecasting: Principles and Practice* (free online)
