# Statistics — Inference

[← Back to index](./index.md)

---

## Statistical Inference (`STAT_INFER`)

The frequentist toolkit for drawing conclusions about a population from a
sample: point estimation, confidence intervals, and hypothesis testing
(null and alternative hypotheses, p-values, Type I/II errors, statistical
power). This is also where the field's most persistent public-facing
problem lives — the p-value is one of the most misunderstood numbers in
science, routinely misread as "the probability the null hypothesis is
true" when it's actually "the probability of data this extreme *given*
the null is true." The replication crisis in psychology and biomedicine is
substantially a story about p-hacking, underpowered studies, and
publication bias interacting with this misunderstanding, which makes this
node worth learning skeptically rather than mechanically.

**Status:** [ ]

**Resources:**
- David Freedman, Robert Pisani & Roger Purves, *Statistics*
- Regina Nuzzo, "Scientific method: Statistical errors" (*Nature*, 2014)
- Andrew Gelman & Jennifer Hill, *Data Analysis Using Regression and Multilevel/Hierarchical Models*

---

## Bayesian Statistics (`STAT_BAYES`)

An entirely different philosophy of inference: instead of asking "how
likely is this data given a fixed but unknown parameter," Bayesian
statistics treats the parameter itself as uncertain, assigns it a prior
distribution, and updates that prior into a posterior using observed data
via Bayes' theorem. This lets you make direct probability statements about
hypotheses ("there's an 80% chance the effect is positive") that frequentist
confidence intervals technically don't allow, at the cost of having to
defend a choice of prior — the traditional point of contention between the
two camps. Modern computational methods (Markov Chain Monte Carlo, and
tools like Stan) have made Bayesian methods practical for models far too
complex for closed-form solutions, which is a big part of why the field has
seen a real resurgence since the 1990s.

**Status:** [ ]

**Resources:**
- Richard McElreath, *Statistical Rethinking*
- John Kruschke, *Doing Bayesian Data Analysis*
- E.T. Jaynes, *Probability Theory: The Logic of Science*

---

## Experimental Design & Causal Inference (`STAT_EXPDESIGN`)

How to actually establish that X causes Y rather than merely correlates
with it. Randomized controlled trials are the gold standard because
randomization breaks the link between treatment assignment and any
confounding variable, known or unknown — but most real-world data isn't
experimental, so this field also covers the quasi-experimental toolkit for
observational data: instrumental variables, difference-in-differences,
regression discontinuity, and propensity score matching. Judea Pearl's
causal graph framework (DAGs, the do-calculus) gives a rigorous language
for reasoning about confounders, colliders, and mediators, and for stating
precisely when a causal claim from observational data is even in principle
identifiable. This is one of the highest-leverage subfields in all of
statistics for anyone doing applied work in economics, medicine, or policy.

**Status:** [ ]

**Resources:**
- Judea Pearl, Madelyn Glymour & Nicholas Jewell, *Causal Inference in Statistics: A Primer*
- Joshua Angrist & Jörn-Steffen Pischke, *Mostly Harmless Econometrics*
- Judea Pearl & Dana Mackenzie, *The Book of Why*
