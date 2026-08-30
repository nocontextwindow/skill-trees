# Economics

How choice, coordination, and money actually work — and how much of what
the field claims to know is settled versus contested. The structure below
is the conventional construction of the subject: individual choice, then
strategic interaction, then aggregates and money, then the politics that
economic analysis usually assumes away.

Specific positions and current arguments live as open questions inside
the branch they belong to, not as branches of their own.

## Tree

```mermaid
flowchart TD
    subgraph Foundations
        ECON_MICRO[Microeconomics]
        ECON_MACRO[Macroeconomics]
        ECON_MICRO --> ECON_MACRO
    end

    subgraph "Behavior & Strategy"
        ECON_GAME[Game Theory]
        ECON_BEHAV[Behavioral Economics]
        ECON_GAME --> ECON_BEHAV
    end

    subgraph "Money & the World"
        ECON_MONEY[Money & Monetary Policy]
        ECON_TRADE[International Trade]
        ECON_DEV[Development Economics]
        ECON_MONEY --> ECON_TRADE --> ECON_DEV
    end

    ECON_POLECON[Political Economy]

    ECON_MICRO --> ECON_GAME
    ECON_MACRO --> ECON_MONEY
    ECON_DEV --> ECON_POLECON

    classDef crosslink stroke-dasharray: 5 5
    ECON_STAT(("→ Statistics")):::crosslink
    ECON_FIN(("→ Finance")):::crosslink
    ECON_POL(("→ Political Philosophy")):::crosslink
    ECON_MACRO --> ECON_STAT
    ECON_MONEY --> ECON_FIN
    ECON_POLECON --> ECON_POL
```

## Related Trees

- [Statistics](../statistics/index.md) — the inference machinery every
  empirical claim in this tree depends on.
- [Finance](../finance/index.md) — where money and asset prices get
  treated as a subject in their own right.
- [Political Philosophy](../political-philosophy/index.md) — the
  questions about property and distribution that economics inherits
  rather than answers.

See also: [Book List](../../BOOKLIST.md).
