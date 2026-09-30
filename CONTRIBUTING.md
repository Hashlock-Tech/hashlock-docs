# Contributing

- Every claim must be traceable to the code (`hashlock-markets`, `hashlock-mcp`, `hashlock-sdk`) or the
  live OpenAPI spec. Do not add numbers, limits or endpoints that the sources do not state.
- Endpoint details live in the OpenAPI spec, not in MDX. Fix the spec in the API, not here.
- Plain, short sentences. Code samples in curl and TypeScript (viem for EVM signing).
- Run `npx mint validate` and `npx mint broken-links` before opening a PR.
