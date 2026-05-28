# Yomimono blog

Astro site published at [blog.yomimono.ai](https://blog.yomimono.ai).

## Run locally

Requires Node `>=22.12.0` and [Bun](https://bun.sh).

```sh
bun install
bun dev      # http://localhost:4321
```

Other commands:

```sh
bun build    # production build to ./dist/
bun preview  # serve the built site locally
```

## Deploy

Pushes to `main` are deployed to GitHub Pages by `.github/workflows/deploy.yaml`. No manual step required; the workflow runs `astro build` and publishes `./dist/`.

The custom domain `blog.yomimono.ai` is configured via `public/CNAME` and DNS.
