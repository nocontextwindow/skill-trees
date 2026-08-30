# Social Skills

Communication, persuasion, and reading a room — the practical layer sitting
on top of frame control and psychology.

## Tree

```mermaid
flowchart TD
    subgraph "Foundation"
        SOC_COMM[Communication Fundamentals]
        SOC_BOUND[Boundaries]
        SOC_STORY[Storytelling & Narrative Framing]
        SOC_COMM --> SOC_BOUND --> SOC_STORY
    end

    subgraph "Persuasion"
        SOC_PERSUADE[Persuasion & Rhetoric]
        SOC_INFLUENCE[Influence]
        SOC_DEBATE[Debate]
        SOC_PERSUADE --> SOC_INFLUENCE --> SOC_DEBATE
    end

    subgraph "Presence"
        SOC_CONVO[Conversational Skill & Charisma]
        SOC_NETWORK[Networking]
        SOC_CONVO --> SOC_NETWORK
    end

    SOC_STORY --> SOC_PERSUADE
    SOC_DEBATE --> SOC_CONVO

    classDef crosslink stroke-dasharray: 5 5
    SOC_PWR(("→ Power & Frame Control")):::crosslink
    SOC_PSY(("→ Psychology & Self-Mastery")):::crosslink
    SOC_COMM --> SOC_PWR
    SOC_CONVO --> SOC_PSY
```

## Related Trees

- [Power & Frame Control](../power-and-frame-control/index.md) — frame
  control underlies everything in this tree.
- [Psychology & Self-Mastery](../psychology-self-mastery/index.md) —
  cognitive control is what makes conversational skill reliable under
  pressure.

- [Social Identity](../../personal/social-identity.md) — the theory of
  social identity, and defining mine.

See also: [Book List](../../BOOKLIST.md).
