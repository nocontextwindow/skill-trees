# Epistemology

The theory of knowledge: what knowledge is, where it comes from, when
belief is justified, and how much confidence anything deserves.

The structure below runs from the analysis of knowledge, through the
debates that break it, to the theories built to repair it and the places
where the whole question gets applied — science, other people, and
decisions made under uncertainty.

## Tree

```mermaid
flowchart TD
    subgraph Foundations
        EP_INTRO[What Is Knowledge?<br/>Justified True Belief]
        EP_LANG[Philosophy of Language]
        EP_SOURCES[Sources of Knowledge<br/>Perception / Reason / Testimony / Memory]
        EP_INTRO --> EP_LANG --> EP_SOURCES
    end

    subgraph "Core Debates"
        EP_GETTIER[The Gettier Problem]
        EP_RATEMP[Rationalism vs Empiricism]
        EP_SKEPT[Skepticism]
        EP_GETTIER --> EP_RATEMP --> EP_SKEPT
    end

    subgraph "Theories of Justification"
        EP_JUST[Theories of Justification]
        EP_FOUND[Foundationalism]
        EP_COH[Coherentism]
        EP_REL[Reliabilism]
        EP_JUST --> EP_FOUND --> EP_COH --> EP_REL
    end

    subgraph "Special Topics"
        EP_SCI[Philosophy of Science<br/>Induction / Falsifiability]
        EP_SOCIAL[Social Epistemology<br/>Testimony & Disagreement]
        EP_BAYES[Formal / Bayesian Epistemology]
        EP_COMPLEX[Decision-Making Under Complexity]
        EP_NAT[Naturalized Epistemology<br/>building accurate world models]
        EP_SCI --> EP_SOCIAL --> EP_BAYES --> EP_COMPLEX --> EP_NAT
    end

    EP_SOURCES --> EP_GETTIER
    EP_SKEPT --> EP_JUST
    EP_REL --> EP_SCI

    classDef crosslink stroke-dasharray: 5 5
    EP_PP(("→ Personal Philosophy<br/>ethics of belief")):::crosslink
    EP_PH(("→ Physics<br/>philosophy of science")):::crosslink
    EP_ML(("→ ML/AI<br/>induction, Bayesian methods")):::crosslink
    EP_INTRO --> EP_PP
    EP_SCI --> EP_PH
    EP_BAYES --> EP_ML
```

## Articles

**Foundations**
- [What Is Knowledge?](articles/what-is-knowledge.md) — `EP_INTRO`
- [Philosophy of Language](articles/philosophy-of-language.md) — `EP_LANG`
- [Sources of Knowledge](articles/sources-of-knowledge.md) — `EP_SOURCES`

**Core Debates**
- [The Gettier Problem](articles/the-gettier-problem.md) — `EP_GETTIER`
- [Rationalism vs Empiricism](articles/rationalism-vs-empiricism.md) — `EP_RATEMP`
- [Skepticism](articles/skepticism.md) — `EP_SKEPT`

**Theories of Justification**
- [Theories of Justification](articles/theories-of-justification.md) — `EP_JUST`
- [Foundationalism](articles/foundationalism.md) — `EP_FOUND`
- [Coherentism](articles/coherentism.md) — `EP_COH`
- [Reliabilism](articles/reliabilism.md) — `EP_REL`

**Special Topics**
- [Philosophy of Science](articles/philosophy-of-science.md) — `EP_SCI`
- [Social Epistemology](articles/social-epistemology.md) — `EP_SOCIAL`
- [Formal / Bayesian Epistemology](articles/formal-bayesian-epistemology.md) — `EP_BAYES`
- [Decision-Making Under Complexity](articles/decision-making-under-complexity.md) — `EP_COMPLEX`
- [Naturalized Epistemology](articles/naturalized-epistemology.md) — `EP_NAT`

## Related Trees

- [Personal Philosophy](../personal-philosophy/index.md) — `EP_INTRO`
  underlies the whole worldview-building project.
- [Physics](../physics/index.md) — `EP_SCI` (induction/falsifiability) is the
  philosophical backbone of `PH_PHILO` (interpretations of QM).
- [Machine Learning / AI](../machine-learning-ai/index.md) — `EP_BAYES` maps
  directly onto `ML_EVAL`; the induction problem in `EP_SCI` is exactly the
  generalization problem in ML.

See also: [Book List](../../BOOKLIST.md).
