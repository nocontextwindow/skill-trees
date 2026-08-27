# Political Philosophy

Fleshing out political positions all the way down to root principles — well
enough to argue them, and well enough to counter them. **Approach: steelman
the strongest version of a position before building the counter-case.** A
counter to a strawman isn't worth having.

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

## Nodes

| ID | Concept | Depends on | Status | Resources / Notes |
|---|---|---|---|---|
| POL_ROOT | State of Nature & Social Contract | — | [ ] | Hobbes, *Leviathan*; Locke, *Second Treatise of Government* |
| POL_RIGHTS | Individual Rights & the Non-Aggression Principle | POL_ROOT | [ ] | Nozick, *Anarchy, State, and Utopia* |
| POL_CHRISTIAN | Christian Heritage of the West | POL_RIGHTS | [ ] | Tom Holland, *Dominion*; Larry Siedentop, *Inventing the Individual* |
| POL_SELFISH | The Virtue of Selfishness | POL_CHRISTIAN | [ ] | Ayn Rand, *The Virtue of Selfishness*; [SEP: Ayn Rand](https://plato.stanford.edu/entries/ayn-rand/) |
| POL_MORAL | Morality & Its Enforcement by Society | POL_SELFISH | [ ] | Jonathan Haidt, *The Righteous Mind* |
| POL_HEDON | Against Hedonism | POL_MORAL | [ ] | Rand's critique of hedonism vs. Aristotelian eudaimonia |
| POL_PROMISC | Against Promiscuity in the Modern Age | POL_HEDON | [ ] | Peterson's lectures on monogamy & pair-bonding |
| POL_RELIGION | The Positive Social Role of Religion | POL_CHRISTIAN | [ ] | Peterson, *Maps of Meaning* |
| POL_DIVINE | The Usefulness of the Conception of the Divine | POL_RELIGION | [ ] | Jung, *Answer to Job*; Peterson's Biblical psychology lectures |
| POL_THEOCRACY | Theocracy — Case Studies & Critique | POL_DIVINE | [ ] | Case studies: Calvin's Geneva, post-1979 Iran |
| POL_SPIRIT | Rationality & the Spiritual (a secular spiritual domain) | POL_THEOCRACY | [ ] | Jung, *Psychology and Religion* |
| POL_FRAMES | Frames of Power & Brainwashing | POL_ROOT | [ ] | Bernays, *Propaganda*; Lakoff, *Don't Think of an Elephant* |
| POL_FACTIONS | Factions & Coalition Stability | POL_FRAMES | [ ] | Madison, *Federalist No. 10* |
| POL_COLONIAL | History of Colonization & Imperialism | POL_FACTIONS | [ ] | Niall Ferguson, *Empire*; steelman: Edward Said, *Orientalism* |
| POL_FEMINISM | Feminism — core claims & a critical response | POL_COLONIAL | [ ] | Steelman: bell hooks, *Feminism Is for Everybody*; critical: Camille Paglia, *Sexual Personae*; Christina Hoff Sommers, *Who Stole Feminism?* |

## Related Trees

- [Personal Philosophy](personal-philosophy.md) — `POL_SELFISH` is the
  political extension of `PP_EGO`.
- [Esotericism & Religion](esotericism-and-religion.md) — `POL_DIVINE` and
  `POL_THEOCRACY` connect to `ES_GNOSTIC` and `ES_SECULAR`.
- [Power & Frame Control](power-and-frame-control.md) — `POL_FRAMES` is the
  political-theory side of `PWR_PROP`.
- [Epistemology](epistemology.md) — root-principles reasoning depends on
  `EP_JUST` (theories of justification).
- [Economics](economics.md) — `POL_FACTIONS` overlaps with the game theory
  of coalitions in `ECON_GAME`.
