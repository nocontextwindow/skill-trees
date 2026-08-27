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

## Nodes

| ID | Concept | Depends on | Status | Resources / Notes |
|---|---|---|---|---|
| BIO_CHEM | Chemistry Foundations | — | [ ] | |
| BIO_CELL | Cell Biology | BIO_CHEM | [ ] | |
| BIO_GENETICS | Genetics & Molecular Biology | BIO_CELL | [ ] | |
| BIO_EVO | Evolutionary Biology | BIO_GENETICS | [ ] | |
| BIO_ECO | Ecology | BIO_EVO | [ ] | |
| BIO_PHYS | Physiology & Anatomy | BIO_CELL | [ ] | |
| BIO_NEURO | Neuroscience | BIO_PHYS | [ ] | |
| BIO_SYNBIO | Synthetic Biology / Biotech | BIO_NEURO, BIO_GENETICS | [ ] | |

## Related Trees

- [Statistics](statistics.md) — `BIO_EVO` (population genetics) leans on
  `STAT_EXPDESIGN`.
- [Machine Learning / AI](machine-learning-ai.md) — `BIO_NEURO` is the
  biological inspiration for `ML_NN`.
- [Materials Science](materials-science.md) — `BIO_CHEM` overlaps with
  `MAT_CHEM`.
