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

## Sections

- [Foundations](./foundations.md) — `FIN_MATH` `FIN_ACCT` `FIN_MARKETS`
- [Valuation & Risk](./valuation-and-risk.md) — `FIN_VALUE` `FIN_PORT` `FIN_PERSONAL`
- [Frontier](./frontier.md) — `FIN_CORP` `FIN_VC` `FIN_CRYPTO`

See also: [Book List](../../BOOKLIST.md).

## Related Trees

- [Economics](../economics/index.md) — `FIN_MARKETS` builds on
  `ECON_MONEY`.
- [Statistics](../statistics/index.md) — `FIN_PORT` leans on `STAT_MULTI`.
- [Power & Frame Control](../power-and-frame-control/index.md) — `FIN_VC`
  and `PWR_MODERN` are the same subject from two angles.
