# Physics

From the math prerequisites through classical and modern physics to the
places where the field's own foundations are still open.

The chain below is the standard order of dependence, not a ranking of
importance — the interpretive questions at the end are live at every level,
and several of them are older than the theories they attach to.

## Tree

```mermaid
flowchart TD
    subgraph Foundations
        PH_MATH[Math Prerequisites<br/>Calculus / Linear Algebra / Diff Eq]
        PH_CLASS[Classical Mechanics]
        PH_MATH --> PH_CLASS
    end

    subgraph Core
        PH_EM[Electromagnetism]
        PH_THERMO[Thermodynamics &<br/>Statistical Mechanics]
        PH_WAVES[Waves & Optics]
        PH_EM --> PH_THERMO --> PH_WAVES
    end

    subgraph Modern
        PH_SR[Special Relativity]
        PH_GR[General Relativity]
        PH_QM[Quantum Mechanics]
        PH_SR --> PH_GR --> PH_QM
    end

    subgraph Advanced
        PH_QFT[Quantum Field Theory]
        PH_PARTICLE[Particle Physics]
        PH_COSMO[Cosmology]
        PH_COND[Condensed Matter Physics]
        PH_QFT --> PH_PARTICLE --> PH_COSMO --> PH_COND
    end

    PH_PHILO[Philosophy of Physics<br/>QM Interpretations / Space & Time]

    PH_CLASS --> PH_EM
    PH_WAVES --> PH_SR
    PH_QM --> PH_QFT
    PH_QM --> PH_PHILO
    PH_GR --> PH_PHILO

    classDef crosslink stroke-dasharray: 5 5
    PH_EP(("→ Epistemology<br/>philosophy of science")):::crosslink
    PH_ML(("→ ML/AI<br/>stat mech <-> energy-based models")):::crosslink
    PH_PHILO --> PH_EP
    PH_THERMO --> PH_ML
```

## Related Trees

- [Epistemology](../../self/epistemology/index.md) — `PH_PHILO` is a direct
  application of `EP_SCI` (induction/falsifiability).
- [Machine Learning / AI](../machine-learning-ai/index.md) — `PH_THERMO`
  (statistical mechanics) shares its math with `ML_GEN` (diffusion models
  are literally simulated thermodynamics).
- [Materials Science](../materials-science/index.md) — `PH_THERMO` and `PH_COND`
  underlie `MAT_THERMO` and `MAT_ELEC`.
- [Personal Philosophy](../../self/personal-philosophy/index.md) — `PH_PHILO`'s
  questions about determinism and the nature of time bear on `PP_META`.

See also: [Book List](../../BOOKLIST.md).
