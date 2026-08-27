# Materials Science

Why materials behave the way they do, from crystal structure up to
engineered composites and semiconductors.

## Skill Tree

```mermaid
flowchart TD
    subgraph Foundations
        MAT_CHEM[Chemistry Foundations]
        MAT_STRUCT[Atomic & Crystal Structure]
        MAT_CHEM --> MAT_STRUCT
    end

    subgraph "Thermodynamics & Mechanics"
        MAT_THERMO[Thermodynamics of Materials]
        MAT_MECH[Mechanical Properties of Materials]
        MAT_THERMO --> MAT_MECH
    end

    subgraph "Material Classes"
        MAT_METALS[Metallurgy]
        MAT_POLYMER[Polymers & Composites]
        MAT_ELEC[Electronic & Semiconductor Materials]
        MAT_NANO[Nanomaterials]
        MAT_METALS --> MAT_POLYMER --> MAT_ELEC --> MAT_NANO
    end

    MAT_STRUCT --> MAT_THERMO
    MAT_MECH --> MAT_METALS

    classDef crosslink stroke-dasharray: 5 5
    MAT_PH(("→ Physics<br/>statistical mechanics")):::crosslink
    MAT_CE(("→ Civil Engineering")):::crosslink
    MAT_THERMO --> MAT_PH
    MAT_MECH --> MAT_CE
```

## Sections

- [Foundations](./foundations.md) — `MAT_CHEM` `MAT_STRUCT`
- [Thermodynamics & Mechanics](./thermodynamics-and-mechanics.md) — `MAT_THERMO` `MAT_MECH`
- [Material Classes](./material-classes.md) — `MAT_METALS` `MAT_POLYMER` `MAT_ELEC` `MAT_NANO`

See also: [Book List](../../BOOKLIST.md).

## Related Trees

- [Physics](../physics/index.md) — `MAT_THERMO` and `MAT_ELEC` build on `PH_THERMO`
  and `PH_COND`.
- [Civil Engineering](../civil-engineering/index.md) — `MAT_MECH` underlies
  `CE_MECH`.
- [Biology](../biology/index.md) — `MAT_CHEM` overlaps with `BIO_CHEM`.
