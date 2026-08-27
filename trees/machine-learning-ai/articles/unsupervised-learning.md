# Unsupervised Learning

[← Machine Learning / AI](../index.md) · `ML_UNSUP`

Finding structure without being told what structure to find. The
algorithms are straightforward; the hard part is evaluation, because
without a target there is no obvious way to say whether structure was
discovered or imposed. A clustering always returns clusters. Modern
practice has largely folded this area into representation learning, where
the question becomes what makes a representation good independent of the
task it will later serve — and whether self-supervised objectives are
really unsupervised or just supervision harvested from the data's own
structure.

## Open questions

- Without labels, what makes a found structure real rather than imposed?
  Is there a non-circular way to evaluate a clustering?
- Is dimensionality reduction finding genuine low-dimensional structure,
  or projecting whatever's there onto a comfortable picture?
- What makes a representation good independently of the downstream task?
- Do density estimates in high dimensions mean what they appear to mean?
- Is self-supervised learning unsupervised, or supervised learning with
  free labels — and does the distinction change anything?
- When a method finds structure that matches human categories, is that
  evidence the structure is real or that the data was human-curated?

## Notes

## Resources
