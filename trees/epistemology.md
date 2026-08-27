# Epistemology

The theory of knowledge: what knowledge is, where it comes from, when belief
is justified, and how confident we should be in anything.

## Skill Tree

```mermaid
flowchart TD
    subgraph Foundations
        EP_INTRO[What Is Knowledge?<br/>Justified True Belief]
        EP_SOURCES[Sources of Knowledge<br/>Perception / Reason / Testimony / Memory]
    end

    subgraph "Core Debates"
        EP_GETTIER[The Gettier Problem]
        EP_RATEMP[Rationalism vs Empiricism]
        EP_SKEPT[Skepticism]
    end

    subgraph "Theories of Justification"
        EP_JUST[Theories of Justification]
        EP_FOUND[Foundationalism]
        EP_COH[Coherentism]
        EP_REL[Reliabilism]
    end

    subgraph "Special Topics"
        EP_SCI[Philosophy of Science<br/>Induction / Falsifiability]
        EP_SOCIAL[Social Epistemology<br/>Testimony & Disagreement]
        EP_BAYES[Formal / Bayesian Epistemology]
        EP_NAT[Naturalized Epistemology]
    end

    EP_CAPSTONE[["Capstone: Audit Your Own Beliefs"]]

    EP_INTRO --> EP_SOURCES
    EP_INTRO --> EP_GETTIER
    EP_SOURCES --> EP_RATEMP
    EP_GETTIER --> EP_SKEPT
    EP_GETTIER --> EP_JUST

    EP_JUST --> EP_FOUND
    EP_JUST --> EP_COH
    EP_JUST --> EP_REL

    EP_RATEMP --> EP_SCI
    EP_JUST --> EP_SOCIAL
    EP_JUST --> EP_BAYES
    EP_SCI --> EP_NAT

    EP_SOCIAL --> EP_CAPSTONE
    EP_BAYES --> EP_CAPSTONE
    EP_NAT --> EP_CAPSTONE
    EP_SKEPT --> EP_CAPSTONE

    classDef crosslink stroke-dasharray: 5 5
    EP_PP(("→ Personal Philosophy<br/>(ethics of belief)")):::crosslink
    EP_PH(("→ Physics<br/>(philosophy of science)")):::crosslink
    EP_ML(("→ ML/AI<br/>(induction, Bayesian methods)")):::crosslink
    EP_INTRO --> EP_PP
    EP_SCI --> EP_PH
    EP_BAYES --> EP_ML
```

## Nodes

| ID | Concept | Depends on | Status | Resources / Notes |
|---|---|---|---|---|
| EP_INTRO | What Is Knowledge? (JTB) | — | [ ] | |
| EP_SOURCES | Sources of Knowledge | EP_INTRO | [ ] | |
| EP_GETTIER | The Gettier Problem | EP_INTRO | [ ] | |
| EP_RATEMP | Rationalism vs Empiricism | EP_SOURCES | [ ] | |
| EP_SKEPT | Skepticism | EP_GETTIER | [ ] | |
| EP_JUST | Theories of Justification | EP_GETTIER | [ ] | |
| EP_FOUND | Foundationalism | EP_JUST | [ ] | |
| EP_COH | Coherentism | EP_JUST | [ ] | |
| EP_REL | Reliabilism | EP_JUST | [ ] | |
| EP_SCI | Philosophy of Science (induction, falsifiability) | EP_RATEMP | [ ] | |
| EP_SOCIAL | Social Epistemology (testimony, disagreement) | EP_JUST | [ ] | |
| EP_BAYES | Formal / Bayesian Epistemology | EP_JUST | [ ] | |
| EP_NAT | Naturalized Epistemology | EP_SCI | [ ] | |
| EP_CAPSTONE | **Capstone:** Audit Your Own Beliefs | EP_SOCIAL, EP_BAYES, EP_NAT, EP_SKEPT | [ ] | Actually list out beliefs and check justification |

## Related Trees

- [Personal Philosophy](personal-philosophy.md) — `EP_INTRO` underlies the
  whole worldview-building project; do it alongside `PP_LOGIC`.
- [Physics](physics.md) — `EP_SCI` (induction/falsifiability) is the
  philosophical backbone of `PH_PHILO` (interpretations of QM).
- [Machine Learning / AI](machine-learning-ai.md) — `EP_BAYES` maps directly
  onto `ML_EVAL` and the probabilistic reasoning behind most of ML; the
  induction problem in `EP_SCI` is exactly the generalization problem in ML.
