# Psychology & Self-Mastery

Controlling your own mind: personality, motivation, habits, and building
toward an ideal-self concept on purpose instead of by accident.

## Skill Tree

```mermaid
flowchart TD
    subgraph "Self-Concept"
        PSY_PERSONALITY[Personality Models<br/>Big Five, Jungian types]
        PSY_IDEAL[Ideal Self Concept<br/>cf. the Platonic ideal form]
        PSY_AUTHOR[Self-Authoring<br/>Personal Narrative Construction]
        PSY_PERSONALITY --> PSY_IDEAL --> PSY_AUTHOR
    end

    subgraph "Drive & Execution"
        PSY_MOTIVE[Motivation — Theory & Practice]
        PSY_HABIT[Habit Formation]
        PSY_PRODUCTIVITY[Productivity Systems]
        PSY_MOTIVE --> PSY_HABIT --> PSY_PRODUCTIVITY
    end

    subgraph "Mental Control"
        PSY_VISUAL[Visualization Techniques]
        PSY_HYPNO[Self-Hypnosis]
        PSY_COGCTRL[Cognitive Control & Meta-Cognition<br/>controlling your own mind]
        PSY_VISUAL --> PSY_HYPNO --> PSY_COGCTRL
    end

    PSY_IDEAL --> PSY_MOTIVE
    PSY_MOTIVE --> PSY_VISUAL
    PSY_AUTHOR --> PSY_COGCTRL

    classDef crosslink stroke-dasharray: 5 5
    PSY_PP(("→ Personal Philosophy<br/>heroic journey")):::crosslink
    PSY_SOC(("→ Social Skills")):::crosslink
    PSY_AUTHOR --> PSY_PP
    PSY_COGCTRL --> PSY_SOC
```

## Sections

- [Self-Concept](./self-concept.md) — `PSY_PERSONALITY` `PSY_IDEAL` `PSY_AUTHOR`
- [Drive & Execution](./drive-and-execution.md) — `PSY_MOTIVE` `PSY_HABIT` `PSY_PRODUCTIVITY`
- [Mental Control](./mental-control.md) — `PSY_VISUAL` `PSY_HYPNO` `PSY_COGCTRL`

See also: [Book List](../../BOOKLIST.md).

## Related Trees

- [Personal Philosophy](../personal-philosophy/index.md) — Self-Authoring is
  the practical arm of the heroic archetype work.
- [Social Skills](../social-skills/index.md) — cognitive control is a
  prerequisite for reliable communication under pressure.
