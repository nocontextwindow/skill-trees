# Model Evaluation & Validation

[← Machine Learning / AI](../index.md) · `ML_EVAL`

Where most real mistakes actually happen. Cross-validation, held-out
sets, and metric selection look like procedure, but each carries a
judgment: which errors cost more, how much leakage is tolerable, whether
the validation distribution resembles the deployment one. A further
problem is collective: a benchmark that a whole field has iterated
against thousands of times is no longer held out in any meaningful sense,
so measured progress and real progress can diverge for years without
anyone noticing.

## Open questions

- How much benchmark progress is the field collectively overfitting to a
  test set it has now effectively seen?
- Which metric is right when the two error types have incommensurable
  costs, and who is entitled to decide?
- How do you detect leakage you didn't think to look for?
- What does a validation score predict about behavior under distribution
  shift — anything at all?
- When is offline evaluation trustworthy enough to skip an online test,
  and is that reasoning ever actually safe?
- If evaluation is where value judgments enter a technical pipeline,
  should the metric be argued for in the way a policy would be?

## Notes

## Resources
