# Mathematics

The general-purpose toolkit that everything else — physics, statistics, ML,
engineering — draws on, and a set of questions about what that toolkit
actually is.

The arrows below are order of dependence. The questions inside each article
mostly are not about technique; they're about what the subject is doing and
what its choices commit you to.

## Tree

```mermaid
flowchart TD
    subgraph Foundations
        MATH_ALGEBRA[Algebra & Precalculus]
        MATH_CALC[Calculus<br/>single & multivariable]
        MATH_LINALG[Linear Algebra]
        MATH_DIFFEQ[Differential Equations]
        MATH_ALGEBRA --> MATH_CALC --> MATH_LINALG --> MATH_DIFFEQ
    end

    subgraph "Proof & Structure"
        MATH_DISCRETE[Discrete Math & Proof]
        MATH_ABSTRACT[Abstract Algebra]
        MATH_DISCRETE --> MATH_ABSTRACT
    end

    subgraph Analysis
        MATH_REALANAL[Real Analysis]
        MATH_TOPOLOGY[Topology]
        MATH_REALANAL --> MATH_TOPOLOGY
    end

    MATH_CALC --> MATH_DISCRETE
    MATH_CALC --> MATH_REALANAL

    classDef crosslink stroke-dasharray: 5 5
    MATH_PH(("→ Physics")):::crosslink
    MATH_STAT(("→ Statistics")):::crosslink
    MATH_ML(("→ ML/AI")):::crosslink
    MATH_LINALG --> MATH_PH
    MATH_LINALG --> MATH_STAT
    MATH_LINALG --> MATH_ML
```

## Articles

**Foundations**
- [Algebra & Precalculus](articles/algebra-and-precalculus.md) — `MATH_ALGEBRA`
- [Calculus](articles/calculus.md) — `MATH_CALC`
- [Linear Algebra](articles/linear-algebra.md) — `MATH_LINALG`
- [Differential Equations](articles/differential-equations.md) — `MATH_DIFFEQ`

**Proof & Structure**
- [Discrete Math & Proof](articles/discrete-math-and-proof.md) — `MATH_DISCRETE`
- [Abstract Algebra](articles/abstract-algebra.md) — `MATH_ABSTRACT`

**Analysis**
- [Real Analysis](articles/real-analysis.md) — `MATH_REALANAL`
- [Topology](articles/topology.md) — `MATH_TOPOLOGY`

## Related Trees

- [Physics](../physics/index.md) — `MATH_LINALG` and `MATH_DIFFEQ` are
  prerequisites for `PH_CLASS` onward.
- [Statistics](../statistics/index.md) — `MATH_LINALG` and `MATH_REALANAL`
  underlie `STAT_PROB`.
- [Machine Learning / AI](../machine-learning-ai/index.md) — `MATH_LINALG` is
  `ML_MATH`'s core.
- [Civil Engineering](../civil-engineering/index.md) and
  [Materials Science](../materials-science/index.md) both build directly on
  `MATH_DIFFEQ`.

See also: [Book List](../../BOOKLIST.md).
