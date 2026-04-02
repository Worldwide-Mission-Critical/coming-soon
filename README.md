# Coming Soon — Worldwide Mission Critical

A simple static "Coming Soon" landing page for Worldwide Mission Critical.

## Deploying to Cloudflare Pages

Requires [Wrangler CLI](https://developers.cloudflare.com/workers/wrangler/install-and-update/) and a Cloudflare account.

### First-time setup

```bash
npx wrangler login
npx wrangler pages project create coming-soon --production-branch=main
```

### Deploy

```bash
npx wrangler pages deploy . --project-name=coming-soon --commit-dirty=true
```

The site will be available at `https://coming-soon-25r.pages.dev`. To use a custom domain, configure it in the Cloudflare dashboard under **Pages > coming-soon > Custom domains**.
