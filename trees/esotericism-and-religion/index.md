# Esotericism & Religion

What religions and esoteric traditions are actually doing — as claims about
the world, as practices, and as social machinery — and what a secular
worldview has to account for or replace.

The structure is the comparative study of religion: survey first, then the
specific traditions, then the question of practice, then what carries over.
Particular systems and personal enthusiasms are open questions *inside*
these branches, not branches of their own.

## Tree

```mermaid
flowchart TD
    subgraph Foundations
        ES_COMPREL[Comparative Religion]
        ES_MYSTIC[Mysticism vs Rationalism]
        ES_COMPREL --> ES_MYSTIC
    end

    subgraph "Hermetic & Gnostic Traditions"
        ES_HERMET[Hermeticism<br/>correspondence & the microcosm]
        ES_GNOSTIC[Gnosticism & Dualism<br/>a defective world]
        ES_HERMET --> ES_GNOSTIC
    end

    subgraph "Symbol & Practice"
        ES_OCCULT[Occult Symbolism & Practice]
        ES_RITUAL[Ritual, Symbol & Efficacy]
        ES_OCCULT --> ES_RITUAL
    end

    ES_SECULAR[Secular Spirituality Synthesis]

    ES_MYSTIC --> ES_HERMET
    ES_MYSTIC --> ES_OCCULT
    ES_GNOSTIC --> ES_SECULAR
    ES_RITUAL --> ES_SECULAR

    classDef crosslink stroke-dasharray: 5 5
    ES_PP(("→ Personal Philosophy<br/>sense of life")):::crosslink
    ES_POL(("→ Political Philosophy<br/>religion & political order")):::crosslink
    ES_SECULAR --> ES_PP
    ES_GNOSTIC --> ES_POL
```

## Related Trees

- [Personal Philosophy](../personal-philosophy/index.md) — secular
  spirituality feeds back into sense of life.
- [Political Philosophy](../political-philosophy/index.md) — what religion
  is doing that political order depends on.

See also: [Book List](../../BOOKLIST.md).
