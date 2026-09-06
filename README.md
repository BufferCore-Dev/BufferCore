# BufferCore

BufferCore is the canonical design system and front-end framework developed and maintained by BufferCreations.

This repository contains the framework itself. It deliberately does not contain Studio code, Figma integration logic, client/flavour data or token-engine implementation.

## Architecture

BufferCore is organised into six levels:

1. Foundations
2. Layout
3. Elements
4. Components
5. Templates
6. Pages

The current active implementation is primarily in `levels/foundations`. Later levels will be built into their corresponding directories as the system develops.

## Repository boundary

Keep this repository focused on the canonical BufferCore framework source.

Related tooling belongs in sibling repositories:

- `BufferCore-Engine` — canonical token graph, parsing and validation
- `BufferCore-Figma` — Figma mappings, manifests and plugin
- `BufferCore-Studio` — BufferCore Studio application
- `BufferCore-Flavours` — reusable BufferCore Flavours

## Status

BufferCore is under active development. The current Foundations are a development baseline, not a v1.0.0 release.
