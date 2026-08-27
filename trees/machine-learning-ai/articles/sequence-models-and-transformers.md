# Sequence Models & Transformers

[← Machine Learning / AI](../index.md) · `ML_SEQ`

Models over ordered data, and the attention-based architecture that
displaced recurrence for most of it. Part of that displacement is an
inductive-bias argument (direct access to any position instead of a
compressed running state) and part is straightforwardly about hardware —
attention parallelizes and recurrence doesn't. The larger question the
area forced open is what next-token prediction at scale actually
produces: the capability curve keeps outrunning the accounts of why, and
the debate over whether it constitutes understanding has struggled to
propose a test that would settle it.

## Open questions

- What does attention compute that recurrence couldn't — is the win about
  inductive bias or about parallel hardware?
- Does next-token prediction at scale yield understanding, a very good
  surface model, or a distinction with no testable difference?
- What are the real limits of in-context learning relative to learning in
  the weights?
- How much apparent reasoning survives rephrasing a problem outside the
  training distribution — and how would you construct that test fairly?
- What is longer context actually buying, and where does more of it stop
  helping?
- Which observed capabilities are emergent in any strong sense, and which
  are artifacts of how the metric was thresholded?

## Notes

## Resources
