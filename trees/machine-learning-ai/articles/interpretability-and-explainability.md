# Interpretability & Explainability

[← Machine Learning / AI](../index.md) · `ML_INTERP`

Two enterprises usually named together and often confused. Post-hoc
explanation produces something a human finds satisfying about a
particular output; mechanistic interpretability tries to describe the
computation the network actually performs. The first is easy to do badly
and hard to falsify — a plausible explanation with no causal relation to
the model's processing is worse than none, since it manufactures
unwarranted trust. The second is genuinely hard, and phenomena like
superposition suggest that the unit of analysis practitioners reach for
(a feature, a neuron) may not be the right one.

## Open questions

- What is an explanation for — auditing, debugging, trust, or legal cover?
  These want different things and are constantly conflated.
- How do you distinguish a faithful explanation from a plausible one with
  no causal relation to the computation?
- Does a model's stated reason for an output have any privileged relation
  to how that output was produced?
- Are features the right unit of analysis, or is superposition evidence
  that the unit is wrong?
- If a system were fully understood mechanistically, would that change
  any decision anyone actually makes about deploying it?
- Is there an unavoidable tradeoff between interpretability and
  capability, or is that assumption doing convenient work?

## Notes

## Resources
