# Wasmou documentation

Mintlify site for the Wasmou API (https://api.wasmou.net/api). Pages are MDX with YAML frontmatter; navigation lives in `docs.json`; the API reference is generated from `openapi.json`.

## Conventions

- Brand: Wasmou, signal yellow `#FFC400` on near-black `#0A0A0A`. Flat, no gradients.
- All amounts are in DZD. Say "your price" for catalog prices (they differ per account).
- Use the three delivery modes by name: `instant`, `key`, `manual`.
- Keep examples runnable: `https://api.wasmou.net/api/...` with an `X-Api-Key` header.
- When the API changes, update `openapi.json`, the guide that mentions it, and `changelog.mdx`.
