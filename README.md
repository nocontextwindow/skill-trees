# Skill Trees

Two separate things, kept apart on purpose:

- **`self/`** — working out my own positions and capabilities. The output
  is *my answer*.
- **`disciplines/`** — bodies of knowledge that exist independently of me.
  The output is *understanding the field*.

Each tree is a folder with an `index.md` holding the map — a Mermaid
diagram plus links. Articles get written by hand, per topic, only where a
topic warrants one.

## Self

Positions and capabilities. Personal documents sit at the top of this
section; the trees under it are where the thinking gets done.

- [Self-Map](self/self-map.md) — personality, drives, proclivities, failure modes.
- [Social Identity](self/social-identity.md) — the theory, and defining mine.

**Worldview**
- [Personal Philosophy](self/personal-philosophy/index.md)
- [Political Philosophy](self/political-philosophy/index.md)
- [Epistemology](self/epistemology/index.md)
- [Esotericism & Religion](self/esotericism-and-religion/index.md)

**Practice**
- [Psychology & Self-Mastery](self/psychology-self-mastery/index.md)
- [Power & Frame Control](self/power-and-frame-control/index.md)
- [Social Skills](self/social-skills/index.md)

## Disciplines

Subjects to learn. Nothing here is about me.

**Formal**
- [Mathematics](disciplines/math/index.md)
- [Statistics](disciplines/statistics/index.md)

**Natural sciences**
- [Physics](disciplines/physics/index.md)
- [Biology](disciplines/biology/index.md)
- [Materials Science](disciplines/materials-science/index.md)

**Applied**
- [Machine Learning / AI](disciplines/machine-learning-ai/index.md)
- [Civil Engineering](disciplines/civil-engineering/index.md)
- [Economics](disciplines/economics/index.md)
- [Finance](disciplines/finance/index.md)

## Reference

- [Book List](BOOKLIST.md)
- [Terms](TERMS.md)

## Structure

```
self/                 my positions and capabilities
  self-map.md
  social-identity.md
  <tree>/
    index.md          the map: blurb, Mermaid diagram, related trees
    articles/         articles I write, once a topic is worth one
disciplines/          subjects that exist independently of me
  <tree>/
    index.md
    articles/
BOOKLIST.md           everything captured, by area, with read status
TERMS.md              vocabulary, one line each
```

The split is the point. `self/` is for arriving at an answer I hold;
`disciplines/` is for learning something true whether I engage with it or
not. A tree drifting across that line is in the wrong directory.

A tree is a **map** — the diagram is the point. It shows how topics relate
and how deep the domain goes.

**Articles are written by hand, when a topic earns one.** They are not
generated up front for every node — a tree with an article per node is a
pile of encyclopedia entries nobody asked for. Most trees have no
`articles/` folder at all, and that's the normal state. When one gets
written, add it to the index under an `## Articles` heading.

Right now only [Personal Philosophy](self/personal-philosophy/index.md)
and [Political Philosophy](self/political-philosophy/index.md) have
articles, and those are **question placeholders** — the questions to work
through, with blank space for my answers.

## Article format

Lightweight. One sentence defining the thing, then:

1. **Questions** — the point of the file.
2. **Challenges & perspectives** — the standard objections and rival
   positions, one line each. Named positions, not essays.
3. **Notes** — empty. Where my answers go.
4. **Resources** — **empty by default.** Only things actually read get
   added, by hand.

No framing essays, no prose explaining the topic to me.

## Conventions

- **Trees are built on the structure of the domain**, not on whatever
  happened to be interesting the day the tree was made. Specific interests,
  positions, and pet topics belong *inside* the relevant branch — not as
  their own top-level box. If a topic can't be placed under an existing
  branch, that's a sign the branch structure is wrong, not that the topic
  needs its own box.
- **Open questions over checklists.** These are for working something out,
  not for clearing a syllabus. Prefer a question with no answer yet to a
  node with a definition already filled in.
- **Node IDs are prefixed** per tree (`PP_`, `POL_`, `EP_`, ...) so IDs
  never collide, and each article names its own ID so it's findable from
  the diagram.
- **Diagrams are vertical.** `flowchart TD`, chained top-to-bottom in narrow
  columns, branching kept to 2–3 wide. The arrow means "comes next in a
  sensible order," not always "strictly requires."
- **No capstones**, no synthetic "final project" nodes.
- **Cross-tree links** are plain markdown links (GitHub's Mermaid doesn't
  reliably support in-diagram links), in a "Related Trees" section, plus a
  dashed circle node in the diagram where one tree is a deep dive off
  another.
- **Status values**: `[ ]` not started, `[~]` in progress, `[x]` done.

## Adding a tree

1. Decide which side it belongs on — is the output my position, or
   understanding a field? Then `self/<name>/index.md` or
   `disciplines/<name>/index.md`, with the blurb and diagram. That's the
   whole tree; no articles until one is worth writing.
2. Add it to the list above and link it both ways from any tree it
   overlaps.
