# Kyuyeon Kim (김규연)

> Frontend Lead / Product Engineer specializing in multi-tenant Next.js monorepos, Rust desktop tooling, and serverless PWA meshes.

[delete-horizon.com](https://delete-horizon.com) · [GitHub](https://github.com/GrangbelrLurain) · [lurain003@gmail.com](mailto:lurain003@gmail.com) · Suwon / Seoul, Korea

---

### Focus & Engineering Scope
- **Current Role**: Frontend Lead @ **YRISM** *(Dispatched to Modetour)*
- **Architecture**: Multi-tenant Monorepo, Next.js (v12→v15), Desktop DX (`Rust` / `Tauri 2`), Micro-Frontend Mesh
- **Primary Stack**: `TypeScript` · `JavaScript` · `Rust` · `Next.js` · `React` · `TanStack Query` · `Zustand` · `Turborepo` · `Tailwind CSS` · `PWA` · `Tauri 2` · `Prisma`

---

<details>
<summary><b>🇰🇷 Profile & Experience (KR)</b></summary>

<br>

> **"복잡한 도메인일수록 아키텍처 관점에서 문제를 정의하고, 인프라 및 모듈화로 해결합니다."**  
> 커머스 프론트엔드로 시작해 B2B 운영 시스템 전환을 거쳐, 모두투어 차세대 플랫폼에서 B2C와 파트너(ONBP) 서비스를 아우르는 Next.js 멀티테넌트 모노레포를 설계하고 있습니다.

#### 💼 Experience

- **주식회사 와이리즘 (YRISM)** — **Frontend Lead** `2024.11 – Present`  
  *모두투어 차세대 웹 파견 (B2C / Best Partner / Online Best Partner)*
  - B2C 및 파트너 서비스를 단일 모노레포(`web-b2c` / `web-onbp` / `core`)로 구조화하여 테넌트별 화면 분기와 공통 자원 공유 독립화
  - 결제 UI 모듈을 MFA embed 형태로 분리하여 멀티 테넌트 간 독립 배포 및 재사용 구조 구축
  - 레거시 리스크를 분석하여 Next.js **v12 → v15** 마이그레이션 직접 주도
  - 프론트엔드 코드 컨벤션, 리뷰 프로세스 및 온보딩 가이드라인 수립

- **주식회사 지에스아이코 (GSIKO)** — **Frontend Developer** `2024.01 – 2024.10`  
  *YesCMS (Cash Management System) B2B 운영 웹*
  - 기존 C/S 설치형 클라이언트를 React 기반 웹 시스템으로 재설계 (10~30개 주요 화면 아키텍처 수립 및 마이그레이션)
  - 운영자 워크플로우 분석을 통한 어드민 UI/UX 개편

- **주식회사 샵팬픽** — **Frontend Developer** `2022.04 – 2023.12`  
  *크리에이터 커머스 플랫폼*
  - CRA 기반 서비스(커머스, 어드민, Studio)를 Next.js로 마이그레이션하여 SEO 가시성 및 라우팅 로딩 성능 개선
  - Next.js BFF 레이어 도입 및 Prisma 타입 공유로 프론트엔드의 독립적인 기능 소유권 확보 (**FE → 프로덕트 엔지니어**로 역할 확장)

#### 🚀 Projects

- **[horizon-gateway](https://gateway.delete-horizon.com)** — `Rust` · `Tauri 2` · `React` · `TypeScript`  
  로컬 개발 환경 관리를 위한 Agentic DX 데스크톱 애플리케이션 (HTTPS MITM 프록시, API 모킹, 모바일 터널링). AI 에이전트(Cursor, Claude, Gemini) 연동 CLI 및 Agent Skill 제공.  
  🔗 [gateway.delete-horizon.com](https://gateway.delete-horizon.com) · [GitHub](https://github.com/GrangbelrLurain/horizon-gateway)

- **[horizon-mesh](https://travel.delete-horizon.com)** — `Turborepo` · `React` · `TypeScript` · `PWA` · `Cloudflare Pages`  
  독립 배포된 PWA 모듈을 공통 프로토콜로 연동한 정적 서블릿 메쉬 아키텍처 (`travel` · `hotel` · `auth`).  
  🔗 [travel.delete-horizon.com](https://travel.delete-horizon.com/?mode=edit) · [hotel.delete-horizon.com](https://hotel.delete-horizon.com/) · [auth.delete-horizon.com](https://auth.delete-horizon.com/)

#### 🎓 Education
- **인제고등학교** *(이과 졸업 · 2013.02)*

</details>

<br>

<details>
<summary><b>🌐 Profile & Experience (EN)</b></summary>

<br>

> **Frontend Lead · Product Engineer**

#### 📌 Overview
Frontend Engineer with 4+ years of experience designing TypeScript monorepos, multi-tenant Next.js platforms, and Rust-based developer tooling. Currently leading frontend architecture for a large-scale travel platform (B2C + Partner tenants). Independently built and maintain **horizon-gateway** (Agentic DX desktop app) and **horizon-mesh** (serverless PWA mesh).

#### 💼 Experience

- **YRISM** *(Dispatched to Modetour)* — **Frontend Lead** `Nov 2024 – Present`  
  - Architected a 3-tenant Next.js monorepo (`web-b2c`, `web-onbp`, `core`) integrating B2C and partner platforms.
  - Extracted payment UI as an MFA embed module for multi-tenant reusability across platforms.
  - Led Next.js **v12 → v15** upgrade, evaluating legacy risk and managing seamless migration.
  - Established FE coding conventions, code review standards, and technical onboarding docs.

- **GSIKO** — **Frontend Developer** `Jan 2024 – Oct 2024`  
  - Re-architected a legacy desktop C/S client into a React web app from scratch *(YesCMS B2B admin)*.

- **ShopFanPick** — **Frontend Developer** `Apr 2022 – Dec 2023`  
  - Migrated 3 CRA services *(Commerce, Admin, Studio)* to Next.js for SSR/SSG SEO gains and performance.
  - Introduced Next.js BFF layer sharing Prisma types across monorepo, empowering FE to own end-to-end features.

#### 🚀 Selected Projects

- **[horizon-gateway](https://gateway.delete-horizon.com)** — Cross-platform Agentic DX desktop app in Rust & Tauri 2. Local HTTPS MITM proxy, API mocking, and AI agent CLI / Skill layer.  
  🔗 [gateway.delete-horizon.com](https://gateway.delete-horizon.com) · [GitHub](https://github.com/GrangbelrLurain/horizon-gateway)

- **[horizon-mesh](https://travel.delete-horizon.com)** — Serverless Multi-Frontend App mesh connecting independently-deployed PWAs via a shared embed protocol.  
  🔗 [travel](https://travel.delete-horizon.com/?mode=edit) · [hotel](https://hotel.delete-horizon.com/) · [auth](https://auth.delete-horizon.com/)

#### 🎓 Education
- **Inje High School** *(Science track · Graduated Feb 2013)*

</details>

<br>
