# Machine Learning / AI — Core ML

[← Back to index](./index.md)

---

## Supervised Learning (`ML_SUP`)

Learning a mapping from inputs to labeled outputs: regression for
continuous targets, classification for discrete ones. The classical
progression — linear/logistic regression, decision trees, ensemble methods
(random forests, gradient boosting), support vector machines — is worth
knowing cold before jumping to neural networks, both because these methods
are often the right practical tool (gradient-boosted trees still win most
tabular-data competitions) and because they make the bias-variance
tradeoff and regularization concrete in settings simple enough to reason
about by hand.

**Status:** [ ]

**Resources:**
- Gareth James et al., *An Introduction to Statistical Learning* (free online, gentler)
- Hastie, Tibshirani & Friedman, *The Elements of Statistical Learning* (free online, more rigorous)
- Andrew Ng's Machine Learning Specialization (Coursera)

---

## Unsupervised Learning (`ML_UNSUP`)

Finding structure in unlabeled data: clustering (k-means, hierarchical,
DBSCAN), dimensionality reduction (PCA, t-SNE, UMAP), and density
estimation. There's no ground-truth label to check answers against, which
makes evaluation itself a genuinely hard and somewhat philosophical problem
— what does it mean for a clustering to be "correct" when the data was
never labeled with clusters in the first place? This node is also the
conceptual bridge to generative modeling (`ML_GEN`), since generative
models are ultimately trying to learn the unlabeled data distribution
itself.

**Status:** [ ]

**Resources:**
- Kevin Murphy, *Probabilistic Machine Learning: An Introduction* (clustering & PCA chapters)
- Christopher Bishop, *Pattern Recognition and Machine Learning*

---

## Model Evaluation & Validation (`ML_EVAL`)

The discipline of knowing whether a model actually works: train/validation/
test splits, cross-validation, the bias-variance tradeoff, and picking the
right metric for the problem (accuracy is often actively misleading under
class imbalance — precision/recall/F1/ROC-AUC exist for a reason). The
deeper issue underneath all of this is generalization — why a model fit to
one finite sample should say anything reliable about data it hasn't seen —
which is exactly Hume's problem of induction (`EP_SCI`) wearing an ML
costume, and which statistical learning theory (VC dimension, PAC
learning) tries to formalize.

**Status:** [ ]

**Resources:**
- Gareth James et al., *An Introduction to Statistical Learning* (ch. 5 on resampling)
- Kevin Murphy, *Probabilistic Machine Learning: An Introduction* (evaluation & model selection)
