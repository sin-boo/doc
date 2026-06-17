# Multi-user Playit docs

Source for the [Multi-user Playit](https://multi-user-playit.mintlify.app) documentation site, built with [Mintlify](https://mintlify.com).

> **Note:** If your site still opens at `neuralart.mintlify.app`, that URL comes from the Mintlify *project* name chosen in the dashboard at signup—not from this repo. See below to change it.

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

## Change the Mintlify URL (`neuralart` → `multi-user-playit`)

The `*.mintlify.app` subdomain is set in the [Mintlify dashboard](https://dashboard.mintlify.com), not in `docs.json`. Mintlify does not let you rename an existing subdomain in place.

**Recommended:** create a new Mintlify docs project with the subdomain you want, then connect the same repo:

1. Go to [mintlify.com/start](https://mintlify.com/start).
2. When asked for a site name / subdomain, use **`multi-user-playit`** (Mintlify URLs look like `multi-user-playit.mintlify.app`).
3. Connect GitHub repo **`sin-boo/doc`**, branch **`main`**.
4. After the new site deploys, delete or archive the old **neuralart** project in the dashboard.

**Alternative:** add a custom domain (e.g. `docs.yourdomain.com`) under [Custom domain](https://dashboard.mintlify.com/settings/deployment/custom-domain) and set `seo.metatags.canonical` in `docs.json`.

## Repository layout

| File | Purpose |
| --- | --- |
| `docs.json` | Site config, theme, and navigation |
| `*.mdx` | Documentation pages |
| `favicon.svg` | Browser tab icon (optional) |
