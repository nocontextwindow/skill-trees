# Political Philosophy

Fleshing out political positions all the way down to root principles — well
enough to argue them, and well enough to counter them.

This tree is structured as **open questions**, not a checklist. For every
contested question below: **steelman the strongest version of the position
you disagree with before writing your own answer.** A counter to a
strawman isn't worth having, and it won't survive contact with someone who
actually knows the material.

## Skill Tree

```mermaid
flowchart TD
    subgraph "Root Principles"
        POL_ROOT[State of Nature & Social Contract<br/>Hobbes / Locke / Rousseau]
        POL_RIGHTS[Individual Rights &<br/>the Non-Aggression Principle]
        POL_CHRISTIAN[Christian Heritage of the West<br/>Christendom's role in liberalism]
        POL_ROOT --> POL_RIGHTS --> POL_CHRISTIAN
    end

    subgraph "Selfhood & Morality"
        POL_SELFISH[The Virtue of Selfishness<br/>Rational egoism as political foundation]
        POL_MORAL[Morality & Its Enforcement by Society]
        POL_HEDON[Against Hedonism]
        POL_PROMISC[Against Promiscuity<br/>in the Modern Age]
        POL_SELFISH --> POL_MORAL --> POL_HEDON --> POL_PROMISC
    end

    subgraph "Religion & the Divine"
        POL_RELIGION[The Positive Social Role of Religion]
        POL_DIVINE[The Usefulness of the<br/>Conception of the Divine]
        POL_THEOCRACY[Theocracy<br/>Case Studies & Critique]
        POL_SPIRIT[Rationality & the Spiritual<br/>A Secular Spiritual Domain]
        POL_RELIGION --> POL_DIVINE --> POL_THEOCRACY --> POL_SPIRIT
    end

    subgraph "Power, History & Stability"
        POL_FRAMES[Frames of Power & Brainwashing<br/>Propaganda / Overton Window]
        POL_FACTIONS[Factions<br/>Federalist No. 10, Coalition Stability]
        POL_COLONIAL[History of Colonization & Imperialism]
        POL_FEMINISM[Feminism<br/>Core Claims & a Critical Response]
        POL_FRAMES --> POL_FACTIONS --> POL_COLONIAL --> POL_FEMINISM
    end

    POL_CHRISTIAN --> POL_SELFISH
    POL_CHRISTIAN --> POL_RELIGION
    POL_ROOT --> POL_FRAMES

    classDef crosslink stroke-dasharray: 5 5
    POL_PP(("→ Personal Philosophy")):::crosslink
    POL_ES(("→ Esotericism & Religion")):::crosslink
    POL_PWR(("→ Power & Frame Control")):::crosslink
    POL_EP(("→ Epistemology")):::crosslink
    POL_SELFISH --> POL_PP
    POL_DIVINE --> POL_ES
    POL_FRAMES --> POL_PWR
    POL_ROOT --> POL_EP
```

## Sections

- [Root Principles](./root-principles.md) — `POL_ROOT` `POL_RIGHTS` `POL_CHRISTIAN`
- [Selfhood & Morality](./selfhood-and-morality.md) — `POL_SELFISH` `POL_MORAL` `POL_HEDON` `POL_PROMISC`
- [Religion & the Divine](./religion-and-the-divine.md) — `POL_RELIGION` `POL_DIVINE` `POL_THEOCRACY` `POL_SPIRIT`
- [Power, History & Stability](./power-history-and-stability.md) — `POL_FRAMES` `POL_FACTIONS` `POL_COLONIAL` `POL_FEMINISM`

See also: [Book List](../../BOOKLIST.md).

## Related Trees

- [Personal Philosophy](../personal-philosophy/index.md) — `POL_SELFISH` is
  the political extension of rational egoism.
- [Esotericism & Religion](../esotericism-and-religion/index.md) —
  `POL_DIVINE` and `POL_THEOCRACY` connect to Gnosticism and secular
  spirituality there.
- [Power & Frame Control](../power-and-frame-control/index.md) —
  `POL_FRAMES` is the political-theory side of propaganda technique.
- [Epistemology](../epistemology/index.md) — root-principles reasoning
  depends on theories of justification.
- [Economics](../economics/index.md) — `POL_FACTIONS` overlaps with the
  game theory of coalitions.
