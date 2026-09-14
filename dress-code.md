# Dress Code

A local wardrobe workspace that turns shopping screenshots into a reviewable clothing collection.

## Workflow

Paste or drop a shopping screenshot → save to the persistent local inbox → ask Codex to process pending items → review extracted garments and optional modeled previews → organize approved wardrobe items.

The web importer queues files without requiring an API key. AI processing is a separate user-initiated Codex workflow, not an automatic model service inside the web app. Optional try-on generation uses a user-provided reference image; that image is not included in this showcase.

## Engineering

React and Vite frontend; local filesystem inbox and JSON library; bundled Codex import and outfit-generation skills. The customized workflow recognizes online finds and preserves screenshot provenance while instructing extraction to ignore shopping-page UI and incidental items.

## Attribution

Customized from [tandpfun/wardrobe](https://github.com/tandpfun/wardrobe). The original wardrobe pipeline is upstream work; the screenshot-import and Codex inbox adaptations are the portfolio contribution. Preserve the upstream MIT license when distributing source.

## Verification scope

The local README confirms the inbox workflow. The supplied development conversation reports successful builds and inbox lifecycle checks. This showcase has not yet independently rerun those checks or exercised AI generation.
