# Kyu-Yeon Kim (김규연)

Frontend Lead at YRISM, dispatched to Modetour.

[Korean Version](./README.ko.md) · [Resume](https://grangbelrlurain.github.io/) · [English Resume](https://grangbelrlurain.github.io/resumes/kyuyeon-kim-en) · [LinkedIn](https://www.linkedin.com/in/kyuyeon-kim-322462261/) · [Contact](mailto:lurain003@gmail.com) · Suwon / Seoul, South Korea

<p align="left">
  <img src="https://img.shields.io/badge/Next.js-v12--v15-black?style=flat-square&logo=next.js" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Rust-Tauri_2-DEA584?style=flat-square&logo=rust&logoColor=black" alt="Rust" />
  <img src="https://img.shields.io/badge/Architecture-Multi--tenant_Monorepo-blueviolet?style=flat-square" alt="Monorepo" />
</p>

---

## Professional Experience

### YRISM, Frontend Lead / FE PL (Team of 6), Nov 2024 - Present
*Dispatched to Modetour next-gen web (B2C / Best Partner / Online Best Partner)*

- 1,490 commits and 669 merged PRs authored on Modetour_PlatformWeb (Dec 2024 to Sep 2026).
- Split the Modetour B2C app into `core`, `web-b2c`, and `web-onbp` in a pnpm and Turborepo monorepo.
- Operate 570+ ONBP partner sites from one codebase.
- Upgraded Next.js 12 Pages to Next.js 15, React 19, and TypeScript 5.
- Replaced Ant Design v4 with Ant Design v5 and removed Less.
- Built Hono BFFs (`@b2c/server`, `@onbp/server`) with Zod, TypeBox, and FE Model and Mapper layers.
- Migrated the Hotel, Flight, Search, and Booking domains.
- Designed a CI test harness that merges only changes that pass the baseline.
- Moved encryption and personal-data handling off the client for ISMS compliance.
- Built an internal proxy for Modetour Dev, Stage, Prod, and airline and hotel sandboxes.
- Wrote Cursor and Claude Agent guidelines for the YRISM team.

### GSIKO, Frontend Developer, Jan 2024 - Oct 2024
*B2B finance admin & KFTC Open Banking*

- Migrated about 30 admin screens from a Windows desktop (C/S) client to a React web admin.
- Built state, validation, and retry handling for KFTC Open Banking withdrawal, collection, and ledger screens.
- Applied table virtualization on YesCMS financial grids.
- Automated Popbill tax-invoice workflows.

### ShopFanPick, Frontend Developer, Apr 2022 - Dec 2023
*Creator commerce (Commerce, Admin, Studio)*

- Migrated 3 CRA apps (Commerce, Admin, Studio) to a Next.js monorepo with SSR and SSG.
- Used Next.js API Routes as a BFF with shared Prisma types across the monorepo.
- Built CMS content types for ShopFanPick.
- Built recursive Excel I/O for ShopFanPick.
- Built serverless zip-encrypted downloads for ShopFanPick.

---

## Independent Projects

Separate from YRISM and Modetour. Site: [delete-horizon.com](https://delete-horizon.com).

### [horizon-gateway](https://gateway.delete-horizon.com)

- Built horizon-gateway with Rust and Tauri 2.
- horizon-gateway is a single binary.
- horizon-gateway includes an HTTPS MITM proxy.
- horizon-gateway includes an API mock sandbox.
- horizon-gateway uses a WinDivert transparent proxy to capture process traffic that ignores the OS proxy.
- horizon-gateway supports mobile tunneling.
- horizon-gateway includes a headless CLI, `hgc`.
- horizon-gateway Agent Skills let Cursor, Claude Code, and Gemini inspect traffic and mock APIs.
- horizon-gateway syncs team domain and mock rules with Supabase Realtime.
- horizon-gateway indexes content with SQLite FTS5.

[gateway.delete-horizon.com](https://gateway.delete-horizon.com) · [GitHub](https://github.com/GrangbelrLurain/horizon-gateway)

### horizon-mesh (Experimental)

Unfinished serverless PWA mesh for [travel.delete-horizon.com](https://travel.delete-horizon.com/), [hotel.delete-horizon.com](https://hotel.delete-horizon.com/), and [auth.delete-horizon.com](https://auth.delete-horizon.com/).

---

## Tech Stack

```text
Languages     │ TypeScript · JavaScript · Rust · SQL
Frontend      │ Next.js (v12-v15) · React 19 · TanStack Query · Zustand · Tailwind CSS · Ant Design · PWA
Backend & BFF │ Hono · Next.js API Routes · Zod · TypeBox · Prisma · SQLite
Desktop & DX  │ Tauri 2 · Rust · MITM Proxy · WinDivert · Vite · Biome
Architecture  │ Multi-tenant Monorepo · Turborepo · pnpm · Micro-Frontend · FSD · Local-First
Infra & Tools │ Cloudflare Pages · Supabase · Azure DevOps · Docker · Git
AI tooling    │ Cursor · Claude
```
