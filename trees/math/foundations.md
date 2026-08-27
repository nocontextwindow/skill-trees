# Mathematics — Foundations

[← Back to index](./index.md)

---

## Algebra & Precalculus (`MATH_ALGEBRA`)

The symbolic manipulation layer everything else sits on: solving and
rearranging equations, working fluently with exponents, logarithms,
polynomials, and rational functions, and reasoning about functions
(domain, range, composition, inverses) and their graphs. Trigonometry
belongs here too — it's the bridge between algebra and geometry that shows
up again the moment calculus needs periodic functions. Most people who
"can't do calculus" actually have a shaky algebra foundation; fluency here
(not just correctness, but speed and pattern recognition) is what makes
everything downstream tractable rather than a slog. It's unglamorous, but
skipping it to get to "real" math is a false economy.

**Status:** [ ]

**Resources:**
- Sheldon Axler, *Precalculus: A Prelude to Calculus*
- Paul's Online Math Notes (Lamar University) — free, thorough reference
- Art of Problem Solving, *Intermediate Algebra*

---

## Calculus (`MATH_CALC`)

Single-variable calculus formalizes rate of change (derivatives) and
accumulation (integrals), and the Fundamental Theorem of Calculus ties the
two together as inverse operations. Multivariable calculus extends this to
functions of several variables — gradients, partial derivatives, multiple
integrals, and vector calculus (line integrals, Stokes' and divergence
theorems) — which is where the machinery needed for physics, optimization,
and machine learning actually lives. The conceptual leap worth dwelling on
is the epsilon-delta definition of a limit, which is what eventually
justifies everything that came before it rigorously (that justification is
deferred to real analysis). Most applied fields only need the computational
fluency, not the proofs, but knowing where the proofs would go matters for
knowing when the intuition breaks.

**Status:** [ ]

**Resources:**
- James Stewart, *Calculus: Early Transcendentals*
- Gilbert Strang, *Calculus* (free via MIT OpenCourseWare)
- 3Blue1Brown, *Essence of Calculus* (video series) — best visual intuition available

---

## Linear Algebra (`MATH_LINALG`)

Vectors, matrices, and linear transformations — plus the deeper structural
ideas of vector spaces, basis, rank, eigenvalues/eigenvectors, and
diagonalization. This is arguably the single highest-leverage math subject
for anyone doing quantitative work: it's the language of systems of
equations, of computer graphics, of quantum mechanics, and of essentially
all of modern machine learning (a neural network is just a stack of linear
transformations interleaved with nonlinearities). The eigenvalue/eigenvector
concept in particular recurs everywhere — PCA, Markov chains, vibration
modes, PageRank — as "the directions a transformation doesn't rotate, only
scales." Gilbert Strang's framing (the four fundamental subspaces, and
understanding matrices as transformations rather than just grids of
numbers) is the standard for building real intuition rather than just
computational competence.

**Status:** [ ]

**Resources:**
- Gilbert Strang, *Introduction to Linear Algebra*
- Gilbert Strang, MIT 18.06 lecture videos (OCW)
- 3Blue1Brown, *Essence of Linear Algebra* (video series)

---

## Differential Equations (`MATH_DIFFEQ`)

Equations that relate a function to its own derivatives — the natural
language for describing anything that changes continuously over time:
population growth, circuits, mechanical vibration, heat flow, orbital
mechanics. Ordinary differential equations (ODEs) handle single-variable
systems; partial differential equations (PDEs) — the heat equation, wave
equation, Laplace's equation — handle fields that vary over space and time
and are considerably harder, usually requiring numerical methods rather
than closed-form solutions. A key conceptual split worth internalizing
early is linear vs. nonlinear systems: linear ODEs have well-behaved,
superposable solutions, while nonlinear systems can exhibit chaos, limit
cycles, and bifurcations that make long-term prediction fundamentally
limited (see chaos theory). This is the subject where math visibly turns
into physics and engineering.

**Status:** [ ]

**Resources:**
- William Boyce & Richard DiPrima, *Elementary Differential Equations*
- Steven Strogatz, *Nonlinear Dynamics and Chaos*
- MIT 18.03 (Differential Equations) lecture videos (OCW)
