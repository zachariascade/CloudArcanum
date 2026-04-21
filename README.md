# Cloud Arcanum

Cloud Arcanum is the MTG-focused content, catalog, browsing, printing, and deckbuilding product.

This repository is intentionally standalone. It owns:

- canonical cards, decks, sets, and universes
- the Arcanum API and web app
- Biblical content pipelines and card assets
- the small shared schema layer in `src/domain/`

It does not own combat simulation, sessions, replay, or battle UI.

## Quick Start

```bash
npm install
npm run dev
```

## Core Commands

- `npm run dev`
- `npm run dev:api`
- `npm run dev:web`
- `npm run build`
- `npm run check`
- `npm run test`
- `npm run validate`

## Repository Layout

```text
apps/
  cloud-arcanum-api/
  cloud-arcanum-web/
data/
images/cards/
scripts/
src/
  biblical/
  cloud-arcanum/
  domain/
tests/
docs/
```

## Docs

- [Cloud Arcanum Docs Index](./docs/arcanum/DOCS_INDEX.md)
- [Cloud Arcanum Extraction Inventory](./docs/planning/CLOUD_ARCANUM_REPO_EXTRACTION_INVENTORY.md)
- [Cloud Arcanum Extraction Plan](./docs/planning/CLOUD_ARCANUM_REPO_EXTRACTION_PLAN.md)
