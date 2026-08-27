# Bayesian Statistics

[← Statistics](../index.md) · `STAT_BAYES`

Treating parameters as uncertain quantities with distributions, and
updating those distributions with evidence. Bayesian methods give you
things frequentism structurally cannot — a direct probability statement
about a hypothesis, coherent handling of nested and hierarchical structure,
a principled way to pool information across groups — at the cost of having
to state a prior, which is both the honest part and the attackable part.
The old objection that priors are subjective has largely given way to a
more practical one: with modern MCMC and variational machinery you can fit
almost anything, which means you can also fit models you have no business
trusting, and diagnosing whether a posterior is real or an artifact of
sampler behaviour is a genuine skill. The frequentist/Bayesian war has
mostly ended in a truce nobody quite articulated.

## Open questions

- Where does a prior stop being a defensible encoding of what's known and
  start being the conclusion smuggled into the setup?
- Is a "non-informative" prior a real thing, or just an informative prior
  nobody audited?
- When does Bayesian machinery earn its extra cost over a simpler
  frequentist procedure that would answer the same practical question?
- How do I tell a posterior that reflects the data from one that reflects
  the sampler or the model's parameterization?
- If Bayesian updating is the normative account of belief revision, why do
  competent people so rarely use it explicitly outside of statistics?
- What happens to the whole framework when the true model is not in the
  hypothesis space — which it never is?

## Notes

## Resources
