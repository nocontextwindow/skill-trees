# Machine Learning / AI — Foundations

[← Back to index](./index.md)

---

## Math Foundations: Linear Algebra / Calculus / Probability & Stats (`ML_MATH`)

Linear algebra is the native language of ML — data points are vectors,
datasets are matrices, and a neural network layer is literally a matrix
multiplication followed by a nonlinearity; eigenvalues/eigenvectors and
singular value decomposition underlie PCA and much of dimensionality
reduction. Multivariable calculus (gradients, the chain rule) is what makes
backpropagation possible. Probability and statistics supply the actual
conceptual foundation of learning from data: what a distribution is, what
it means to estimate parameters from samples, and why every model is
implicitly a statement about uncertainty. Skipping straight to frameworks
without this tends to produce practitioners who can call `.fit()` but can't
diagnose why a model is failing.

**Status:** [ ]

**Resources:**
- Gilbert Strang, *Linear Algebra and Learning from Data*
- Kevin Murphy, *Probabilistic Machine Learning: An Introduction* (ch. 1–3 for the math refresher)
- Mathematics for Machine Learning (Deisenroth, Faisal, Ong) — free online

---

## Programming Foundations: Python / Data Structures & Algorithms (`ML_PROG`)

Python is the field's lingua franca because of its ecosystem (NumPy,
PyTorch, scikit-learn) rather than any special language feature, so fluency
in vectorized array operations (avoiding Python-level loops in favor of
NumPy/tensor broadcasting) matters more than deep language mastery. Classic
data structures and algorithms (complexity analysis, hash maps, trees,
sorting/searching) still matter for writing efficient data pipelines and
for technical interviews, but the ML-specific skill on top of that is
being comfortable reading and modifying someone else's tensor code, where
shape mismatches are the single most common bug class.

**Status:** [ ]

**Resources:**
- Wes McKinney, *Python for Data Analysis*
- CS50's Introduction to Computer Science (for DS&A fundamentals, if needed)
- fast.ai's *Practical Deep Learning for Coders* (code-first, gets you productive fast)
