# Finance

From accounting and markets through valuation and portfolio theory, out to
crypto and venture capital.

## Skill Tree

```mermaid
flowchart TD
    subgraph Foundations
        FIN_MATH[Quantitative Foundations]
        FIN_ACCT[Accounting Fundamentals]
        FIN_MARKETS[Financial Markets & Instruments]
        FIN_MATH --> FIN_ACCT --> FIN_MARKETS
    end

    subgraph "Valuation & Risk"
        FIN_VALUE[Valuation<br/>DCF, comparables]
        FIN_PORT[Portfolio Theory & Risk]
        FIN_PERSONAL[Personal Finance & Wealth Building]
        FIN_VALUE --> FIN_PORT --> FIN_PERSONAL
    end

    subgraph "Frontier"
        FIN_CORP[Corporate Finance]
        FIN_VC[Venture Capital & Network Power<br/>a16z model]
        FIN_CRYPTO[Cryptocurrency & Digital Assets]
        FIN_CORP --> FIN_VC --> FIN_CRYPTO
    end

    FIN_MARKETS --> FIN_VALUE
    FIN_MARKETS --> FIN_CORP

    classDef crosslink stroke-dasharray: 5 5
    FIN_ECON(("→ Economics")):::crosslink
    FIN_STAT(("→ Statistics")):::crosslink
    FIN_PWR(("→ Power & Frame Control")):::crosslink
    FIN_MARKETS --> FIN_ECON
    FIN_PORT --> FIN_STAT
    FIN_VC --> FIN_PWR
```

## Nodes

| ID | Concept | Depends on | Status | Resources / Notes |
|---|---|---|---|---|
| FIN_MATH | Quantitative Foundations | — | [ ] | |
| FIN_ACCT | Accounting Fundamentals | FIN_MATH | [ ] | |
| FIN_MARKETS | Financial Markets & Instruments | FIN_ACCT | [ ] | |
| FIN_VALUE | Valuation (DCF, comparables) | FIN_MARKETS | [ ] | |
| FIN_PORT | Portfolio Theory & Risk | FIN_VALUE | [ ] | |
| FIN_PERSONAL | Personal Finance & Wealth Building | FIN_PORT | [ ] | |
| FIN_CORP | Corporate Finance | FIN_MARKETS | [ ] | |
| FIN_VC | Venture Capital & Network Power | FIN_CORP | [ ] | Marc Andreessen, "It's Time to Build"; a16z's American Dynamism thesis |
| FIN_CRYPTO | Cryptocurrency & Digital Assets | FIN_VC | [ ] | |

## Related Trees

- [Economics](economics.md) — `FIN_MARKETS` builds on `ECON_MONEY`.
- [Statistics](statistics.md) — `FIN_PORT` leans on `STAT_MULTI`.
- [Power & Frame Control](power-and-frame-control.md) — `FIN_VC` and
  `PWR_MODERN` are the same subject from two angles.
