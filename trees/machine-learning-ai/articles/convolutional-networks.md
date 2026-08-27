# Convolutional Networks

[← Machine Learning / AI](../index.md) · `ML_CNN`

Architectures that build assumptions about images — locality, weight
sharing, approximate translation equivariance — directly into the model.
For a long time that prior was the whole story of computer vision;
attention-based architectures with enough data have since matched or
beaten it, which reframes the prior as a data-efficiency device rather
than a structural truth about images. The field's other standing
embarrassment is adversarial examples: imperceptible perturbations that
flip a confident prediction, which suggest these systems key on
statistics of the training distribution rather than on objects.

## Open questions

- Is the convolutional prior a genuine fact about images, or a
  data-efficiency crutch that scale makes unnecessary?
- What do adversarial examples reveal — a defect of the models, of the
  training distribution, or of what "recognition" was taken to mean?
- Do these systems perceive objects, or exploit shortcut features that
  happen to correlate within the benchmark?
- How much of vision progress is architecture versus data scale and
  augmentation? Has anyone cleanly separated them?
- What does an out-of-distribution failure tell you about the failures
  you can't see?
- Where does the analogy between these models and biological vision do
  real explanatory work, and where is it decoration?

## Notes

## Resources
