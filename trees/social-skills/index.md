# Social Skills

Communication, persuasion, and reading a room — the practical layer sitting
on top of frame control and psychology.

The structure runs from getting understood, to moving people, to the
standing presence that makes both easier. Specific tactics and scenes are
open questions *inside* these branches, not branches of their own.

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

## Articles

**Foundation**
- [Communication Fundamentals](articles/communication-fundamentals.md) — `SOC_COMM`
- [Boundaries](articles/boundaries.md) — `SOC_BOUND`
- [Storytelling & Narrative Framing](articles/storytelling-and-framing.md) — `SOC_STORY`

**Persuasion**
- [Persuasion & Rhetoric](articles/persuasion-and-rhetoric.md) — `SOC_PERSUADE`
- [Influence](articles/influence.md) — `SOC_INFLUENCE`
- [Debate](articles/debate.md) — `SOC_DEBATE`

**Presence**
- [Conversational Skill & Charisma](articles/charisma-and-conversation.md) — `SOC_CONVO`
- [Networking](articles/networking.md) — `SOC_NETWORK`

## Related Trees

- [Power & Frame Control](../power-and-frame-control/index.md) — frame
  control underlies everything in this tree.
- [Psychology & Self-Mastery](../psychology-self-mastery/index.md) —
  cognitive control is what makes conversational skill reliable under
  pressure.

See also: [Book List](../../BOOKLIST.md).
