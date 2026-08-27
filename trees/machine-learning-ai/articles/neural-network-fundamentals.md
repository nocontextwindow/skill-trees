# Neural Network Fundamentals

[← Machine Learning / AI](../index.md) · `ML_NN`

Composition of simple parametrized functions, fit end-to-end by
backpropagating error. The mechanics are simple enough to derive on a
page; the explanation of why they work is not, and theory has trailed
practice by years in almost every case. Universal approximation results
say a shallow network could represent anything, which conspicuously fails
to explain why depth helps so much in practice — suggesting the real
story is about optimization and inductive bias rather than expressive
capacity.

## Open questions

- Why does depth help beyond what approximation theorems say? Is the
  answer about expressivity or about what's findable by gradient descent?
- What is a learned representation — a compression, a feature set, or an
  artifact of the particular training path taken?
- How much of a network's behavior is architecture versus data versus
  initialization, and can that be measured rather than argued?
- Is there any account of generalization in overparametrized networks
  that isn't retrospective?
- Where is a neural network the wrong tool, and how would I recognize
  that before spending the compute?
- Which architectural choices encode a real assumption about the data,
  and which are folklore that survived because nobody re-tested it?

## Notes

## Resources
