# Machine Learning / AI — Frontier

[← Back to index](./index.md)

---

## Reinforcement Learning (`ML_RL`)

Learning by acting in an environment and getting reward signals rather than
labeled examples: the agent must balance exploration (trying uncertain
actions to learn more) against exploitation (taking the best known
action), formalized through Markov decision processes, value functions, and
policy gradients. Deep RL combines this framework with neural function
approximators (DQN for Atari, AlphaGo/AlphaZero's combination of
self-play and Monte Carlo tree search), but the field is notorious for
brittle reward specification — an agent will reliably find and exploit any
gap between the reward function you wrote and the behavior you actually
wanted, which is a direct preview of the alignment problem in `ML_ALIGN`.
RL from human feedback (RLHF) is also the specific technique that turned
raw language models into usable chat assistants.

**Status:** [ ]

**Resources:**
- Richard Sutton & Andrew Barto, *Reinforcement Learning: An Introduction* (free online)
- David Silver's UCL Course on Reinforcement Learning (lecture videos)
- OpenAI's "Spinning Up in Deep RL" (free online, code-first)

---

## Generative Models: GANs / Diffusion / LLMs (`ML_GEN`)

Models that learn to produce new samples from a data distribution rather
than just classify or predict. GANs (Goodfellow et al.) pit a generator
against a discriminator in an adversarial game; diffusion models instead
learn to reverse a gradual noising process, and their math is drawn
directly from nonequilibrium statistical mechanics — the forward process
is literally a physical diffusion process, and training amounts to
learning the score function (gradient of the log-density), tying this node
concretely back to `PH_THERMO`. Large language models are generative
models over token sequences, trained by next-token prediction at scale;
their emergent capabilities as scale increases remain an active empirical
puzzle without full theoretical explanation.

**Status:** [ ]

**Resources:**
- Ian Goodfellow et al., "Generative Adversarial Networks" (2014)
- Jonathan Ho et al., "Denoising Diffusion Probabilistic Models" (2020)
- Yang Song's blog, "Generative Modeling by Estimating Gradients of the Data Distribution" (score-based/diffusion intuition)

---

## Interpretability & Explainability (`ML_INTERP`)

The project of understanding what's actually happening inside a trained
model rather than treating it as an opaque black box. Classical
explainability tools (feature importance, SHAP, LIME, saliency maps) give
post-hoc, often approximate explanations of individual predictions;
mechanistic interpretability instead tries to reverse-engineer the actual
algorithm a network has learned — Anthropic's work on transformer circuits
and "superposition" (models representing more features than they have
neurons, packed in overlapping directions) is the current frontier of that
more ambitious program. This matters practically for debugging and
trusting models, and matters for alignment because you can't verify a
model is safe by behavior alone if it can behave well on the exact
distribution you happened to test.

**Status:** [ ]

**Resources:**
- Christoph Molnar, *Interpretable Machine Learning* (free online)
- Anthropic, "A Mathematical Framework for Transformer Circuits" (Elhage et al., transformer-circuits.pub)
- Chris Olah et al., "Zoom In: An Introduction to Circuits" (Distill)

---

## AI Alignment & Safety (`ML_ALIGN`)

The problem of ensuring increasingly capable AI systems reliably do what
their operators (or humanity broadly) actually want, which turns out to be
hard even in principle: specifying human values precisely enough to
optimize for is itself an open problem (Goodhart's law — any proxy metric
optimized hard enough stops tracking the thing it was a proxy for), and
more capable optimizers are better at finding unintended shortcuts to a
misspecified goal. The field splits roughly into near-term/empirical work
(robustness, RLHF, red-teaming, evaluations) and longer-horizon theoretical
concerns (deceptive alignment, scalable oversight of systems smarter than
their overseers, corrigibility). This is the node where the tree's applied
ethics content (`PP` ethics trees) becomes concretely load-bearing rather
than abstract.

**Status:** [ ]

**Resources:**
- Brian Christian, *The Alignment Problem*
- Stuart Russell, *Human Compatible*
- Amodei et al., "Concrete Problems in AI Safety" (2016)
- Anthropic's "Core Views on AI Safety" (blog post)
