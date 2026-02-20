# Deployment

This site is hosted on **Cloudflare Pages** (project: `shuffwebsite`).

It is NOT linked to GitHub — deployments are done manually from the local machine.

## Deploy

From the project root, run:

```sh
npx wrangler pages deploy . --project-name shuffwebsite
```

This uploads all files in the current directory to Cloudflare Pages.

## Requirements

- Node.js (for npx)
- Authenticated with Cloudflare (`npx wrangler login` if needed)
