# Imported world content source snapshot

This directory contains authored world assets, source credits, design briefs,
and world-authoring data copied from a pinned public snapshot of
[lozknowles/ElseMesh](https://github.com/lozknowles/ElseMesh/tree/95719848d5ffa4428b57c75c272483e1c2113a72).

- Source commit: `95719848d5ffa4428b57c75c272483e1c2113a72` (the base revision of [PR #6](https://github.com/lozknowles/ElseMesh/pull/6)).
- Imported: 213 files, 196,407,093 bytes (187.3 MiB).
- Inventory by top-level source path: CREDITS.md: 1 files, docs: 8 files, public: 198 files, tools: 6 files.
- `IMPORT-MANIFEST.json` records each original path, upstream Git blob ID, file size, and SHA-256.

The files are retained under their original upstream paths so Lawrence can
review and edit the content in place. This is a content-source snapshot only;
it does not prescribe ElseMesh's project or engine direction. Engine runtime
modules were excluded. These assets and briefs are not yet connected to
`world-source.json` and are not a runnable world package.

The upstream cave model and layout are byte-identical to the existing
`source/caves.glb` and `source/underneath-layout.json`, so they remain in their
existing locations instead of being duplicated here. Any future content
selection or conversion into a loadable world package should be reviewed as a
separate step, with engine changes handled separately.
