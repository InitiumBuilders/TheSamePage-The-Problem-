# TheSame.Page — Site Backup (The Problem / "The Price of Concentration")

This repository is a faithful backup of the website that was live at **https://thesame.page**
prior to its repurposing as the Initium signal bridge.

## Provenance
- **Source:** Vercel production deployment `dpl_8k893ttcKj4v8Xcjq1NraBmhwKtF`
  (project `v0-static-site-deployment`, team `sourcecrowd`), created 2026-06-03, status Ready.
- **Live title at backup time:** `TheSame.Page — The Price of Concentration`
- **Backed up:** 2026-06-18
- **Fidelity:** The rendered page `src/public/index.html` is a byte-exact copy of the live site (213,465 bytes).

## Contents
- `src/` — the complete v0 / Next.js (App Router) source project as deployed, including:
  - `src/app/` — `layout.tsx`, `page.tsx`, `globals.css`
  - `src/components/` — UI component library (shadcn/ui)
  - `src/hooks/`, `src/lib/`, `src/public/`
  - `src/package.json`, `src/pnpm-lock.yaml`, `src/next.config.mjs`, `src/tsconfig.json`, configs
- `src/public/index.html` — the live static page content.

All 81 source files were retrieved via the Vercel Deployment Files API with zero failures.
