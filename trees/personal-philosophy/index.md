# Personal Philosophy

Building a coherent, examined worldview: how to think clearly, what's
actually good, what a life well-lived looks like, and how to live by it.
Heavily shaped by Ayn Rand's Objectivism ([SEP entry](https://plato.stanford.edu/entries/ayn-rand/))
and Jordan Peterson's work on meaning and mythic archetypes.

This tree is structured as **open questions**, not a checklist — the goal
isn't to "complete" a node, it's to arrive at (and keep revising) an actual
answer. Each section file has the questions, a place for the current
answer, and the resources behind it.

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

## Sections

- [Foundations](./foundations.md) — `PP_WHATIS` `PP_LOGIC` `PP_AXIO` `PP_HIST`
- [Ethics & Character](./ethics-and-character.md) — `PP_META` `PP_EGO` `PP_VIRTUE` `PP_STOIC`
- [Sense of Life & Aesthetics](./sense-of-life-and-aesthetics.md) — `PP_SENSE` `PP_AES` `PP_MUSIC`
- [The Heroic Archetype](./the-heroic-archetype.md) — `PP_HERO` `PP_PETERSON` `PP_PATRIARCH` `PP_NARR`
- [Meaning, Mind & Future](./meaning-mind-and-future.md) — `PP_EXIS` `PP_MIND` `PP_TRANS`

See also: [Book List](../../BOOKLIST.md).

## Related Trees

- [Political Philosophy](../political-philosophy/index.md) — off of the
  Ethics & Character section: the deep dive into root political principles.
- [Psychology & Self-Mastery](../psychology-self-mastery/index.md) — off of
  Meaning, Mind & Future: controlling your own mind, building the
  ideal-self concept.
- [Power & Frame Control](../power-and-frame-control/index.md) — off of The
  Heroic Archetype: the patriarch as a power/frame-control archetype.
- [Esotericism & Religion](../esotericism-and-religion/index.md) — off of
  Sense of Life & Aesthetics: a secular, useful account of the "spiritual."
- [Epistemology](../epistemology/index.md) — how you justify what you
  believe underlies both ethics and metaphysics.
- [Physics](../physics/index.md) — the metaphysics questions here connect to
  interpretations of QM.
