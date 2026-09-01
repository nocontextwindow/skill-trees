# Psychology & Self-Mastery

The mechanics of running yourself on purpose: what's stable about a person,
what moves them, and what can actually be changed by deciding to change it.

## Tree

```mermaid
flowchart TD
    subgraph "Self-Concept"
        PSY_PERSONALITY[Personality Models<br/>traits & types]
        PSY_IDEAL[Ideal Self Concept]
        PSY_AUTHOR[Self-Authoring<br/>personal narrative]
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
        PSY_COGCTRL[Cognitive Control &<br/>Meta-Cognition]
        PSY_VISUAL --> PSY_HYPNO --> PSY_COGCTRL
    end

    PSY_IDEAL --> PSY_MOTIVE
    PSY_MOTIVE --> PSY_VISUAL
    PSY_AUTHOR --> PSY_COGCTRL

    classDef crosslink stroke-dasharray: 5 5
    PSY_PP(("→ Personal Philosophy<br/>narrative & the heroic")):::crosslink
    PSY_SOC(("→ Social Skills")):::crosslink
    PSY_AUTHOR --> PSY_PP
    PSY_COGCTRL --> PSY_SOC
```

## Related Trees

- [Personal Philosophy](../personal-philosophy/index.md) — self-authoring is
  the practical arm of the narrative and heroic work.
- [Social Skills](../social-skills/index.md) — cognitive control is a
  prerequisite for reliable communication under pressure.

- [Self-Map](../self-map.md) — where this tree's models get
  applied to my own case.

See also: [Book List](../../BOOKLIST.md).
