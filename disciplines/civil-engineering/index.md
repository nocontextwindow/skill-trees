# Civil Engineering

From statics and mechanics of materials up through structural design and
the built environment.

The structure below follows the discipline's own progression: a shared
analytical foundation, then the four sub-disciplines that branch off it,
ending in how a design actually gets built.

## Tree

```mermaid
flowchart TD
    subgraph Foundations
        CE_MATH[Engineering Math]
        CE_STATICS[Statics]
        CE_MECH[Mechanics of Materials]
        CE_MATH --> CE_STATICS --> CE_MECH
    end

    subgraph "Structural & Geotechnical"
        CE_STRUCT[Structural Analysis & Design]
        CE_GEOTECH[Geotechnical Engineering]
        CE_STRUCT --> CE_GEOTECH
    end

    subgraph "Fluids & Environment"
        CE_FLUID[Fluid Mechanics & Hydraulics]
        CE_ENV[Environmental Engineering]
        CE_FLUID --> CE_ENV
    end

    subgraph "Delivery"
        CE_TRANSPORT[Transportation Engineering]
        CE_CONST[Construction Management]
        CE_TRANSPORT --> CE_CONST
    end

    CE_MECH --> CE_STRUCT
    CE_MECH --> CE_FLUID
    CE_GEOTECH --> CE_TRANSPORT

    classDef crosslink stroke-dasharray: 5 5
    CE_MATH_LINK(("→ Mathematics")):::crosslink
    CE_MAT(("→ Materials Science")):::crosslink
    CE_MATH --> CE_MATH_LINK
    CE_MECH --> CE_MAT
```

## Related Trees

- [Mathematics](../math/index.md) — `CE_MATH` draws on `MATH_DIFFEQ`.
- [Materials Science](../materials-science/index.md) — `CE_MECH` is the
  applied counterpart to `MAT_MECH`.
- [Physics](../physics/index.md) — `CE_STATICS` builds on `PH_CLASS`.

See also: [Book List](../../BOOKLIST.md).
