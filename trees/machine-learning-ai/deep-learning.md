# Machine Learning / AI — Deep Learning

[← Back to index](./index.md)

---

## Neural Network Fundamentals (`ML_NN`)

Stacking layers of learned linear transformations and fixed nonlinearities
(ReLU, sigmoid, tanh) gives a universal function approximator, trained by
backpropagation — the chain rule applied systematically to compute how the
loss depends on every weight. The universal approximation theorem
guarantees a wide-enough shallow network can approximate any continuous
function, but says nothing about how easy that function is to actually
learn via gradient descent, which is the practical reason depth (not just
width) turned out to matter so much. Understanding backprop by hand (not
just calling `.backward()`) is worth the effort once, since it demystifies
almost every training pathology you'll hit later.

**Status:** [ ]

**Resources:**
- Ian Goodfellow, Yoshua Bengio & Aaron Courville, *Deep Learning* (free online)
- Michael Nielsen, *Neural Networks and Deep Learning* (free online, excellent for backprop intuition)
- Andrej Karpathy's "Neural Networks: Zero to Hero" video series

---

## Optimization for Deep Learning (`ML_OPT`)

Training a neural network is a high-dimensional, non-convex optimization
problem, and the practical toolkit (SGD, momentum, Adam and its variants,
learning-rate schedules, batch normalization, weight initialization
schemes, gradient clipping) exists largely to make that optimization
tractable and stable. Surprisingly, local minima turn out not to be the
main obstacle in high dimensions — saddle points and ill-conditioned loss
landscapes are the bigger practical enemies. Understanding vanishing and
exploding gradients, and why architectural tricks like residual
connections and normalization layers fix them, is essential before going
deeper into any specific architecture.

**Status:** [ ]

**Resources:**
- Ian Goodfellow, Yoshua Bengio & Aaron Courville, *Deep Learning* (Part II, optimization chapters)
- Sebastian Ruder, "An Overview of Gradient Descent Optimization Algorithms"

---

## Convolutional Networks / Computer Vision (`ML_CNN`)

Convolutional layers exploit the spatial structure of images — local
connectivity and weight sharing — to learn translation-invariant features
with far fewer parameters than a fully-connected network would need. The
historical arc (LeNet → AlexNet → VGG → ResNet's residual connections
solving the degradation problem in very deep nets → Vision Transformers
challenging the convolutional prior itself) is a good case study in how a
field's architectural assumptions get revised as more compute and data
become available. Beyond classification, the same building blocks
underlie object detection, segmentation, and pose estimation.

**Status:** [ ]

**Resources:**
- Stanford CS231n, *Convolutional Neural Networks for Visual Recognition* (lecture notes and videos, free online)
- Kaiming He et al., "Deep Residual Learning for Image Recognition" (the ResNet paper)

---

## Sequence Models & Transformers / NLP (`ML_SEQ`)

RNNs and LSTMs process sequences step by step and struggle with long-range
dependencies and parallelization; the transformer architecture (Vaswani et
al., "Attention Is All You Need") replaced recurrence with self-attention,
letting every token attend directly to every other token and enabling
massive parallel training on GPUs/TPUs — which is the single architectural
change that made today's large language models feasible. Positional
encodings, multi-head attention, and the encoder-decoder vs. decoder-only
distinction (GPT-style) are the core pieces worth understanding in depth,
since essentially all frontier NLP and multimodal work now sits on top of
this architecture.

**Status:** [ ]

**Resources:**
- Vaswani et al., "Attention Is All You Need" (2017)
- Stanford CS224n, *Natural Language Processing with Deep Learning* (lecture notes and videos, free online)
- Jay Alammar, "The Illustrated Transformer" (blog post, excellent visual intuition)
