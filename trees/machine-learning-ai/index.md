# Machine Learning / AI

The groundwork, the classical methods, deep learning, and the frontier —
built as the field's own dependency order rather than as a tour of
whatever is currently loud. Theory has trailed practice here for a
decade, so a lot of the real content is knowing which explanations are
established and which are stories told after the fact.

Specific systems, papers, and current arguments belong as open questions
inside the relevant article, not as branches of their own.

## Tree

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

## Articles

**Foundations**
- [Math Foundations](articles/math-foundations.md) — `ML_MATH`
- [Programming Foundations](articles/programming-foundations.md) — `ML_PROG`

**Core ML**
- [Supervised Learning](articles/supervised-learning.md) — `ML_SUP`
- [Unsupervised Learning](articles/unsupervised-learning.md) — `ML_UNSUP`
- [Model Evaluation & Validation](articles/model-evaluation-and-validation.md) — `ML_EVAL`

**Deep Learning**
- [Neural Network Fundamentals](articles/neural-network-fundamentals.md) — `ML_NN`
- [Optimization for Deep Learning](articles/optimization-for-deep-learning.md) — `ML_OPT`
- [Convolutional Networks](articles/convolutional-networks.md) — `ML_CNN`
- [Sequence Models & Transformers](articles/sequence-models-and-transformers.md) — `ML_SEQ`

**Frontier**
- [Reinforcement Learning](articles/reinforcement-learning.md) — `ML_RL`
- [Generative Models](articles/generative-models.md) — `ML_GEN`
- [Interpretability & Explainability](articles/interpretability-and-explainability.md) — `ML_INTERP`
- [AI Alignment & Safety](articles/ai-alignment-and-safety.md) — `ML_ALIGN`

## Related Trees

- [Epistemology](../epistemology/index.md) — generalization is the problem
  of induction, and model evaluation is applied Bayesian reasoning.
- [Statistics](../statistics/index.md) — the inference and estimation
  theory underneath all of it.
- [Physics](../physics/index.md) — statistical mechanics, which diffusion
  models borrow from directly.
- [Personal Philosophy](../personal-philosophy/index.md) — where alignment
  stops being a technical question and becomes an ethical one.

See also: [Book List](../../BOOKLIST.md).
