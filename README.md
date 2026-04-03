# About Me

<p align="center">
  <a href="#korean">한국어</a> | <a href="#english">English</a>
</p>

<p align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=GrangbelrLurain&show_icons=true&theme=radical&hide_border=true" />
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=GrangbelrLurain&theme=radical&hide_border=true" />
</p>

---

<div id="korean">

## 🚀 비즈니스의 확장성을 아키텍처로 증명하는 프론트엔드 PL, 김규연입니다.

### 👤 Profile Summary
> **"복잡한 비즈니스 요구사항을 탄탄한 아키텍처와 측정 가능한 개발 생산성으로 전환합니다."**

* 🏗 **멀티 테넌트 및 모노레포 전문가:** 단일 코드베이스에서 B2C와 B2B를 동시에 대응하는 멀티 테넌트 환경을 구축하고, 모노레포 도입을 통해 팀 전체의 개발 및 배포 생산성을 극대화합니다.
* 🛠 **실효성 있는 트러블슈팅과 개발 환경 최적화:** 4년 차 프론트엔드 PL로서 팀의 워크플로우를 저해하는 병목 현상을 주도적으로 파악합니다. 패키지 매니저 마이그레이션(Yarn → pnpm) 등을 통해 빌드 안정성을 확보하고 쾌적한 DX(Developer Experience)를 구축합니다.
* 🌐 **풀스택적 사고를 갖춘 아키텍트:** Prisma, Next.js 기반의 풀스택 경험과 Rust/Tauri를 활용한 고성능 데스크톱 앱 개발 역량을 바탕으로, 백엔드와의 효율적인 통신 구조를 설계하며 기술적 완성도를 높입니다.

### 🛠 Tech Stack
<p align="left">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white">
  <img src="https://img.shields.io/badge/Tauri-FFC131?style=for-the-badge&logo=tauri&logoColor=white">
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white">
  <img src="https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white">
</p>

### 📂 Work Experience

#### 1. [모두투어 트래블 에이전시](https://www.modetour.com/) (2024.11 ~ 현재)
**Role:** FE PL (프론트엔드 파트 리드 및 아키텍처 개편)
**Context:** 기존 B2C 전용 FE 앱을 B2B 파트너사 용도로 확장하고, 다수 브랜드를 지원하는 멀티 테넌트 환경 셋업.

* **🔥 Key Achievements:** * **모노레포(Monorepo) 기반 통합 아키텍처 설계:** 기존 PC/MO 단일 앱을 모노레포 워크스페이스로 마이그레이션하여 B2C, Best Partner, Online Best Partner 등 3개 이상의 앱을 독립적이면서도 통합적으로 관리. `pages` 단위의 import만으로 신규 서비스 뷰를 구성하도록 결합도를 낮춰 **신규 파트너사 앱 구축 기간을 [약 50%] 단축**.
  * **런타임(Runtime) 기반 동적 전역 상태 제어:** 빌드 타임에 고정되는 환경 변수의 한계를 극복하기 위해, 런타임에 `env`와 `init data`를 주입받아 Redux Context와 연동. 서비스 타겟에 따라 커스터마이징이 필요한 전역 뷰(View)를 동적으로 제어하는 유연한 아키텍처 구현.
  * **의존성 꼬임 해결 및 CI/CD 최적화:** Yarn 환경의 고질적인 유령 의존성(Phantom Dependency) 문제를 해결하기 위해 pnpm으로의 마이그레이션 주도. 이를 통해 패키지 충돌을 원천 차단하고 **빌드 속도를 [약 30%] 개선**하여 팀의 배포 파이프라인 안정화.

#### 2. [AI YESCMS 프로젝트](https://ai.yescms.com/) (2024.01 ~ 2024.10)
**Role:** 프론트엔드 엔지니어
**Context:** 노후화된 설치형 CS 프로그램(자동이체, 고객 관리, 세금계산서 발행 등)의 모던 웹 마이그레이션 및 레거시 청산.

