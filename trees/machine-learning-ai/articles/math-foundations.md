# Math Foundations

[← Machine Learning / AI](../index.md) · `ML_MATH`

Linear algebra, calculus, and probability, which between them describe
what a model is (a parametrized function), how it is fit (following
gradients), and what its outputs mean (distributions over things that
might happen). The practical question is which parts change what you'd
build versus which are notation for reasoning you could do anyway. The
uncomfortable part is that classical statistical theory — capacity
bounds, the bias-variance tradeoff — makes predictions about
overparametrized models that modern practice routinely violates without
apparent penalty.

## Open questions

- Which pieces of the math actually change a design decision, and which
  are vocabulary for intuitions I already have?
- Is probability in ML a claim about the world, or bookkeeping for
  uncertainty inside the model?
- Why do methods designed under convexity assumptions work at all in a
  non-convex setting?
- What does high-dimensional geometry do to intuitions built in two or
  three dimensions — and which of my intuitions are the unsafe ones?
- How much do classical generalization bounds still say about models that
  interpolate their training data and generalize anyway?
- Where does a probabilistic framing of a problem buy something a purely
  optimization framing doesn't?

## Notes

## Resources
