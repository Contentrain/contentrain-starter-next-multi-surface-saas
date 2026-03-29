> Source of truth: this starter is exported from the `contentrain-starters` monorepo.
> Internal starter id: `next-multi-surface-saas`.
# Contentrain Next Multi-Surface SaaS

Next.js starter for teams that need one content architecture across marketing, app shell, docs, and changelog surfaces.

## Start

```bash
pnpm install
pnpm dev
```

## Commands

```bash
pnpm check
pnpm build
pnpm start
```

## Demo routes

- `/`
- `/app`
- `/docs`
- `/guides/surface-governance`
- `/reference/content-contracts`
- `/packages/query-client`
- `/changelog/unified-surface-rollout`
- `/architecture`

## Why this starter exists

- Product marketing, dashboard UI, docs, and release notes should not drift apart
- `.contentrain/` stays local, typed, and reviewable in git
- The generated `#contentrain` SDK keeps framework code simple while preserving a real content schema
- This starter shows Contentrain as product-surface infrastructure, not only as a website CMS

Official references:

- [SDK](https://ai.contentrain.io/packages/sdk.html)
- [Docs](https://docs.contentrain.io/)
- [Studio](https://studio.contentrain.io/)
