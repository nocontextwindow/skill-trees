# Personal Philosophy

Constructing a philosophy from the ground up, on the classical branches.
Articles are questions to work through, not write-ups.

## Tree

```mermaid
flowchart TD
    subgraph "The Frame"
        PP_WHATFOR[What a Philosophy Is For]
        PP_STRUCTURE[Structure of a System<br/>what rests on what]
        PP_METHOD[Holding a Position<br/>revision, contradiction, integration]
        PP_WHATFOR --> PP_STRUCTURE --> PP_METHOD
    end

    subgraph Metaphysics
        PP_REALITY[Nature of Reality]
        PP_IDENTITY[Identity & Causality]
        PP_FREEWILL[Free Will & Determinism]
        PP_MIND[Consciousness & the Self]
        PP_REALITY --> PP_IDENTITY --> PP_FREEWILL --> PP_MIND
    end

    subgraph Ethics
        PP_AXIOLOGY[Axiology<br/>what value is]
        PP_STANDARD[The Standard of Value]
        PP_EGOISM[Egoism & Altruism]
        PP_VIRTUE[Virtue & Character]
        PP_PRACTICE[Living It<br/>ethics under real conditions]
        PP_AXIOLOGY --> PP_STANDARD --> PP_EGOISM --> PP_VIRTUE --> PP_PRACTICE
    end

    subgraph Aesthetics
        PP_SENSE[Sense of Life]
        PP_ART[Art, Beauty & Taste]
        PP_SENSE --> PP_ART
    end

    subgraph "Meaning & Self"
        PP_MEANING[Meaning & Purpose]
        PP_NARRATIVE[Narrative & the Heroic]
        PP_ROLE[Role, Duty & the Binding Figure]
        PP_MORTALITY[Mortality & Time Horizon]
        PP_MEANING --> PP_NARRATIVE --> PP_ROLE --> PP_MORTALITY
    end

    PP_METHOD --> PP_REALITY
    PP_MIND --> PP_AXIOLOGY
    PP_PRACTICE --> PP_SENSE
    PP_ART --> PP_MEANING

    classDef crosslink stroke-dasharray: 5 5
    PP_EP(("→ Epistemology")):::crosslink
    PP_POL(("→ Political Philosophy")):::crosslink
    PP_PSY(("→ Psychology & Self-Mastery")):::crosslink
    PP_ES(("→ Esotericism & Religion")):::crosslink
    PP_STRUCTURE --> PP_EP
    PP_PRACTICE --> PP_POL
    PP_ROLE --> PP_PSY
    PP_MEANING --> PP_ES
```

## Articles

**The Frame**
- [What a Philosophy Is For](articles/what-a-philosophy-is-for.md) — `PP_WHATFOR`
- [Structure of a System](articles/structure-of-a-system.md) — `PP_STRUCTURE`
- [Holding a Position](articles/holding-a-position.md) — `PP_METHOD`

**Metaphysics**
- [Nature of Reality](articles/nature-of-reality.md) — `PP_REALITY`
- [Identity & Causality](articles/identity-and-causality.md) — `PP_IDENTITY`
- [Free Will & Determinism](articles/free-will-and-determinism.md) — `PP_FREEWILL`
- [Consciousness & the Self](articles/consciousness-and-the-self.md) — `PP_MIND`

**Ethics**
- [Axiology — What Value Is](articles/axiology.md) — `PP_AXIOLOGY`
- [The Standard of Value](articles/the-standard-of-value.md) — `PP_STANDARD`
- [Egoism & Altruism](articles/egoism-and-altruism.md) — `PP_EGOISM`
- [Virtue & Character](articles/virtue-and-character.md) — `PP_VIRTUE`
- [Living It](articles/living-it.md) — `PP_PRACTICE`

**Aesthetics**
- [Sense of Life](articles/sense-of-life.md) — `PP_SENSE`
- [Art, Beauty & Taste](articles/art-beauty-and-taste.md) — `PP_ART`

**Meaning & Self**
- [Meaning & Purpose](articles/meaning-and-purpose.md) — `PP_MEANING`
- [Narrative & the Heroic](articles/narrative-and-the-heroic.md) — `PP_NARRATIVE`
- [Role, Duty & the Binding Figure](articles/role-duty-and-the-binding-figure.md) — `PP_ROLE`
- [Mortality & Time Horizon](articles/mortality-and-time-horizon.md) — `PP_MORTALITY`

## Related Trees

- [Epistemology](../epistemology/index.md) — the branch this system's
  claims to knowledge have to answer to.
- [Political Philosophy](../political-philosophy/index.md) — where the
  ethics gets extended to how people live together.
- [Psychology & Self-Mastery](../psychology-self-mastery/index.md) — the
  mechanics of actually running on a philosophy.
- [Esotericism & Religion](../esotericism-and-religion/index.md) — what the
  religious traditions are doing that a secular system has to account for.

See also: [Book List](../../BOOKLIST.md).
