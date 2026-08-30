# Power & Frame Control

How power, status, and frames actually operate — as opposed to how they get
justified — from a single conversation up to civilizational scale.

## Tree

```mermaid
flowchart TD
    subgraph "Interpersonal Power"
        PWR_FRAME[Frame Control Fundamentals]
        PWR_BOUND[Boundaries as Power Maintenance]
        PWR_STATUS[Status Dynamics<br/>dominance & prestige]
        PWR_POLARITY[Polarity Dynamics]
        PWR_FRAME --> PWR_BOUND --> PWR_STATUS --> PWR_POLARITY
    end

    subgraph "Structural Power"
        PWR_HIER[Hierarchy & Power Structures]
        PWR_OWNER[Power & Ownership]
        PWR_DOMINANCE[Supremacy & Dominance Dynamics]
        PWR_HIER --> PWR_OWNER --> PWR_DOMINANCE
    end

    subgraph "Power at Scale"
        PWR_HISTORY[Historical Power<br/>conquest, empire, state-building]
        PWR_PROP[Propaganda & Manufactured Belief]
        PWR_MODERN[Institutional & Network Power<br/>position, brokerage, standing]
        PWR_HISTORY --> PWR_PROP --> PWR_MODERN
    end

    PWR_STATUS --> PWR_HIER
    PWR_DOMINANCE --> PWR_HISTORY

    classDef crosslink stroke-dasharray: 5 5
    PWR_SOC(("→ Social Skills")):::crosslink
    PWR_POL(("→ Political Philosophy<br/>legitimacy & ideology")):::crosslink
    PWR_PP(("→ Personal Philosophy<br/>role & the binding figure")):::crosslink
    PWR_FIN(("→ Finance<br/>capital as control")):::crosslink
    PWR_FRAME --> PWR_SOC
    PWR_PROP --> PWR_POL
    PWR_POLARITY --> PWR_PP
    PWR_MODERN --> PWR_FIN
```

## Related Trees

- [Social Skills](../social-skills/index.md) — frame control is the base
  layer under persuasion and influence.
- [Political Philosophy](../political-philosophy/index.md) — where the same
  phenomena get argued about as legitimacy rather than as mechanics.
- [Personal Philosophy](../personal-philosophy/index.md) — what occupying a
  position of power does to the person occupying it.
- [Finance](../finance/index.md) — where the allocation of capital becomes
  a form of institutional power.

- [Social Identity](../../personal/social-identity.md) — identity as the
  thing being claimed, granted, and contested.

See also: [Book List](../../BOOKLIST.md).
