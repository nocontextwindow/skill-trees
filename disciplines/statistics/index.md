# Statistics

Probability, inference, and how to actually trust (or distrust) a
conclusion drawn from data.

The structure below runs from what probability *is*, through the two rival
inferential frameworks, to the modelling methods built on top of them.

## Tree

```mermaid
flowchart TD
    subgraph Foundations
        STAT_PROB[Probability Theory]
        STAT_DESC[Descriptive Statistics]
        STAT_PROB --> STAT_DESC
    end

    subgraph Inference
        STAT_INFER[Statistical Inference<br/>hypothesis testing, confidence intervals]
        STAT_BAYES[Bayesian Statistics]
        STAT_EXPDESIGN[Experimental Design & Causal Inference]
        STAT_INFER --> STAT_BAYES --> STAT_EXPDESIGN
    end

    subgraph Modeling
        STAT_REGRESS[Regression & Modeling]
        STAT_MULTI[Multivariate & Time Series Methods]
        STAT_REGRESS --> STAT_MULTI
    end

    STAT_DESC --> STAT_INFER
    STAT_EXPDESIGN --> STAT_REGRESS

    classDef crosslink stroke-dasharray: 5 5
    STAT_MATH(("→ Mathematics")):::crosslink
    STAT_EP(("→ Epistemology<br/>Bayesian epistemology")):::crosslink
    STAT_ML(("→ ML/AI")):::crosslink
    STAT_ECON(("→ Economics")):::crosslink
    STAT_PROB --> STAT_MATH
    STAT_BAYES --> STAT_EP
    STAT_MULTI --> STAT_ML
    STAT_MULTI --> STAT_ECON
```

## Related Trees

- [Mathematics](../math/index.md) — `STAT_PROB` builds on `MATH_LINALG` and
  `MATH_REALANAL`.
- [Epistemology](../../self/epistemology/index.md) — `STAT_BAYES` is `EP_BAYES` in
  practice.
- [Machine Learning / AI](../machine-learning-ai/index.md) — `STAT_MULTI` feeds
  `ML_MATH` and `ML_EVAL`.
- [Economics](../economics/index.md) — `STAT_MULTI` underlies `ECON_MACRO`
  modeling.
- [Biology](../biology/index.md) — `STAT_EXPDESIGN` underlies `BIO_EVO`
  (population genetics) and experimental biology generally.

See also: [Book List](../../BOOKLIST.md).
