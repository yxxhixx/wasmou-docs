# Wasmou documentation

Source of the Wasmou API documentation, built with [Mintlify](https://mintlify.com).

```bash
npm i -g mint
mint dev        # preview at http://localhost:3000
mint broken-links
```

Pushing to `main` publishes the site (GitHub app connected in the Mintlify dashboard).

- `docs.json`: theme, navigation
- `openapi.json`: API reference source
- `*.mdx`, `concepts/`, `guides/`: pages
