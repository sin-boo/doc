# Documentation

Source for a [Mintlify](https://mintlify.com) documentation site.

## Local development

```bash
npm i -g mint
mint dev
```

Then open [http://localhost:3000](http://localhost:3000).

## Deploy with Mintlify

1. Go to [dashboard.mintlify.com](https://dashboard.mintlify.com).
2. Create or open a docs project.
3. Connect this repository: **`sin-boo/doc`**, branch **`main`**.
4. Install the Mintlify GitHub app when prompted.

Pushes to `main` deploy automatically. Add or edit `.mdx` pages and update `docs.json` for navigation.

## Repository layout

| File | Purpose |
| --- | --- |
| `docs.json` | Site config, theme, and navigation |
| `*.mdx` | Documentation pages |
| `favicon.svg` | Browser tab icon (optional) |
