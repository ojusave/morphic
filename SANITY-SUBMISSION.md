# Sanity submission — Morphic on Render

Paste these values into the [Sanity Templates studio](https://www.sanity.io/@oXAmmqIVT/studio/8b41d55c7325153fdba18d1b/production/structure/templates;templates).

## Prerequisites

- [ ] `render-examples/morphic-render-template` exists with `is_template: true`
- [ ] `render.yaml` on the **default branch** (one-click deploy ignores `&branch=`)
- [ ] `render blueprints validate render.yaml` passes
- [ ] Smoke deploy from a fresh template fork reaches **Live**
- [ ] Upload `assets/hero.png` (1600×900 recommended; use `assets/home.png` until a dedicated hero is exported)

## Sanity fields

| Field | Value |
|-------|--------|
| **Title** | `Morphic on Render` |
| **Slug** | `morphic-render-template` |
| **Description** | Deploy Morphic on Render with one click: AI search with a generative UI, Exa neural search, managed PostgreSQL, and Docker build from the upstream app. |
| **GitHub Repository** | `https://github.com/render-examples/morphic-render-template` |
| **Demo URL** | `https://morphic-us8x.onrender.com/` |
| **Image** | Upload `assets/hero.png` |
| **Stack** | `docker`, `postgresql`, `nextjs`, `nodejs` |
| **Tags** | `ai`, `llm`, `rag`, `search` |
| **Body (Markdown)** | Paste README body from this repo, or `sanity-drafts/morphic-markdown-body.md` from the render-templates workspace |

## One-click deploy URL

```text
https://render.com/deploy-template/api/github/start?template_repo=morphic-render-template
```

## Template Generator

Optional: paste the GitHub repo URL into the [Template Generator](https://thumbnail-generator-lme2.onrender.com/template-generator.html) for thumbnail, tags, and Sanity rich text.

## Approval

Have the DX lead (Raph) review repo, README, deploy flow, and Sanity entry before publishing to **production**.

## Verify

- [ ] https://render.com/templates/morphic-render-template loads
- [ ] **Deploy this template** forks the repo and Blueprint Apply works
- [ ] Demo link opens https://morphic-us8x.onrender.com/
