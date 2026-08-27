# Power & Frame Control

How power, status, and frames actually work — from interpersonal dynamics
up to civilizational-scale power structures.

## Skill Tree

```mermaid
flowchart TD
    subgraph "Interpersonal Power"
        PWR_FRAME[Frame Control Fundamentals]
        PWR_BOUND[Boundaries as Power Maintenance]
        PWR_STATUS[Status Dynamics]
        PWR_POLARITY[Masculinity / Femininity<br/>Polarity Dynamics]
        PWR_FRAME --> PWR_BOUND --> PWR_STATUS --> PWR_POLARITY
    end

    subgraph "Structural Power"
        PWR_HIER[Hierarchy & Power Structures]
        PWR_OWNER[Power & Ownership]
        PWR_DOMINANCE[Supremacy & Dominance Dynamics]
        PWR_HIER --> PWR_OWNER --> PWR_DOMINANCE
    end

    subgraph "Power at Scale"
        PWR_HISTORY[Historical Power<br/>Conquest, Colonization, Civilization-Building]
        PWR_PROP[Propaganda & Brainwashing Techniques]
        PWR_MODERN[Modern Institutional Power<br/>Network & Venture Power]
        PWR_HISTORY --> PWR_PROP --> PWR_MODERN
    end

    PWR_STATUS --> PWR_HIER
    PWR_DOMINANCE --> PWR_HISTORY

    classDef crosslink stroke-dasharray: 5 5
    PWR_SOC(("→ Social Skills")):::crosslink
    PWR_POL(("→ Political Philosophy<br/>frames of power")):::crosslink
    PWR_PP(("→ Personal Philosophy<br/>the patriarch")):::crosslink
    PWR_FIN(("→ Finance<br/>venture capital & network power")):::crosslink
    PWR_FRAME --> PWR_SOC
    PWR_PROP --> PWR_POL
    PWR_POLARITY --> PWR_PP
    PWR_MODERN --> PWR_FIN
```

## Sections

- [Interpersonal Power](./interpersonal-power.md) — `PWR_FRAME` `PWR_BOUND` `PWR_STATUS` `PWR_POLARITY`
- [Structural Power](./structural-power.md) — `PWR_HIER` `PWR_OWNER` `PWR_DOMINANCE`
- [Power at Scale](./power-at-scale.md) — `PWR_HISTORY` `PWR_PROP` `PWR_MODERN`

See also: [Book List](../../BOOKLIST.md).

## Related Trees

- [Social Skills](../social-skills/index.md) — frame control is the base
  layer under persuasion and influence.
- [Political Philosophy](../political-philosophy/index.md) — propaganda
  technique is the applied side of "frames of power."
- [Personal Philosophy](../personal-philosophy/index.md) — polarity dynamics
  connect to the patriarch archetype.
- [Finance](../finance/index.md) — modern institutional power and venture
  capital are the same subject from two angles.
