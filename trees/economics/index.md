# Economics

Micro and macro fundamentals up through game theory, money, and political
economy.

## Skill Tree

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

## Sections

- [Foundations](./foundations.md) — `ECON_MICRO` `ECON_MACRO`
- [Behavior & Strategy](./behavior-and-strategy.md) — `ECON_GAME` `ECON_BEHAV`
- [Money & the World](./money-and-the-world.md) — `ECON_MONEY` `ECON_TRADE` `ECON_DEV` `ECON_POLECON`

See also: [Book List](../../BOOKLIST.md).

## Related Trees

- [Statistics](../statistics/index.md) — `ECON_MACRO` modeling leans on
  `STAT_MULTI`.
- [Finance](../finance/index.md) — `ECON_MONEY` underlies `FIN_MARKETS`.
- [Political Philosophy](../political-philosophy/index.md) — `ECON_POLECON`
  connects to `POL_FACTIONS`.
