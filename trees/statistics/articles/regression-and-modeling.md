# Regression & Modeling

[← Statistics](../index.md) · `STAT_REGRESS`

Fitting a functional relationship between variables — the workhorse of
applied statistics and the place where "explain" and "predict" get
conflated. A model tuned for predictive accuracy and a model built to
estimate one interpretable coefficient are different objects with different
correct practices; adding a control that improves fit can destroy the
causal interpretation of the coefficient you cared about, and collider
bias means some controls make things strictly worse. Model selection
procedures — stepwise, all-subsets, anything driven by the same data you
then report inference on — invalidate the standard errors they print.
Diagnostics are cheap and routinely skipped, and the bias-variance tradeoff
is easy to state and hard to actually feel until a model fails out of
sample.

## Open questions

- What is this model *for* — prediction, estimation of one effect, or
  description — and does every choice in it serve that purpose?
- Which control variables improve the estimate and which quietly destroy
  it, and do I have a principled way to tell before fitting?
- How much interpretability am I willing to trade for accuracy, and does
  that tradeoff look different when someone has to act on the output?
- When is a linear model with a well-understood failure mode preferable to
  a flexible one with an opaque one?
- If the model selection was data-driven, what are the reported p-values
  and intervals actually worth?
- How do I know a model has failed rather than merely fit poorly — what
  would falsify my use of it?

## Notes

## Resources