* **Key Achievements:** * 방대한 데이터 그리드와 복잡한 폼(Form)을 다루는 레거시 CS 시스템을 React 생태계로 성공적으로 마이그레이션하여 제품 경쟁력 및 유지보수성 대폭 향상.
  * 데이터 시각화 및 직관적인 UX/UI 개편을 통해 사용자 학습 비용을 최소화하였으며, 결과적으로 **신규 기업 고객 20개사 이상 유입** 및 플랫폼 리텐션 증가에 직접적으로 기여.

#### 3. [Fanpick 커머스 & 스튜디오](https://www.shopfanpick.com/) (2022.04 ~ 2023.12)
**Role:** 프론트엔드 엔지니어
**Context:** 크리에이터 전용 커머스 스토어 및 판매 통계를 제공하는 백오피스(Studio) 구축.

* **Key Achievements:** * **Mono-repo 도입을 통한 개발 효율성 극대화:** 스토어와 백오피스로 파편화된 Multi-repo 환경을 통합. 공통 컴포넌트 및 유틸리티 함수 공유를 통해 코드 중복을 제거하고 프론트엔드 자원 관리 효율을 극대화.
  * **Next.js + Prisma 기반 풀스택 피쳐 개발:** 프론트엔드와 백엔드의 통합 구조를 설계하고 구현하여, 한 명의 개발자가 도메인의 End-to-End를 담당할 수 있는 환경 조성. 이를 통해 인력 배분 최적화 및 **빠른 피쳐 단위 개발(Agile) 사이클** 확보.

### 💻 Personal & Open Source Projects

#### Watchtower (도메인 및 서비스 모니터링 데스크톱 앱)
* **Tech:** Rust, Tauri, React, TypeScript
* **Status:** ✅ **Production** | 팀 내부 도입 완료
* **Description:** 웹 기술과 시스템 프로그래밍(Rust)을 결합하여 구축한 엔터프라이즈급 모니터링 데스크톱 애플리케이션입니다.

* **🎯 Key Achievement: 400+ 도메인 로컬 테스트 인프라 구축**
  * **400개가 넘는 프로덕션 도메인**을 로컬 환경에서 테스트할 수 있도록 시스템 레벨의 프록시 라우팅 및 SSL 인증서 관리를 자동화했습니다.
  * 외부 네트워크 대기 시간이나 고비용의 스테이징 인프라 없이, 팀원들이 로컬에서 실제 서비스와 매우 유사한 환경을 구성해 개발할 수 있도록 워크플로우를 혁신했습니다.

* **Engineering Excellence:**
  * **Scale & Architecture:** 복잡한 멀티윈도우 상태 동기화를 구현하고 400개 이상의 동시 도메인을 <100ms 응답 속도로 안정적으로 관리합니다.
  * **Performance:** 무거운 Electron(약 150MB) 대신 **Tauri와 Rust(약 5MB)**를 채택하여 바이너리 크기를 70% 이상 줄이고 네이티브 수준의 성능과 극도로 가벼운 메모리 점유율을 달성했습니다.

</div>

---

<div id="english">
  
## 🚀 Front-End Architect & PL Driving Business Scalability

### 👤 Profile Summary
> **"Translating complex business needs into robust architecture and measurable engineering productivity."**

* 🏗 **Multi-tenant & Monorepo Expert:** Adept at building scalable multi-tenant architectures that serve both B2C and B2B platforms from a single codebase. I leverage Monorepo workspaces to maximize team productivity and streamline deployment cycles.
* 🛠 **Proactive DX Engineering & Troubleshooting:** As a 4th-year Front-End Project Leader (PL), I proactively identify and eliminate workflow bottlenecks. By spearheading critical migrations (e.g., Yarn to pnpm), I secure build stability and cultivate a seamless Developer Experience (DX).
* 🌐 **Full-Stack Vision & System-Level Capability:** Combining full-stack experience (Next.js, Prisma) with high-performance desktop app development (Rust, Tauri) to design highly efficient client-server communication models and deliver polished user experiences.

