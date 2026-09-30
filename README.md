# Hashlock Markets docs

Mintlify source for the Hashlock Markets developer documentation.

## Run locally

```sh
npx mint dev          # preview at http://localhost:3000
npx mint validate     # strict build check
npx mint broken-links # internal link check
```

## Layout

- `docs.json` — site config and navigation
- `index.mdx`, `quickstart.mdx` — get started
- `concepts/`, `guides/`, `agents/` — documentation pages
- `api-reference/introduction.mdx` — API overview; endpoint pages are generated from
  `api-reference/openapi.json`, a copy of the API's own spec with the production server only.
  Refresh it from the API whenever endpoints change, and keep `servers` production-only.
