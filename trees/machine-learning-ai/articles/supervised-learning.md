# Supervised Learning

[← Machine Learning / AI](../index.md) · `ML_SUP`

Fitting a function from inputs to labels, which covers the large majority
of machine learning that does economically useful work. The algorithms
are largely commoditized; the difficulty has migrated to the data — what
the labels mean, who produced them, whether the training distribution
resembles the deployment one. The bias-variance framing organizes a lot
of thinking here, and the choice of a simpler model over a more accurate
one is a real engineering decision rather than a concession.

## Open questions

- How much of a model's performance is the algorithm and how much is the
  dataset? What experiment cleanly separates them?
- What does a label represent when annotators disagree — is there a
  ground truth, or a negotiated one?
- When is a simple inspectable model preferable at a measurable accuracy
  cost, and how is that tradeoff argued rather than asserted?
- Where does the i.i.d. assumption break in real deployments, and what
  breaks with it?
- Do hand-engineered features ever beat learned representations, and what
  does it mean about the problem when they do?
- What is the honest way to report performance on a problem where the
  base rate is extreme?

## Notes

## Resources
