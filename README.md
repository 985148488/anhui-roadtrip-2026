# 2026 National Day Anhui Road Trip

Static travel handbook deployed with Cloudflare Workers.

## Project shape

- `public/index.html`: the complete single-file offline-capable website
- `wrangler.jsonc`: Cloudflare Workers static asset configuration
- `pnpm-lock.yaml`: reproducible dependency lockfile

## Local preview

```powershell
pnpm install --frozen-lockfile
pnpm run dev
```

## Cloudflare Workers Builds

Use these settings when connecting the GitHub repository:

- Production branch: `main`
- Build command: `pnpm install --frozen-lockfile`
- Deploy command: `pnpm run deploy`

After the first deployment, every push to `main` triggers a new deployment automatically.
