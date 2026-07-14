# 🛠️ 기술 스택 (Tech Stack)

**GitHub**: [@akfakf0509](https://github.com/akfakf0509)

---

## 💻 언어 / 프레임워크
- **TypeScript**: 타입 안전성, 고급 패턴, 대규모 프로젝트
- **Vue.js 3**: Composition API, 엔터프라이즈급 애플리케이션
- **Nuxt.js**: Nuxt Layers 기반 모듈화 아키텍처, SSR/SSG 구성
- **JavaScript**: ES6+, 모듈화, 비동기 처리

---

## 🎨 스타일링
- **Tailwind CSS**: 유틸리티 우선 CSS, 반응형 디자인, Dark Mode
- **SCSS/CSS**: 시맨틱 마크업, 커스텀 스타일링
- **Tailwind CSS Animations**: tailwindcss-animated
- **Motion Vue**: 선언적 애니메이션
- **Embla Carousel**: 터치 친화적 캐러셀

---

## 📊 상태 관리 / 데이터 페칭
- **Pinia**: Vue 3 공식 상태 관리, Store 설계 및 구조화
- **@pinia/colada**: 스마트 데이터 페칭, 캐싱 전략, 낙관적 업데이트
- **VueUse**: @vueuse/core, @vueuse/nuxt, @vueuse/router, @vueuse/math

---

## 🎯 UI 라이브러리
- **Reka UI**: Headless UI 컴포넌트, Ariakit 생태계
- **Nuxt UI**: 사전 구성된 컴포넌트, Tailwind CSS 통합
- **Nuxt Icon**: Iconify 기반 아이콘 시스템 (@iconify-json/*)
- **TanStack Vue Table**: Headless UI Table
- **TanStack Vue Virtual**: 가상 스크롤

---

## 📝 콘텐츠 / 에디터
- **Tiptap**: WYSIWYG 에디터, ProseMirror 기반
  - 텍스트 포매팅, 리스트, 블록, 이미지, 파일 처리
  - 링크 관리, 버블/플로팅 메뉴, 텍스트 정렬, 히스토리

---

## 🌍 국제화
- **Nuxt I18n / Vue I18n**: 다국어 지원
- **@internationalized/date**: 날짜 지역화
- **@internationalized/number**: 숫자 포매팅
- **date-fns**: 날짜 포매팅 및 계산
- **@date-fns/tz**: 타임존 처리
- **es-hangul**: 한글 처리
- **libphonenumber-js**: 전화번호 포매팅

---

## 📊 데이터 시각화
- **Chart.js / vue-chartjs**: 차트 라이브러리
- **D3**: 고급 시각화
- **Three.js**: 3D 그래픽

---

## 🎮 멀티미디어
- **HLS.js**: HLS 스트리밍
- **video.js**: 비디오 플레이어
- **@ffmpeg/ffmpeg**: 브라우저 기반 인코딩
- **html5-qrcode**: QR 코드 스캔
- **@channel.io/channel-web-sdk-loader**: 실시간 채팅

---

## 🔒 보안 / 모니터링
- **Sentry**: @sentry/nuxt, @sentry/vue (에러 트래킹, 성능 모니터링)
- **Zod**: 타입 안전 유효성 검사
- **openapi-fetch**: 타입 안전 API 클라이언트
- **OpenTelemetry**: @opentelemetry/api

---

## 📊 분석 / 로깅
- **Mixpanel**: mixpanel-browser (사용자 행동 추적, 이벤트 분석)
- **GTM Support**: Google Tag Manager 통합

---

## 🧪 테스트 / 품질 보증
- **Vitest**: 단위/통합 테스트, @vitest/browser
- **Testing Library**: @testing-library/vue, @testing-library/user-event
- **Playwright**: E2E 테스트
- **JSdom**: DOM 환경 시뮬레이션

### 린팅 / 타입 체킹
- **TypeScript**: 타입 안정성
- **ESLint**: @nuxt/eslint, @fanding/eslint
- **vue-tsc**: Vue 타입 체킹

---

## 🛠️ 빌드 / 번들링
- **Vite**: 초고속 개발 서버, ES 모듈 기반
- **Nuxt DevTools**: @nuxt/devtools, 컴포넌트/라우터 시각화
- **rollup-plugin-visualizer**: 번들 분석

---

## 📦 패키지 관리
- **pnpm**: Monorepo 관리, 빠른 설치 (v10.18.2+)
- **Yarn**: 대체 패키지 매니저

---

## 🚀 배포 / CI-CD
- **GitHub Actions**: 워크플로우 자동화
- **Nuxt**: SSR/SSG 배포

---

## 🔧 개발 도구 / 유틸리티

### 빌드 & 설정
- **magic-string**: 문자열 조작
- **defu**: 기본값 병합
- **unimport**: 자동 import
- **tinyglobby**: 파일 패턴 매칭

### 날짜 / 시간
- **date-fns**: 날짜 포매팅, 계산
- **@date-fns/tz**: 타임존 처리

### 유틸리티 라이브러리
- **es-toolkit**: 경량 유틸리티, 함수형 프로그래밍
- **type-fest**: 고급 TypeScript 타입
- **lodash**: 배열/객체 조작

### API 처리
- **openapi-fetch**: 타입 안전 API 클라이언트
- **query-string**: 쿼리 문자열 파싱
- **ufo**: URL 처리 유틸
- **h3**: 경량 HTTP 프레임워크

### 데이터 처리
- **immer**: 불변 상태 업데이트
- **fflate**: 압축/해제
- **jszip**: ZIP 파일 조작
- **sharp**: 이미지 처리
- **svgo**: SVG 최적화

### 검증 & 스키마
- **Zod**: 타입 안전 스키마 검증
- **@notionhq/client**: Notion API

---

## 🚀 커스텀 내부 라이브러리

**Fanding Packages:**
- `@fanding/web`: 메인 웹 프로젝트
- `@fanding/auto-block`: 자동 차단 시스템
- `@fanding/cross-routing`: 크로스 도메인 라우팅
- `@fanding/env-vars`: 환경 변수 관리
- `@fanding/eslint`: 커스텀 ESLint 설정
- `@fanding/locales`: 다국어 로케일 데이터
- `@fanding/markdown`: Markdown 처리
- `@fanding/mixpanel`: Mixpanel 래퍼
- `@fanding/nuxt-kit`: Nuxt 유틸리티 모음
- `@fanding/sentry`: Sentry 통합
- `@fanding/server-api`: API 타입 정의

---

## 📱 개발 환경

### 필수 버전
- **Node.js**: 22.18.0 이상 (권장: 24.13.1+)
- **pnpm**: 10.18.2+ (권장: 10.30.1+)

### 주요 명령어
```bash
pnpm dev          # 개발 서버 실행
pnpm build        # 프로덕션 빌드
pnpm typecheck    # TypeScript 타입 체킹
pnpm test         # 테스트 실행
pnpm eslint       # 린트 검사
pnpm preview      # 빌드 결과 미리보기
```

---

## 📊 프로젝트별 언어 구성

### 팬딩 WEB (`fanding/web`)
| 언어 | 비중 |
|------|------|
| Vue | 60% |
| TypeScript | 38.6% |
| JavaScript | 0.7% |
| SCSS | 0.4% |
| CSS | 0.3% |

### 팬베이스 WEB (`fanding/lamewall-web`)
| 언어 | 비중 |
|------|------|
| Vue | 51.3% |
| TypeScript | 46.4% |
| CSS | 1.1% |
| Dockerfile | 1.1% |
| JavaScript | 0.1% |

---

## 🏆 기술 역량

| 분야 | 수준 | 세부 역량 |
|------|------|----------|
| **웹 개발** | ⭐⭐⭐⭐⭐ | Vue 3, TypeScript, Nuxt.js, 대규모 프로젝트 |
| **상태 관리** | ⭐⭐⭐⭐⭐ | Pinia, 데이터 페칭, 캐싱 전략 |
| **UI/UX** | ⭐⭐⭐⭐⭐ | Tailwind CSS, 컴포넌트 설계, 접근성 |
| **성능 최적화** | ⭐⭐⭐⭐☆ | 번들 최적화, 렌더링 성능 |
| **DevOps** | ⭐⭐⭐☆☆ | GitHub Actions, Docker 기본 |
| **테스트** | ⭐⭐⭐⭐☆ | 단위/통합 테스트, E2E 테스트 |

---

**마지막 업데이트**: 2026년 7월  
**주요 버전**: Vue 3, Nuxt 3, TypeScript 5, Vite 5, Tailwind CSS 3
