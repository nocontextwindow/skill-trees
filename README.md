# Skill Trees

A personal map of concepts to learn and positions to work out. Each tree is
a folder with an `index.md` holding the map — a Mermaid diagram plus links.
Articles get written by hand, per topic, only where a topic warrants one.

## Trees

**Philosophy & Mind**
- [Personal Philosophy](trees/personal-philosophy/index.md)
- [Political Philosophy](trees/political-philosophy/index.md)
- [Epistemology](trees/epistemology/index.md)
- [Esotericism & Religion](trees/esotericism-and-religion/index.md)
- [Psychology & Self-Mastery](trees/psychology-self-mastery/index.md)

**Power & Social**
- [Power & Frame Control](trees/power-and-frame-control/index.md)
- [Social Skills](trees/social-skills/index.md)

**Hard Sciences**
- [Physics](trees/physics/index.md)
- [Biology](trees/biology/index.md)
- [Mathematics](trees/math/index.md)
- [Statistics](trees/statistics/index.md)
- [Materials Science](trees/materials-science/index.md)

**Applied / Quant**
- [Machine Learning / AI](trees/machine-learning-ai/index.md)
- [Civil Engineering](trees/civil-engineering/index.md)
- [Economics](trees/economics/index.md)
- [Finance](trees/finance/index.md)

**Personal**
- [Self-Map](personal/self-map.md) — personality, drives, proclivities,
  failure modes.
- [Social Identity](personal/social-identity.md) — the theory of social
  identity, and defining mine.

**Reading**
- [Book List](BOOKLIST.md)

## Structure

```
trees/<tree>/
  index.md            the map: blurb, Mermaid diagram, related trees
  articles/           articles I write, once a topic is worth one
    <topic>.md
personal/             documents about me rather than about a subject
BOOKLIST.md           everything captured, by area, with read status
```

A tree is a **map** — the diagram is the point. It shows how topics relate
and how deep the domain goes.

**Articles are written by hand, when a topic earns one.** They are not
generated up front for every node — a tree with an article per node is a
pile of encyclopedia entries nobody asked for. Most trees have no
`articles/` folder at all, and that's the normal state. When one gets
written, add it to the index under an `## Articles` heading.

Right now only [Personal Philosophy](trees/personal-philosophy/index.md)
and [Political Philosophy](trees/political-philosophy/index.md) have
articles, and those are **question placeholders** — the questions to work
through, with blank space for my answers.

## Article format

1. **Framing** — short. Enough to know why the questions below are the
   questions.
2. **Open questions** — the real content, stated as questions rather than
   as a syllabus.
3. **Notes** — empty. Where working-out goes.
4. **Resources** — **empty by default.** Only things actually read get
   added, by hand. Nothing gets pre-populated with recommendations — an
   unread suggestion in a resource list is noise that looks like progress.

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

1. `trees/<name>/index.md` with the blurb and diagram. That's the whole
   tree — no articles until one is actually worth writing.
2. Add it to the list above and link it both ways from any tree it
   overlaps.
