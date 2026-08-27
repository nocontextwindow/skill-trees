# Civil Engineering

From statics and mechanics of materials up through structural design and
the built environment.

## Skill Tree

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

## Nodes

| ID | Concept | Depends on | Status | Resources / Notes |
|---|---|---|---|---|
| CE_MATH | Engineering Math | — | [ ] | |
| CE_STATICS | Statics | CE_MATH | [ ] | |
| CE_MECH | Mechanics of Materials | CE_STATICS | [ ] | |
| CE_STRUCT | Structural Analysis & Design | CE_MECH | [ ] | |
| CE_GEOTECH | Geotechnical Engineering | CE_STRUCT | [ ] | |
| CE_FLUID | Fluid Mechanics & Hydraulics | CE_MECH | [ ] | |
| CE_ENV | Environmental Engineering | CE_FLUID | [ ] | |
| CE_TRANSPORT | Transportation Engineering | CE_GEOTECH | [ ] | |
| CE_CONST | Construction Management | CE_TRANSPORT | [ ] | |

## Related Trees

- [Mathematics](math.md) — `CE_MATH` draws on `MATH_DIFFEQ`.
- [Materials Science](materials-science.md) — `CE_MECH` is the applied
  counterpart to `MAT_MECH`.
- [Physics](physics.md) — `CE_STATICS` builds on `PH_CLASS`.
