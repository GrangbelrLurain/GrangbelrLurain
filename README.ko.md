# 김규연 (Kyuyeon Kim)

와이리즘(YRISM)에서 모두투어 차세대 웹 플랫폼의 프론트엔드 리드를 맡고 있습니다. Next.js 멀티테넌트 모노레포와 프론트엔드가 소유하는 BFF를 만듭니다.

[이력서](https://grangbelrlurain.github.io/) · [LinkedIn](https://www.linkedin.com/in/kyuyeon-kim-322462261/) · [Email](mailto:lurain003@gmail.com) · [English](./README.md) · 수원 / 서울

---

## 경력

### 주식회사 와이리즘 (YRISM), Frontend Lead / FE PL (본인 포함 6명) `2024.11 - 재직 중`
*모두투어 차세대 웹 플랫폼 파견 (B2C / Best Partner / Online Best Partner)*

- 파트너(ONBP) 사이트 570여 개를 하나의 Next.js 코드베이스로 운영
- B2C 단일 앱을 `core`, `web-b2c`, `web-onbp` 패키지로 나누고 pnpm + Turborepo 모노레포로 전환
- Next.js 12(Pages Router)에서 15로, React 19와 TypeScript 5로 업그레이드 주도
- Ant Design v4를 v5로 올리고 Less 빌드 체인 제거
- Hono BFF(`@b2c/server`, `@onbp/server`)에 Zod와 TypeBox 검증을 넣고, API와 UI 사이에 FE Model / Mapper 계층 분리
- 호텔, 항공, 검색, 예약 흐름을 새 플랫폼으로 이관
- 기준을 통과한 변경만 머지되도록 CI 테스트 하네스 설계
- ISMS 기준에 맞춰 암복호와 개인정보 처리를 클라이언트 밖으로 이동
- Dev / Stage / Prod와 항공·호텔 샌드박스 엔드포인트를 전환하는 내부 프록시 도구 제작
- 팀 공통 Cursor / Claude 에이전트 가이드라인 작성
- 커밋 1,490건, 머지된 PR 669건 작성 (2024.12 - 2026.09)

### 주식회사 지에스아이코 (GSIKO), Frontend Developer `2024.01 - 2024.10`
*YesCMS B2B 자금관리 웹 · 금융결제원 CMS 출금이체 연계*

- Windows 설치형 C/S 클라이언트의 주요 화면 약 30개를 React 웹 어드민으로 전환
- CMS 출금이체 기반 출금·수납·원장 화면의 상태 관리, 검증, 재시도 처리를 FE에서 담당
- 고밀도 금융 데이터 그리드에 테이블 가상화 적용

### 주식회사 샵팬픽 (ShopFanPick), Frontend Developer `2022.04 - 2023.12`
*크리에이터 커머스 플랫폼과 어드민, 스튜디오*

- 커머스, 어드민, Studio 3개 CRA 앱을 SSR/SSG를 쓰는 Next.js 모노레포로 전환
- Next.js API Routes를 BFF로 쓰고 모노레포 전체에서 Prisma 타입 공유
- CMS 콘텐츠 타입, 재귀 엑셀 입출력 파서, 서버리스 Zip 암호화 다운로드 구현

---

## 개인 프로젝트

### [horizon-gateway](https://gateway.delete-horizon.com)
로컬 네트워크 디버깅과 API 모킹을 위한 Rust + Tauri 2 데스크톱 도구입니다.

- HTTPS MITM 프록시, API 모킹 샌드박스, WinDivert 투명 프록시, 모바일 터널링 제공
- Cursor, Claude Code 같은 AI 에이전트가 트래픽을 조회하고 Mock을 설정하는 CLI(`hgc`)와 Agent Skill 제공
- Supabase Realtime으로 팀 도메인·Mock 규칙을 동기화하고 SQLite FTS5로 검색

[사이트](https://gateway.delete-horizon.com) · [저장소](https://github.com/GrangbelrLurain/horizon-gateway)

### horizon-mesh (실험 중)
따로 배포한 PWA(`travel`, `hotel`, `auth`)를 공통 임베드 프로토콜로 연결해 보는 실험이며, Cloudflare Pages에 배포되어 있습니다. 완성된 제품은 아닙니다.

---

## 기술 스택

```text
Languages     │ TypeScript · JavaScript · Rust · SQL
Frontend      │ Next.js (v12 to v15) · React 19 · TanStack Query · Zustand · Tailwind CSS · Ant Design · PWA
Backend & BFF │ Hono · Next.js API Routes · Zod · TypeBox · Prisma · SQLite
Desktop & DX  │ Tauri 2 · Vite · Biome · Cursor · Claude
Architecture  │ Multi-tenant Monorepo · Turborepo · pnpm · Micro-Frontend · FSD · Local-First
Infra & Tools │ Cloudflare Pages · Supabase · Azure DevOps · Docker · Git
```
