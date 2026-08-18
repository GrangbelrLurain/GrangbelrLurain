# Kyuyeon Kim (김규연)

Frontend Lead & Product Engineer specializing in multi-tenant Next.js monorepos, type-safe BFF pipelines, and Rust desktop developer tooling.

[Korean Version](./README.ko.md) · [delete-horizon.com](https://delete-horizon.com) · [Contact](mailto:lurain003@gmail.com) · Suwon / Seoul, South Korea

<p align="left">
  <img src="https://img.shields.io/badge/Next.js-v12→v15-black?style=flat-square&logo=next.js" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Rust-Tauri_2-DEA584?style=flat-square&logo=rust&logoColor=black" alt="Rust" />
  <img src="https://img.shields.io/badge/Architecture-Multi--tenant_Monorepo-blueviolet?style=flat-square" alt="Monorepo" />
  <img src="https://img.shields.io/badge/AI_DX-Cursor_%7C_Claude_%7C_Gemini-412991?style=flat-square" alt="AI DX" />
</p>

---

> "When domains get complex, I start with structure — cutting repeat cost through shared modules, type-safe BFF pipelines, and infrastructure-level developer tooling."

---

## Featured Projects (delete-horizon)

### [horizon-gateway](https://gateway.delete-horizon.com)
**Agentic DX Desktop Application for Local Network & Infrastructure Orchestration**

- **Cross-Platform Desktop Tool**: Built with Rust & Tauri 2 as a lightweight single binary, reproducing production-grade networking and proxy environments locally.
- **Built-in Network Engine**: HTTPS MITM proxy, API mocking sandbox, WinDivert-based Transparent Proxy (capturing runtime traffic from processes ignoring OS proxy), and mobile tunneling.
- **AI Agent Integration**: Ships with a dedicated headless CLI (`hgc`) and Agent Skill layers enabling AI agents (Cursor, Claude Code, Gemini) to inspect traffic, mock APIs, and orchestrate local infrastructure.
- **Real-Time Team Sync**: Team workspace domain/mock rule synchronization powered by Supabase Realtime and SQLite FTS5 search indexing.

[Live Site](https://gateway.delete-horizon.com) · [GitHub Repository](https://github.com/GrangbelrLurain/horizon-gateway)

<br>

### [horizon-mesh](https://travel.delete-horizon.com)
**Serverless Micro-Frontend App Mesh across Independent PWA Surfaces**

- **Serverless MFA Mesh**: Connects independently deployed PWAs across separate domains using a lightweight shared embed protocol without requiring server-side rendering orchestration.
- **Local-First Architecture**: Modularized `travel`, `hotel`, and `auth` surfaces with IndexedDB-backed offline capabilities and static hosting on Cloudflare Pages.

[travel.delete-horizon.com](https://travel.delete-horizon.com/?mode=edit) · [hotel.delete-horizon.com](https://hotel.delete-horizon.com/) · [auth.delete-horizon.com](https://auth.delete-horizon.com/)

---

## Professional Experience

### YRISM — Frontend Lead / FE PL *(Team of 3–5)* `Nov 2024 – Present`
*Dispatched to Modetour Next-Gen Web Platform (B2C / Best Partner / Online Best Partner)*

- **Multi-Tenant Monorepo**: Re-architected single B2C into `core`, `web-b2c`, and `web-onbp` packages within a pnpm + Turborepo monorepo, establishing single-source operations for ~300+ partner (ONBP) sites.
- **Major Framework Migration**: Led full upgrades from Next.js v12 (Pages) to v15, React 19, and Ant Design v4 to v5 (eliminating legacy Less build chains and standardizing Design Tokens).
- **Type-Safe BFF Pipeline**: Built Hono-based BFFs (`@b2c/server`, `@onbp/server`) with Zod/TypeBox validation pipelines, strictly decoupling API changes from the UI via FE Model/Mapper layers.
- **Core Domain & Payment**: Decoupled payment UI into an independent MFA embed module (`payment.modetour.com`); migrated revenue-critical domains (Hotel, Flight, Search, Booking).
- **Engineering DX**: Built internal `proxy-tool` for instant environment switching across Dev/Stage/Prod and airline/hotel sandboxes; authored team-wide Cursor/Claude Agent guidelines.

### GSIKO — Frontend Developer `Jan 2024 – Oct 2024`
*YesCMS B2B Cash Management System & KFTC Open Banking*

- **Legacy C/S to Web Migration**: Re-architected a legacy Windows C/S desktop client into a modern React web admin (~30 major enterprise screens).
- **KFTC Open Banking Integration**: Owned frontend state machines, data validation, and exception/retry flows for core ledger and transaction domains.
- **Performance & Automation**: Applied table virtualization for high-density financial data streams to stabilize DOM memory; automated tax-invoice (Popbill) workflows.

### ShopFanPick — Frontend Developer `Apr 2022 – Dec 2023`
*Creator Commerce Platform & Admin Ecosystem*

- **CRA to Next.js Monorepo**: Migrated 3 CRA services (Commerce, Admin, Studio) to Next.js, introducing SSR/SSG for enhanced SEO visibility and routing performance.
- **End-to-End Feature Ownership**: Introduced Next.js BFF + shared Prisma types across the monorepo, empowering frontend engineers to deliver features end-to-end without waiting for backend changes.
- **Ops Pipelines**: Implemented CMS content type systems, recursive Excel I/O parsers, and serverless Zip-encrypted batch exports.

---

## Tech Stack

```text
Languages     │ TypeScript · JavaScript · Rust · SQL
Frontend      │ Next.js (v12~v15) · React 19 · TanStack Query · Zustand · Tailwind CSS · PWA
Backend & BFF │ Hono · Next.js API Routes · Zod · TypeBox · Prisma · SQLite
Desktop & DX  │ Tauri 2 · Rust · MITM Proxy · WinDivert · Cursor Agent Skills · Vite · Biome
Architecture  │ Multi-tenant Monorepo · Turborepo · pnpm · Micro-Frontend · FSD · Local-First
Infra & Tools │ Cloudflare Pages · Supabase · Azure DevOps · Docker · Git
