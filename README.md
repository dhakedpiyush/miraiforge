# MiraiForge Technologies — Website

Marketing site for **MiraiForge Technologies**, a Salesforce consulting & implementation company.

Built with [Astro](https://astro.build/) using the *Seal Swirl* brand system
(Forge Ink / Cold Paper / Steel Blue · Sora + JetBrains Mono + Noto Serif JP).

## Develop

```bash
npm install
npm run dev      # http://localhost:4321
```

## Build

```bash
npm run build    # static output → dist/
npm run preview  # preview the production build locally
```

## Deploy

Hosted on **Netlify**. Build settings live in `netlify.toml`
(`npm run build` → publish `dist/`). Pushing to `main` triggers a deploy.

## Structure

```
src/
├── styles/global.css     brand tokens & shared utilities
├── components/           Logo, Nav, Footer
├── layouts/Base.astro    fonts, meta, page shell
└── pages/index.astro     landing page
public/favicon.svg        the seal mark
```

---
© 2026 MiraiForge Technologies · 未来を鍛える
