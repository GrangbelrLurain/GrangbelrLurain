# 김규연 (Kyuyeon Kim)

Next.js 멀티테넌트 모노레포, 타입 안전한 BFF 파이프라인, Rust 기반 데스크톱 개발자 도구를 설계하는 프론트엔드 리드 / 프로덕트 엔지니어입니다.

[English Version](./README.md) · [delete-horizon.com](https://delete-horizon.com) · [Contact](mailto:lurain003@gmail.com) · 수원 / 서울, 대한민국

---

> "도메인이 복잡할수록 구조를 먼저 정의하고, 공통 모듈과 타입 안전한 BFF, 인프라 레벨의 개발 도구로 팀의 반복 비용을 줄입니다."

---

## 주요 프로젝트 (delete-horizon)

### [horizon-gateway](https://gateway.delete-horizon.com)
**로컬 네트워크 및 인프라 오케스트레이션을 위한 Agentic DX 데스크톱 도구**

- **단일 바이너리 데스크톱 앱**: Rust와 Tauri 2 기반 경량 바이너리로 로컬에서 프로덕션 수준의 네트워크·프록시 환경 재현
- **내장 네트워크 엔진**: HTTPS MITM 프록시, API 모킹 샌드박스, WinDivert 기반 투명 프록시(OS 프록시 설정을 무시하는 프로세스 패킷 캡처), 모바일 터널링 지원
- **AI 에이전트 연동**: Cursor, Claude Code, Gemini 등 AI 에이전트가 로컬 인프라 상태를 직접 조회하고 제어할 수 있는 CLI(`hgc`) 및 Agent Skill 계층 제공
- **실시간 팀 워크스페이스 동기화**: Supabase Realtime 기반 도메인·Mock 규칙 동기화 및 SQLite FTS5 본문 검색 지원

[Live](https://gateway.delete-horizon.com) · [GitHub](https://github.com/GrangbelrLurain/horizon-gateway)

<br>

### [horizon-mesh](https://travel.delete-horizon.com)
**독립 배포된 PWA 표면을 연동하는 서버리스 마이크로 프론트엔드 메쉬**

- **서버리스 프론트엔드 메쉬**: 복잡한 서버 오케스트레이션 없이 공통 임베드 프로토콜을 통해 서로 다른 독립 도메인의 PWA 연동
- **Local-First 오프라인 지원**: `travel`, `hotel`, `auth` 모듈 분리 및 IndexedDB 기반 오프라인 동작 지원, Cloudflare Pages 정적 배포

[travel.delete-horizon.com](https://travel.delete-horizon.com/?mode=edit) · [hotel.delete-horizon.com](https://hotel.delete-horizon.com/) · [auth.delete-horizon.com](https://auth.delete-horizon.com/)

---

## 경력 사항

### 주식회사 와이리즘 (YRISM) — Frontend Lead / FE PL *(팀원 3~5명)* `2024.11 – 재직 중`
*모두투어 차세대 웹 플랫폼 파견 (B2C / Best Partner / Online Best Partner)*

- **멀티테넌트 모노레포 구축**: B2C 단일 구조를 `core`, `web-b2c`, `web-onbp` 패키지로 분리하고, pnpm + Turborepo 전환 및 Docker 빌드 캐시 최적화로 약 300여 개 파트너사(ONBP) 사이트 원소스 운영 체계 구축
- **프레임워크 메이저 업그레이드**: Next.js v12(Pages) → v15, React 19, TypeScript 5 마이그레이션 주도 및 Ant Design v4 → v5 전환으로 레거시 Less 빌드 체인 제거
- **타입 안전한 BFF 파이프라인**: Hono 기반 BFF(`@b2c/server`, `@onbp/server`)와 Zod/TypeBox 스키마 검증을 도입하여 FE–BE 경계를 엄격히 관리하고 FE Model/Mapper 분리로 API 변경 영향도 격리
- **결제 및 핵심 도메인 독립화**: 결제 UI를 독립 배포 가능한 임베드 모듈(`payment.modetour.com`)로 분리하고 호텔·항공·검색·예약 등 핵심 비즈니스 플로우 차세대 이관
- **엔지니어링 DX 표준화**: Dev/Stage/Prod 및 항공·호텔 샌드박스 엔드포인트를 즉시 전환하는 `proxy-tool` 구축, 팀 공통 Cursor/Claude Agent 가이드라인 수립

### 주식회사 지에스아이코 (GSIKO) — Frontend Developer `2024.01 – 2024.10`
*YesCMS B2B 자금관리 시스템 & KFTC 오픈뱅킹*

- **레거시 C/S → 웹 전면 전환**: 기존 Windows 설치형 C/S 클라이언트를 React 기반 웹 어드민으로 재설계 (30여 개 주요 운영 화면 신규 구축)
- **KFTC(금융결제원) 오픈뱅킹 연동**: 출금·수납·원장 및 송수신 내역 화면의 상태 관리, 데이터 검증, 예외/재처리 워크플로우 FE 소유 및 개발
- **대용량 금융 그리드 최적화**: 금융 데이터 테이블에 가상화(Virtualization)를 적용해 브라우저 메모리 부하 해소 및 스크롤 렌더링 성능 안정화

### 주식회사 샵팬픽 (ShopFanPick) — Frontend Developer `2022.04 – 2023.12`
*크리에이터 커머스 플랫폼 & 어드민 생태계*

- **CRA → Next.js 모노레포 전환**: 커머스, 어드민, Studio 3개 서비스를 Next.js로 마이그레이션하여 SSR/SSG 도입 및 SEO 가시성/초기 로딩 속도 대폭 개선
- **FE 주도 프로덕트 개발**: Next.js BFF + Prisma 모델 공유로 프론트엔드가 백엔드 대기 없이 비즈니스 기능을 엔드투엔드로 완결짓는 구조 수립
- **CMS 및 서버리스 파이프라인**: 메인 콘텐츠 타입 시스템 정규화, 재귀 엑셀 I/O 파서 및 Next.js 서버리스 환경에서의 Zip 암호화 다운로드 파이프라인 구현

---

## 기술 스택

```text
Languages     │ TypeScript · JavaScript · Rust · SQL
Frontend      │ Next.js (v12~v15) · React 19 · TanStack Query · Zustand · Tailwind CSS · PWA
Backend & BFF │ Hono · Next.js API Routes · Zod · TypeBox · Prisma · SQLite
Desktop & DX  │ Tauri 2 · Rust · MITM Proxy · WinDivert · Cursor Agent Skills · Vite · Biome
Architecture  │ Multi-tenant Monorepo · Turborepo · pnpm · Micro-Frontend · FSD · Local-First
Infra & Tools │ Cloudflare Pages · Supabase · Azure DevOps · Docker · Git
