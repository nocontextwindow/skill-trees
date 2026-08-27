# Physics

From the math prerequisites through classical and modern physics to the
open questions at the edges of the field.

## Skill Tree

```mermaid
flowchart TD
    subgraph Foundations
        PH_MATH[Math Prerequisites<br/>Calculus / Linear Algebra / Diff Eq]
        PH_CLASS[Classical Mechanics]
    end

    subgraph Core
        PH_EM[Electromagnetism]
        PH_THERMO[Thermodynamics &<br/>Statistical Mechanics]
        PH_WAVES[Waves & Optics]
    end

    subgraph Modern
        PH_SR[Special Relativity]
        PH_GR[General Relativity]
        PH_QM[Quantum Mechanics]
    end

    subgraph Advanced
        PH_QFT[Quantum Field Theory]
        PH_PARTICLE[Particle Physics]
        PH_COSMO[Cosmology]
        PH_COND[Condensed Matter Physics]
    end

    PH_PHILO[Philosophy of Physics<br/>QM Interpretations / Space & Time]
    PH_CAPSTONE[["Capstone: Research Deep Dive"]]

    PH_MATH --> PH_CLASS
    PH_CLASS --> PH_EM
    PH_CLASS --> PH_THERMO
    PH_EM --> PH_WAVES
    PH_EM --> PH_SR
    PH_SR --> PH_GR
    PH_WAVES --> PH_QM
    PH_THERMO --> PH_QM

    PH_QM --> PH_QFT
    PH_SR --> PH_QFT
    PH_QFT --> PH_PARTICLE
    PH_GR --> PH_COSMO
    PH_QM --> PH_COSMO
    PH_QM --> PH_COND
    PH_THERMO --> PH_COND

    PH_QM --> PH_PHILO
    PH_GR --> PH_PHILO

    PH_PARTICLE --> PH_CAPSTONE
    PH_COSMO --> PH_CAPSTONE
    PH_COND --> PH_CAPSTONE
    PH_PHILO --> PH_CAPSTONE

    classDef crosslink stroke-dasharray: 5 5
    PH_EP(("→ Epistemology<br/>(philosophy of science)")):::crosslink
    PH_ML(("→ ML/AI<br/>(stat mech <-> energy-based models)")):::crosslink
    PH_PHILO --> PH_EP
    PH_THERMO --> PH_ML
```

## Nodes

| ID | Concept | Depends on | Status | Resources / Notes |
|---|---|---|---|---|
| PH_MATH | Math prerequisites | — | [ ] | |
| PH_CLASS | Classical Mechanics | PH_MATH | [ ] | |
| PH_EM | Electromagnetism | PH_CLASS | [ ] | |
| PH_THERMO | Thermodynamics & Statistical Mechanics | PH_CLASS | [ ] | |
| PH_WAVES | Waves & Optics | PH_EM | [ ] | |
| PH_SR | Special Relativity | PH_EM | [ ] | |
| PH_GR | General Relativity | PH_SR | [ ] | |
| PH_QM | Quantum Mechanics | PH_WAVES, PH_THERMO | [ ] | |
| PH_QFT | Quantum Field Theory | PH_QM, PH_SR | [ ] | |
| PH_PARTICLE | Particle Physics | PH_QFT | [ ] | |
| PH_COSMO | Cosmology | PH_GR, PH_QM | [ ] | |
| PH_COND | Condensed Matter Physics | PH_QM, PH_THERMO | [ ] | |
| PH_PHILO | Philosophy of Physics (QM interpretations, space & time) | PH_QM, PH_GR | [ ] | |
| PH_CAPSTONE | **Capstone:** Research Deep Dive | PH_PARTICLE, PH_COSMO, PH_COND, PH_PHILO | [ ] | Pick one open question and go deep |

## Related Trees

- [Epistemology](epistemology.md) — `PH_PHILO` is a direct application of
  `EP_SCI` (induction/falsifiability).
- [Machine Learning / AI](machine-learning-ai.md) — `PH_THERMO` (statistical
  mechanics) shares its math with `ML_GEN` (energy-based models, diffusion
  models are literally simulated thermodynamics).
- [Personal Philosophy](personal-philosophy.md) — `PH_PHILO`'s questions
  about determinism and the nature of time bear on `PP_META`.
