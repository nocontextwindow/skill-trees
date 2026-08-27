# Biology

From chemistry up through cells, genetics, and systems, to the
neuroscience/biotech frontier.

## Skill Tree

```mermaid
flowchart TD
    subgraph Foundations
        BIO_CHEM[Chemistry Foundations]
        BIO_CELL[Cell Biology]
        BIO_CHEM --> BIO_CELL
    end

    subgraph "Genetics & Evolution"
        BIO_GENETICS[Genetics & Molecular Biology]
        BIO_EVO[Evolutionary Biology]
        BIO_ECO[Ecology]
        BIO_GENETICS --> BIO_EVO --> BIO_ECO
    end

    subgraph "Systems & Frontier"
        BIO_PHYS[Physiology & Anatomy]
        BIO_NEURO[Neuroscience]
        BIO_SYNBIO[Synthetic Biology / Biotech]
        BIO_PHYS --> BIO_NEURO --> BIO_SYNBIO
    end

    BIO_CELL --> BIO_GENETICS
    BIO_CELL --> BIO_PHYS
    BIO_GENETICS --> BIO_SYNBIO

    classDef crosslink stroke-dasharray: 5 5
    BIO_STAT(("→ Statistics<br/>population genetics")):::crosslink
    BIO_ML(("→ ML/AI<br/>neural nets")):::crosslink
    BIO_EVO --> BIO_STAT
    BIO_NEURO --> BIO_ML
```

## Sections

- [Foundations](./foundations.md) — `BIO_CHEM` `BIO_CELL`
- [Genetics & Evolution](./genetics-and-evolution.md) — `BIO_GENETICS` `BIO_EVO` `BIO_ECO`
- [Systems & Frontier](./systems-and-frontier.md) — `BIO_PHYS` `BIO_NEURO` `BIO_SYNBIO`

See also: [Book List](../../BOOKLIST.md).

## Related Trees

- [Statistics](../statistics/index.md) — `BIO_EVO` (population genetics) leans on
  `STAT_EXPDESIGN`.
- [Machine Learning / AI](../machine-learning-ai/index.md) — `BIO_NEURO` is the
  biological inspiration for `ML_NN`.
- [Materials Science](../materials-science/index.md) — `BIO_CHEM` overlaps
  with `MAT_CHEM`.