### 🛠 Tech Stack
<p align="left">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white">
  <img src="https://img.shields.io/badge/Tauri-FFC131?style=for-the-badge&logo=tauri&logoColor=white">
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white">
  <img src="https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white">
</p>

### 📂 Work Experience

#### 1. [Modetour Travel Agency Project](https://www.modetour.com/) (2024.11 ~ Present)
**Role:** Front-End PL (Lead & Architecture Revamp)
**Context:** Expanding a B2C-exclusive application into a multi-tenant ecosystem serving various B2B partners.

* **🔥 Key Achievements:**
  * **Architected a Monorepo-Based Unified Ecosystem:** Migrated a monolithic PC/Mobile app into a scalable Monorepo workspace, centrally managing multiple applications (B2C, Best Partner, Online Best Partner). Drastically reduced coupling, enabling the construction of new service views via simple `pages` directory imports, **accelerating new partner app deployment by [e.g., 50%]**.
  * **Engineered Dynamic Runtime View Control:** Overcame the limitations of static build-time variables by designing an architecture that injects `env` and `init data` at runtime. Integrated this with Redux Context to dynamically render and customize global UI elements based on the specific tenant context.
  * **Optimized CI/CD & Resolved Dependency Entanglement:** Spearheaded the migration from Yarn to pnpm to eliminate chronic phantom dependencies. This critical DX improvement guaranteed zero package conflicts and **boosted build speeds by [e.g., 30%]**, stabilizing the team's deployment pipeline.

#### 2. [AI YESCMS Project](https://ai.yescms.com/) (2024.01 ~ 2024.10)
**Role:** Front-End Engineer
**Context:** Modernizing a legacy, installable CS program (auto-transfers, CRM, tax invoicing) into a modern web environment.

* **Key Achievements:** * Successfully migrated complex, data-heavy legacy desktop interfaces into a performant React ecosystem, fully restoring product competitiveness and long-term maintainability.
  * Completely revamped the data visualization and UI/UX, minimizing user onboarding friction. This directly contributed to the **acquisition of 20+ new corporate clients** and drove a steady increase in platform retention.

#### 3. [Fanpick Commerce & Studio](https://www.shopfanpick.com/) (2022.04 ~ 2023.12)
**Role:** Front-End Engineer
**Context:** Building creator-specific e-commerce storefronts and a robust data analytics back-office (Studio).

* **Key Achievements:** * **Maximized Efficiency via Mono-repo Consolidation:** Merged a fragmented multi-repo setup into a single workspace, centralizing UI components and utility functions. This significantly reduced code duplication and streamlined front-end resource management.
  * **Implemented Next.js + Prisma Full-Stack Architecture:** Designed an integrated E2E workflow that allowed developers to take full ownership of feature lifecycles. This optimized human resource allocation and enabled a **rapid, agile feature deployment cycle**.

### 💻 Personal & Open Source Projects

#### Watchtower (Domain & Service Monitoring App)
* **Tech:** Rust, Tauri, React, TypeScript
* **Status:** ✅ **Production** | Adopted by internal teams
* **Description:** A high-performance, cross-platform desktop application designed for enterprise-level domain monitoring and local testing infrastructure.

* **🎯 Key Achievement: Architected a 400+ Domain Local Testing Infrastructure**
  * Engineered a robust system capable of managing **400+ concurrent production domains** with sub-millisecond precision.
  * Implemented system-level HTTP/HTTPS proxy routing and automated SSL certificate management, enabling internal development teams to test against environments identical to real production services locally without network latency or external dependencies.

* **Engineering Excellence:**
  * **Architecture:** Features complex multi-window state synchronization (isolated yet fully synchronized).
  * **Performance:** Replaced traditional resource-heavy Electron architectures with **Tauri and Rust**, reducing the binary footprint by ~70% (5MB vs. 150MB) while achieving near-native execution speeds and remarkably low memory usage.

---

### 📫 Contact
* **Email:** [lurain003@gmail.com](mailto:lurain003@gmail.com)
* **Phone:** +8210-2300-6059
* **GitHub:** [@GrangbelrLurain](https://github.com/GrangbelrLurain)

</div>
