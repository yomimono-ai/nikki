# CLAUDE.md

Notes for Claude Code working in this repo.

## What this is

Astro static site for the Yomimono blog, published to GitHub Pages at `blog.yomimono.ai`. See `README.md` for how to run and deploy.

## Stack

- Astro 6 (static output) with `@astrojs/mdx`, `@astrojs/sitemap`, `@astrojs/rss`
- Bun for install/dev/build (Node `>=22.12.0`)
- Plain CSS (no Tailwind/PostCSS) — global tokens in `src/styles/global.css`

## Layout

- `src/pages/` — Astro routes. `index.astro` is the home, `[...slug].astro` renders blog posts, `rss.xml.js` builds the feed. Files prefixed with `_` (e.g. `_home.astro`, `_about.astro`) are not routed.
- `src/layouts/BlogPost.astro` — wraps individual posts.
- `src/components/` — `Header.astro`, `Footer.astro`, `BaseHead.astro`, `HeaderLink.astro`, `FormattedDate.astro`.
- `src/content/blog/` — Markdown/MDX posts. Schema lives in `src/content.config.ts` (frontmatter: `title`, `description`, `pubDate`, optional `updatedDate`, `heroImage`, `draft`).
- `src/styles/global.css` — color tokens (`--ink`, `--pink`, `--bg`, `--rule`, etc.), typography (`--serif-display`), and shared rules.
- `public/` — static assets. `CNAME` pins the custom domain; favicons live alongside it and in `public/icons/`.

## Conventions

- Container widths: header uses `max-width: 1080px`; main content/footer inner uses `max-width: 720px`. Keep these aligned when adding chrome.
- Brand pink is `var(--pink)` (`#ee5d7a`); the logo SVG fill is intentionally near-identical.
- Drafts: set `draft: true` in post frontmatter to hide a post; remove it to publish.

## Deploy

GitHub Actions workflow `.github/workflows/deploy.yaml` builds and publishes on push to `main`. No manual steps.
