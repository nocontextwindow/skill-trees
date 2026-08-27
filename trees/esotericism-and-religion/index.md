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

## Sections

- [Foundations](./foundations.md) — `ES_COMPREL` `ES_MYSTIC`
- [Hermetic & Gnostic Traditions](./hermetic-and-gnostic-traditions.md) — `ES_HERMET` `ES_GNOSTIC`
- [Occult Practice & Frameworks](./occult-practice-and-frameworks.md) — `ES_OCCULT` `ES_MAGIC_ETHICS`
- [Secular Spirituality](./secular-spirituality.md) — `ES_SECULAR`

See also: [Book List](../../BOOKLIST.md).

## Related Trees

- [Personal Philosophy](../personal-philosophy/index.md) — Secular
  Spirituality feeds back into Sense of Life.
- [Political Philosophy](../political-philosophy/index.md) — Gnosticism
  connects to Religion & the Divine.
