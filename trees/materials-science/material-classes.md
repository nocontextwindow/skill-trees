# Materials Science — Material Classes

[← Back to index](./index.md)

---

## Metallurgy (`MAT_METALS`)

Metallurgy applies the thermodynamics and mechanics of the previous section
to specific alloy systems — steel, aluminum, titanium, nickel superalloys —
where the practical craft is controlling microstructure through alloying
and heat treatment to hit a target property (hardness, toughness, corrosion
resistance) without sacrificing the others. The iron-carbon phase diagram
and the martensitic transformation it enables (quenching austenite to
produce a hard, brittle phase, then tempering it back toward toughness) is
the canonical worked example every metallurgist learns first. Physical
(microstructure-property) metallurgy and process (extraction, casting,
forming) metallurgy are somewhat separate subfields worth distinguishing.

**Status:** [ ]

**Resources:**
- Donald Askeland & Wendelin Wright, *The Science and Engineering of
  Materials*
- ASM International, *ASM Handbook* (the field's reference standard)

---

## Polymers & Composites (`MAT_POLYMER`)

Polymers behave nothing like metals or ceramics mechanically because their
long-chain molecular structure introduces viscoelasticity — response
depends on both load and time, which is why a polymer can be rubbery at one
loading rate and glassy at another. Composites (fiberglass, carbon-fiber
epoxy) combine a strong, stiff reinforcement phase with a tougher matrix to
get a property combination neither material offers alone; the rule of
mixtures gives a first-order estimate of composite properties from the
constituents' properties and volume fractions, though real composites
deviate from it in instructive ways (fiber orientation, interfacial
bonding). Composite design is as much about the interface as the
constituents.

**Status:** [ ]

**Resources:**
- Paul Painter & Michael Coleman, *Fundamentals of Polymer Science*
- Derek Hull & T.W. Clyne, *An Introduction to Composite Materials*

---

## Electronic & Semiconductor Materials (`MAT_ELEC`)

Band theory — the idea that electron energy levels in a solid form
continuous bands separated by gaps — is what distinguishes conductors,
insulators, and semiconductors, and it's the direct bridge from atomic
bonding to device physics. Doping a semiconductor with donor or acceptor
impurities lets you engineer carrier concentration and type (n- or p-type),
and putting an n-type and p-type region together makes a p-n junction, the
building block of diodes and transistors. Dielectric and magnetic materials
run on related but distinct physics (polarization response, spin ordering)
and underlie capacitors, memory, and sensors.

**Status:** [ ]

**Resources:**
- Safa Kasap, *Principles of Electronic Materials and Devices*
- S.M. Sze, *Semiconductor Devices: Physics and Technology*

---

## Nanomaterials (`MAT_NANO`)

Below roughly 100 nanometers, materials start showing size-dependent
properties that bulk thermodynamics doesn't predict: quantum confinement
shifts the electronic band structure of semiconductor nanocrystals (the
basis of quantum dots), and surface-to-volume ratio gets large enough that
surface effects dominate bulk ones (why gold nanoparticles are chemically
reactive and colored, unlike bulk gold). Fabrication (top-down lithography
versus bottom-up self-assembly) and characterization (electron microscopy,
AFM) are as central to the field as the underlying physics, since most
nanomaterial properties are useless without the ability to make and verify
structures at that scale reliably.

**Status:** [ ]

**Resources:**
- Guozhong Cao & Ying Wang, *Nanostructures and Nanomaterials*
- Charles Poole & Frank Owens, *Introduction to Nanotechnology*
