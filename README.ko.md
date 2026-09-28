# 김규연 (Kyu-Yeon Kim)

YRISM 프론트엔드 리드. 모두투어에 파견 중입니다.

[English Version](./README.md) · [이력서](https://grangbelrlurain.github.io/) · [영문 이력서](https://grangbelrlurain.github.io/resumes/kyuyeon-kim-en) · [LinkedIn](https://www.linkedin.com/in/kyuyeon-kim-322462261/) · [Contact](mailto:lurain003@gmail.com) · 수원 / 서울, 대한민국

<p align="left">
  <img src="https://img.shields.io/badge/Next.js-v12--v15-black?style=flat-square&logo=next.js" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Rust-Tauri_2-DEA584?style=flat-square&logo=rust&logoColor=black" alt="Rust" />
  <img src="https://img.shields.io/badge/Architecture-Multi--tenant_Monorepo-blueviolet?style=flat-square" alt="Monorepo" />
</p>

---

## 경력 사항

### 주식회사 와이리즘 (YRISM), Frontend Lead / FE PL (팀 6명, 본인 포함), 2024.11 - 현재
*모두투어 차세대 웹 파견 (B2C / Best Partner / Online Best Partner)*

- Modetour_PlatformWeb에 커밋 1,490건과 머지된 PR 669건을 작성했습니다 (2024년 12월부터 2026년 9월까지).
- 모두투어 B2C를 pnpm과 Turborepo 모노레포의 `core`, `web-b2c`, `web-onbp` 패키지로 나눴습니다.
- 하나의 코드베이스에서 ONBP 파트너 사이트 570+곳을 운영합니다.
- Next.js 12 Pages를 Next.js 15, React 19, TypeScript 5로 올렸습니다.
- Ant Design v4를 Ant Design v5로 바꾸고 Less를 제거했습니다.
- Hono BFF(`@b2c/server`, `@onbp/server`)에 Zod, TypeBox, FE Model, Mapper를 적용했습니다.
- 호텔, 항공, 검색, 예약 도메인을 이관했습니다.
- 기준을 통과한 변경만 반영하는 CI 테스트 하네스를 설계했습니다.
- ISMS에 맞춰 암복호와 개인정보 처리를 클라이언트 밖으로 옮겼습니다.
- 모두투어 Dev, Stage, Prod와 항공, 호텔 샌드박스용 내부 프록시를 만들었습니다.
- YRISM 팀의 Cursor, Claude Agent 가이드라인을 작성했습니다.

### 주식회사 지에스아이코 (GSIKO), Frontend Developer, 2024.01 - 2024.10
*B2B 금융 어드민 및 KFTC 오픈뱅킹*

- Windows 데스크톱(C/S) 클라이언트의 관리 화면 약 30개를 React 웹 어드민으로 옮겼습니다.
- KFTC 오픈뱅킹 출금, 수납, 원장 화면의 상태, 검증, 재시도를 처리했습니다.
- YesCMS 금융 그리드에 테이블 가상화를 적용했습니다.
- Popbill 세금계산서 처리를 자동화했습니다.

### 주식회사 샵팬픽 (ShopFanPick), Frontend Developer, 2022.04 - 2023.12
*크리에이터 커머스 (Commerce, Admin, Studio)*

- CRA 앱 3개(Commerce, Admin, Studio)를 SSR과 SSG가 있는 Next.js 모노레포로 옮겼습니다.
- Next.js API Routes를 BFF로 쓰고, 모노레포에서 Prisma 타입을 공유했습니다.
- ShopFanPick CMS 콘텐츠 타입을 만들었습니다.
- ShopFanPick 재귀 Excel I/O를 만들었습니다.
- ShopFanPick 서버리스 zip 암호화 다운로드를 만들었습니다.

---

## 개인 프로젝트

YRISM 및 모두투어 업무와 별개입니다. 사이트: [delete-horizon.com](https://delete-horizon.com).

### [horizon-gateway](https://gateway.delete-horizon.com)

- Rust와 Tauri 2로 horizon-gateway를 만들었습니다.
- horizon-gateway는 단일 바이너리입니다.
- horizon-gateway에 HTTPS MITM 프록시가 있습니다.
- horizon-gateway에 API mock 샌드박스가 있습니다.
- WinDivert 투명 프록시로 OS 프록시를 무시하는 프로세스 트래픽을 캡처합니다.
- horizon-gateway는 모바일 터널링을 지원합니다.
- horizon-gateway에 헤드리스 CLI `hgc`가 있습니다.
- Agent Skill로 Cursor, Claude Code, Gemini가 트래픽을 조회하고 API를 mock합니다.
- Supabase Realtime으로 팀 도메인과 mock 규칙을 동기화합니다.
- SQLite FTS5로 본문을 검색합니다.

[gateway.delete-horizon.com](https://gateway.delete-horizon.com) · [GitHub](https://github.com/GrangbelrLurain/horizon-gateway)

### horizon-mesh (실험 중)

미완성. [travel.delete-horizon.com](https://travel.delete-horizon.com/), [hotel.delete-horizon.com](https://hotel.delete-horizon.com/), [auth.delete-horizon.com](https://auth.delete-horizon.com/)을 잇는 서버리스 PWA 메쉬입니다.

---

## 기술 스택

```text
Languages     │ TypeScript · JavaScript · Rust · SQL
Frontend      │ Next.js (v12-v15) · React 19 · TanStack Query · Zustand · Tailwind CSS · Ant Design · PWA
Backend & BFF │ Hono · Next.js API Routes · Zod · TypeBox · Prisma · SQLite
Desktop & DX  │ Tauri 2 · Rust · MITM Proxy · WinDivert · Vite · Biome
Architecture  │ Multi-tenant Monorepo · Turborepo · pnpm · Micro-Frontend · FSD · Local-First
Infra & Tools │ Cloudflare Pages · Supabase · Azure DevOps · Docker · Git
AI tooling    │ Cursor · Claude
```
