# Machine Learning / AI

From the math and programming groundwork through classical ML, deep
learning, and the frontier topics (generative models, alignment).

## Skill Tree

```mermaid
flowchart TD
    subgraph Foundations
        ML_MATH[Math Foundations<br/>Linear Algebra / Calculus / Probability & Stats]
        ML_PROG[Programming Foundations<br/>Python / Data Structures & Algorithms]
        ML_MATH --> ML_PROG
    end

    subgraph "Core ML"
        ML_SUP[Supervised Learning]
        ML_UNSUP[Unsupervised Learning]
        ML_EVAL[Model Evaluation & Validation]
        ML_SUP --> ML_UNSUP --> ML_EVAL
    end

    subgraph "Deep Learning"
        ML_NN[Neural Network Fundamentals]
        ML_OPT[Optimization for Deep Learning]
        ML_CNN[Convolutional Networks<br/>Computer Vision]
        ML_SEQ[Sequence Models & Transformers<br/>NLP]
        ML_NN --> ML_OPT --> ML_CNN --> ML_SEQ
    end

    subgraph Frontier
        ML_RL[Reinforcement Learning]
        ML_GEN[Generative Models<br/>GANs / Diffusion / LLMs]
        ML_INTERP[Interpretability & Explainability]
        ML_ALIGN[AI Alignment & Safety]
        ML_RL --> ML_GEN --> ML_INTERP --> ML_ALIGN
    end

    ML_PROG --> ML_SUP
    ML_EVAL --> ML_NN
    ML_SEQ --> ML_RL

    classDef crosslink stroke-dasharray: 5 5
    ML_EP(("→ Epistemology<br/>induction, Bayesian reasoning")):::crosslink
    ML_PH(("→ Physics<br/>statistical mechanics")):::crosslink
    ML_PP(("→ Personal Philosophy<br/>ethics")):::crosslink
    ML_EVAL --> ML_EP
    ML_GEN --> ML_PH
    ML_ALIGN --> ML_PP
```

## Nodes

| ID | Concept | Depends on | Status | Resources / Notes |
|---|---|---|---|---|
| ML_MATH | Math Foundations (linear algebra, calculus, probability & stats) | — | [ ] | |
| ML_PROG | Programming Foundations (Python, data structures & algorithms) | ML_MATH | [ ] | |
| ML_SUP | Supervised Learning | ML_PROG | [ ] | |
| ML_UNSUP | Unsupervised Learning | ML_SUP | [ ] | |
| ML_EVAL | Model Evaluation & Validation | ML_UNSUP | [ ] | |
| ML_NN | Neural Network Fundamentals | ML_EVAL | [ ] | |
| ML_OPT | Optimization for Deep Learning | ML_NN | [ ] | |
| ML_CNN | Convolutional Networks / Computer Vision | ML_OPT | [ ] | |
| ML_SEQ | Sequence Models & Transformers / NLP | ML_CNN | [ ] | |
| ML_RL | Reinforcement Learning | ML_SEQ | [ ] | |
| ML_GEN | Generative Models (GANs, Diffusion, LLMs) | ML_RL | [ ] | |
| ML_INTERP | Interpretability & Explainability | ML_GEN | [ ] | |
| ML_ALIGN | AI Alignment & Safety | ML_INTERP | [ ] | |

## Related Trees

- [Epistemology](epistemology.md) — `ML_EVAL` is applied Bayesian
  epistemology (`EP_BAYES`); the generalization problem in ML is the
  problem of induction (`EP_SCI`).
- [Physics](physics.md) — `ML_GEN` (especially diffusion models) borrows
  directly from statistical mechanics (`PH_THERMO`).
- [Statistics](statistics.md) — `ML_MATH` and `ML_EVAL` lean heavily on
  `STAT_INFER` and `STAT_BAYES`.
- [Personal Philosophy](personal-philosophy.md) — `ML_ALIGN` is where
  applied ethics meets real systems.
