# Kyuyeon Kim (김규연)

Frontend Lead at YRISM, working on Modetour's next-generation travel platform. I build multi-tenant Next.js monorepos and frontend-owned BFF layers.

[Resume](https://grangbelrlurain.github.io/resumes/kyuyeon-kim-en) · [Portfolio](https://grangbelrlurain.github.io/) · [LinkedIn](https://www.linkedin.com/in/kyuyeon-kim-322462261/) · [Email](mailto:lurain003@gmail.com) · [한국어](./README.ko.md) · Suwon / Seoul, South Korea (UTC+9)

<p align="left">
  <img src="https://img.shields.io/badge/Next.js-12_to_15-black?style=flat-square&logo=next.js" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Rust-Tauri_2-DEA584?style=flat-square&logo=rust&logoColor=black" alt="Rust" />
  <img src="https://img.shields.io/badge/Monorepo-pnpm_%7C_Turborepo-blueviolet?style=flat-square" alt="Monorepo" />
</p>

---

## Experience

### YRISM, Frontend Lead / FE PL (team of 6) `Nov 2024 - Present`
*Dispatched to Modetour's next-generation web platform (B2C, Best Partner, Online Best Partner)*

- Ran 570+ Online Best Partner (ONBP) sites from one Next.js codebase.
- Split the single B2C app into `core`, `web-b2c`, and `web-onbp` packages in a pnpm and Turborepo monorepo.
- Led the upgrade from Next.js 12 (Pages Router) to Next.js 15, React 19, and TypeScript 5.
- Moved Ant Design v4 to v5 and removed the Less build chain.
- Built Hono BFFs (`@b2c/server`, `@onbp/server`) with Zod and TypeBox validation, plus FE Model and Mapper layers between the API and the UI.
- Migrated the Hotel, Flight, Search, and Booking flows to the new platform.
- Designed a CI test harness so only changes that pass the checks get merged.
- Moved encryption and personal-data handling off the client to meet ISMS requirements.
- Built an internal proxy tool that switches between Dev, Stage, Prod, and airline and hotel sandbox endpoints.
- Wrote the team's Cursor and Claude agent guidelines.
- Authored 1,490 commits and 669 merged pull requests (Dec 2024 to Sep 2026).

### GSIKO, Frontend Developer `Jan 2024 - Oct 2024`
*B2B finance admin and KFTC CMS direct debit*

- Migrated about 30 admin screens from a Windows desktop client to a React web admin.
- Owned state, validation, and retry handling for withdrawal, collection, and ledger screens integrated with KFTC CMS direct debit.
- Added table virtualization to high-density finance data grids.

### ShopFanPick, Frontend Developer `Apr 2022 - Dec 2023`
*Creator commerce platform with admin and studio apps*

- Migrated 3 CRA apps (Commerce, Admin, Studio) to a Next.js monorepo with SSR and SSG.
- Used Next.js API Routes as a BFF and shared Prisma types across the monorepo.
- Built the CMS content type system, a recursive Excel import and export parser, and encrypted Zip downloads in serverless functions.

---

## Independent Projects

### [horizon-gateway](https://gateway.delete-horizon.com)
A Rust and Tauri 2 desktop tool for local network debugging and API mocking.

- Includes an HTTPS MITM proxy, an API mock sandbox, a WinDivert transparent proxy, and mobile tunneling.
- Ships a headless CLI (`hgc`) and Agent Skills so AI coding agents such as Cursor and Claude Code can inspect traffic and set mocks.
- Syncs team domain and mock rules with Supabase Realtime and searches them with SQLite FTS5.

[Site](https://gateway.delete-horizon.com) · [Repository](https://github.com/GrangbelrLurain/horizon-gateway)

### horizon-mesh (Experimental)
An experiment that connects separately deployed PWAs (`travel`, `hotel`, `auth`) through a shared embed protocol, hosted on Cloudflare Pages. Not a finished product.

---

## Tech Stack

```text
Languages     │ TypeScript · JavaScript · Rust · SQL
Frontend      │ Next.js (v12 to v15) · React 19 · TanStack Query · Zustand · Tailwind CSS · Ant Design · PWA
Backend & BFF │ Hono · Next.js API Routes · Zod · TypeBox · Prisma · SQLite
Desktop & DX  │ Tauri 2 · Vite · Biome · Cursor · Claude
Architecture  │ Multi-tenant Monorepo · Turborepo · pnpm · Micro-Frontend · FSD · Local-First
Infra & Tools │ Cloudflare Pages · Supabase · Azure DevOps · Docker · Git
```
