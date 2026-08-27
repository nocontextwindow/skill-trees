# Esotericism & Religion

Comparative religion, occult/hermetic traditions, and how to fold what's
useful in them into a rational, secular worldview.

## Skill Tree

```mermaid
flowchart TD
    subgraph Foundations
        ES_COMPREL[Comparative Religion<br/>Survey]
        ES_MYSTIC[Mysticism vs Rationalism]
        ES_COMPREL --> ES_MYSTIC
    end

    subgraph "Hermetic & Gnostic Traditions"
        ES_HERMET[Hermeticism & The Kybalion]
        ES_GNOSTIC[Gnosticism<br/>God vs the Devil, Dualism]
        ES_HERMET --> ES_GNOSTIC
    end

    subgraph "Occult Practice & Frameworks"
        ES_OCCULT[Occult Symbolism & Practice<br/>Wizardry]
        ES_MAGIC_ETHICS[Meta-Ethics of Magic Systems<br/>fictional/philosophical frameworks]
        ES_OCCULT --> ES_MAGIC_ETHICS
    end

    ES_SECULAR[Secular Spirituality Synthesis]

    ES_MYSTIC --> ES_HERMET
    ES_MYSTIC --> ES_OCCULT
    ES_GNOSTIC --> ES_SECULAR
    ES_MAGIC_ETHICS --> ES_SECULAR

    classDef crosslink stroke-dasharray: 5 5
    ES_PP(("→ Personal Philosophy<br/>sense of life")):::crosslink
    ES_POL(("→ Political Philosophy<br/>religion & the divine")):::crosslink
    ES_SECULAR --> ES_PP
    ES_GNOSTIC --> ES_POL
```

## Nodes

| ID | Concept | Depends on | Status | Resources / Notes |
|---|---|---|---|---|
| ES_COMPREL | Comparative Religion (survey) | — | [ ] | |
| ES_MYSTIC | Mysticism vs Rationalism | ES_COMPREL | [ ] | |
| ES_HERMET | Hermeticism & The Kybalion | ES_MYSTIC | [ ] | *The Kybalion* (1908); *Corpus Hermeticum* |
| ES_GNOSTIC | Gnosticism — God vs the Devil, Dualism | ES_HERMET | [ ] | |
| ES_OCCULT | Occult Symbolism & Practice | ES_MYSTIC | [ ] | |
| ES_MAGIC_ETHICS | Meta-Ethics of Magic Systems | ES_OCCULT | [ ] | Comparing fictional magic-system rules as ethics thought experiments |
| ES_SECULAR | Secular Spirituality Synthesis | ES_GNOSTIC, ES_MAGIC_ETHICS | [ ] | Ties back to sense of life / a useful, non-literal concept of the divine |

## Related Trees

- [Personal Philosophy](personal-philosophy.md) — `ES_SECULAR` feeds back
  into `PP_SENSE` (sense of life).
- [Political Philosophy](political-philosophy.md) — `ES_GNOSTIC` connects to
  `POL_DIVINE` and `POL_THEOCRACY`.
