# Civil Engineering — Foundations

[← Back to index](./index.md)

---

## Engineering Math (`CE_MATH`)

The working toolkit is calculus (through multivariable and vector
calculus), linear algebra (for stiffness matrices and finite element
methods), ordinary and partial differential equations (beam deflection,
heat and fluid flow), and enough numerical methods to know when a
closed-form solution doesn't exist and an iterative one is needed instead.
None of this is civil-engineering-specific, but the field leans especially
hard on differential equations and matrix methods because almost every
downstream topic — structural analysis, hydraulics, soil consolidation —
reduces to solving one.

**Status:** [ ]

**Resources:**
- Erwin Kreyszig, *Advanced Engineering Mathematics*
- Steven Chapra & Raymond Canale, *Numerical Methods for Engineers*

---

## Statics (`CE_STATICS`)

Statics is the study of bodies in equilibrium — forces and moments summing
to zero — and it's the entry point to every structural problem because a
building, bridge, or dam has to satisfy exactly this condition to not fall
down. The core skills are free-body diagrams, truss and frame analysis
(method of joints, method of sections), and shear/moment diagrams for
beams, all of which look simple in isolation but compound quickly once a
structure has more members than equations, which is where the "Structural
Analysis" section's indeterminate methods pick up.

**Status:** [ ]

**Resources:**
- Russell Hibbeler, *Engineering Mechanics: Statics*
- J.L. Meriam & L.G. Kraige, *Engineering Mechanics: Statics*

---

## Mechanics of Materials (`CE_MECH`)

Where statics treats members as rigid, mechanics of materials asks what
actually happens inside a loaded member: stress and strain distributions,
axial and bending stress, torsion, shear, and deflection, plus failure
modes like buckling in slender compression members. This is the direct
engineering application of the stress-strain behavior covered in materials
science's `MAT_MECH`, translated into the design formulas (allowable
stress, factor of safety, load and resistance factor design) that actually
size a beam or column. Getting this section solid is a prerequisite for
every structural design decision downstream.

**Status:** [ ]

**Resources:**
- Russell Hibbeler, *Mechanics of Materials*
- James Gere & Barry Goodno, *Mechanics of Materials*
