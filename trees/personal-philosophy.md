# Personal Philosophy

Building a coherent, examined worldview: how to think clearly, what's
actually good, what a life well-lived looks like, and how to live by it.
Heavily shaped by Ayn Rand's Objectivism ([SEP entry](https://plato.stanford.edu/entries/ayn-rand/))
and Jordan Peterson's work on meaning and mythic archetypes.

## Skill Tree

```mermaid
flowchart TD
    subgraph Foundations
        PP_WHATIS[What Is Philosophy?]
        PP_LOGIC[Logic & Critical Thinking]
        PP_AXIO[Axiology<br/>Theory of Value]
        PP_HIST[History of Philosophy<br/>Survey]
        PP_WHATIS --> PP_LOGIC --> PP_AXIO --> PP_HIST
    end

    subgraph "Ethics & Character"
        PP_META[Metaphysics<br/>Objective Reality / the Forms debate]
        PP_EGO[Rational Egoism<br/>Rand's Virtue of Selfishness]
        PP_VIRTUE[Virtue Ethics<br/>Rationality, Independence, Integrity, Pride]
        PP_STOIC[Stoicism & Practical Philosophy]
        PP_META --> PP_EGO --> PP_VIRTUE --> PP_STOIC
    end

    subgraph "Sense of Life & Aesthetics"
        PP_SENSE[Sense of Life<br/>Rand's pre-conceptual value-sense]
        PP_AES[Aesthetics<br/>Romantic Realism]
        PP_MUSIC[Music & Art as<br/>Sense-of-Life Expression]
        PP_SENSE --> PP_AES --> PP_MUSIC
    end

    subgraph "The Heroic Archetype"
        PP_HERO[The Heroic Journey<br/>Campbell's Monomyth]
        PP_PETERSON[Peterson's Hero Archetype<br/>Chaos & Order, Meaning]
        PP_PATRIARCH[The Patriarch<br/>The Ever-Present, Binding Figure]
        PP_NARR[Heroic Narratives in Fiction<br/>e.g. One Piece]
        PP_HERO --> PP_PETERSON --> PP_PATRIARCH --> PP_NARR
    end

    subgraph "Meaning, Mind & Future"
        PP_EXIS[Existentialism & Meaning]
        PP_MIND[Philosophy of Mind]
        PP_TRANS[Transhumanism & Longevity<br/>Life-Affirming Ambition]
    end

    PP_HIST --> PP_META
    PP_META --> PP_SENSE
    PP_HIST --> PP_HERO
    PP_HIST --> PP_EXIS
    PP_META --> PP_MIND
    PP_SENSE --> PP_TRANS

    classDef crosslink stroke-dasharray: 5 5
    PP_EPIS(("→ Epistemology")):::crosslink
    PP_PHILSCI(("→ Physics<br/>philosophy of science")):::crosslink
    PP_POL(("→ Political Philosophy<br/>full tree")):::crosslink
    PP_SELF(("→ Psychology & Self-Mastery<br/>full tree")):::crosslink
    PP_PWR(("→ Power & Frame Control<br/>full tree")):::crosslink
    PP_ES(("→ Esotericism & Religion<br/>secular spirituality")):::crosslink

    PP_LOGIC --> PP_EPIS
    PP_META --> PP_PHILSCI
    PP_VIRTUE --> PP_POL
    PP_MIND --> PP_SELF
    PP_PATRIARCH --> PP_PWR
    PP_SENSE --> PP_ES
```

## Nodes

| ID | Concept | Depends on | Status | Resources / Notes |
|---|---|---|---|---|
| PP_WHATIS | What Is Philosophy? | — | [ ] | |
| PP_LOGIC | Logic & Critical Thinking | PP_WHATIS | [ ] | |
| PP_AXIO | Axiology (theory of value) | PP_LOGIC | [ ] | |
| PP_HIST | History of Philosophy (survey) | PP_AXIO | [ ] | |
| PP_META | Metaphysics (objective reality, Platonic Forms debate) | PP_HIST | [ ] | |
| PP_EGO | Rational Egoism | PP_META | [ ] | Ayn Rand, *The Virtue of Selfishness*; [SEP: Ayn Rand](https://plato.stanford.edu/entries/ayn-rand/) |
| PP_VIRTUE | Virtue Ethics (rationality, independence, integrity, justice, productiveness, pride) | PP_EGO | [ ] | Rand's list of rational virtues; Aristotle, *Nicomachean Ethics* for contrast |
| PP_STOIC | Stoicism & Practical Philosophy | PP_VIRTUE | [ ] | |
| PP_SENSE | Sense of Life | PP_META | [ ] | Rand, *The Romantic Manifesto* — ch. on sense of life as "a pre-conceptual equivalent of metaphysics" |
| PP_AES | Aesthetics (Romantic Realism) | PP_SENSE | [ ] | Rand, *The Romantic Manifesto* |
| PP_MUSIC | Music & Art as sense-of-life expression | PP_AES | [ ] | |
| PP_HERO | The Heroic Journey | PP_HIST | [ ] | Joseph Campbell, *The Hero with a Thousand Faces* |
| PP_PETERSON | Peterson's Hero Archetype (chaos & order, meaning) | PP_HERO | [ ] | Jordan Peterson, *Maps of Meaning*; *12 Rules for Life* |
| PP_PATRIARCH | The Patriarch — the ever-present, binding figure | PP_PETERSON | [ ] | Peterson on paternal archetypes; Jung on symbols of the father |
| PP_NARR | Heroic narratives in fiction | PP_PATRIARCH | [ ] | e.g. *One Piece* as a modern monomyth case study |
| PP_EXIS | Existentialism & Meaning | PP_HIST | [ ] | |
| PP_MIND | Philosophy of Mind | PP_META | [ ] | |
| PP_TRANS | Transhumanism & Longevity | PP_SENSE | [ ] | Life-affirming, achievement-oriented "technosupremacy" angle |

## Related Trees

- [Political Philosophy](political-philosophy.md) — off of `PP_VIRTUE`: the
  deep dive into root political principles.
- [Psychology & Self-Mastery](psychology-self-mastery.md) — off of `PP_MIND`:
  controlling your own mind, building the ideal-self concept.
- [Power & Frame Control](power-and-frame-control.md) — off of
  `PP_PATRIARCH`: the patriarch as a power/frame-control archetype.
- [Esotericism & Religion](esotericism-and-religion.md) — off of `PP_SENSE`:
  a secular, useful account of the "spiritual."
- [Epistemology](epistemology.md) — how you justify what you believe
  underlies both ethics and metaphysics.
- [Physics](physics.md) — `PP_META`'s questions about causation and
  determinism connect to `PH_PHILO` (interpretations of QM).
