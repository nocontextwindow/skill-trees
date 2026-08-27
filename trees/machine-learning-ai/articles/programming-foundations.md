# Programming Foundations

[← Machine Learning / AI](../index.md) · `ML_PROG`

Most of the work in a machine learning project is not modeling: it is
data movement, memory, numerical stability, and making experiments
reproducible enough to learn from. Frameworks abstract a great deal of
this, which is why the failures that matter are the ones where the
abstraction leaks — a silent dtype cast, a data loader that reorders,
nondeterminism in the hardware. The discipline question is which software
engineering practices transfer to code whose output is stochastic and
whose correctness has no simple oracle.

## Open questions

- Where does the framework abstraction leak, and which leaks do I need to
  understand rather than route around?
- How much of a given performance problem is algorithmic versus memory
  layout and data movement?
- When a model trains but underperforms, what's the ordered list of
  places to look — code, data, objective, or evaluation?
- Which engineering practices (tests, types, review) transfer to ML code,
  and which fail because there's no deterministic expected output?
- What does reproducibility mean when nondeterminism lives in the
  hardware, and how much is it worth paying for?
- How much abstraction is right for research code that will be rewritten
  versus code that will be deployed?

## Notes

## Resources
