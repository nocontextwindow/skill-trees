# Optimization for Deep Learning

[← Machine Learning / AI](../index.md) · `ML_OPT`

Fitting these models is a non-convex problem with no guarantee that
gradient descent finds anything good — and yet it reliably does. That gap
between what the theory licenses and what practice observes is the
subject. Learning rate schedules, batch size, normalization, and adaptive
methods all measurably change the solution reached, which means the
optimizer is not a neutral solver but part of the model's inductive bias.
"Implicit regularization" is the name given to this, though it is closer
to a label for the phenomenon than an explanation of it.

## Open questions

- Why does SGD find good solutions in a landscape where nothing
  guarantees it should?
- Is implicit regularization a real explanation of generalization, or a
  name for the part we can't explain?
- Adaptive methods often train faster and generalize worse — is that
  robust, and what mechanism would account for it?
- How much of hyperparameter tuning is learning something about the
  problem versus compensating for a misspecification elsewhere?
- What do scaling laws license predicting, and where should I expect them
  to break?
- If the optimizer is part of the inductive bias, is the distinction
  between model and training procedure worth keeping?

## Notes

## Resources
