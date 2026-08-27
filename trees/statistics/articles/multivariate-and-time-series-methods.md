# Multivariate & Time Series Methods

[← Statistics](../index.md) · `STAT_MULTI`

Data where the observations are not independent — many correlated
dimensions, or a sequence through time. Both break the assumption almost
every introductory method rests on, and both punish naive practice
severely. In high dimensions, distance and density stop behaving
intuitively and dimensionality reduction becomes a modelling choice rather
than a preprocessing step. In time series, autocorrelation inflates
apparent sample size, non-stationarity makes ordinary regression produce
spurious relationships between unrelated trending series, and any
validation scheme that shuffles observations leaks the future into the
past. Forecasting is also the sub-field where the gap between in-sample fit
and out-of-sample performance is widest and most humbling.

## Open questions

- How much of my sample is real information once autocorrelation is
  accounted for?
- Is a latent factor from a dimensionality reduction a discovered structure
  or an artifact of the rotation and scaling I chose?
- Where is the line between a genuine regime change and a model that was
  always wrong and finally showed it?
- What forecast horizon is honest for a given system, and how would I
  establish that rather than assert it?
- If out-of-sample performance is the only real test, how do I get enough
  genuinely out-of-sample data to trust the answer?
- Which of my time-series intuitions came from finance-shaped data and
  would mislead me on physical or biological series?

## Notes

## Resources
