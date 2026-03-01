# DailyReceipt

**Print your time** — 하루의 할 일을 기록하고, AI 대화로 관리하고, 영수증 스타일로 돌아보는 앱.

### 주요 기능

- Task/Goal/Plan 계층 관리 + 포커스 타이머
- AI Quick Log — 자연어 대화로 태스크 자동 생성 (Phone-as-BFF)
- 영수증 스타일 일일 리포트 저장/공유
- Notion + Google Calendar 양방향 동기화
- 원격 설정 + 피처 플래그 (백오피스)
- 크래시 리포팅 (Bugsink, self-hosted Sentry)

### 기술 스택

| Mobile | Backend | Admin | Infra |
|--------|---------|-------|-------|
| React Native (Expo) | Cloudflare Workers | Next.js 15 | K3s + ArgoCD |
| TypeScript + Zustand | Hono + D1 | PostgreSQL 16 | Cloudflare Tunnel |
| AI SDK + llama.rn | OAuth (Apple/Google) | Drizzle ORM | GitHub Actions |

### 레포지토리

| 레포 | 설명 |
|------|------|
| **DailyReceipt** | 모노레포 (mobile + api + backoffice + web) |
| DailyReceipt-Flutter | (archived) v1 Flutter 앱 |
| DailyReceipt-FE-WEB | (archived) v0 React 웹앱 |
| DailyReceipt-BE-WEB | (archived) v0 Spring Boot 백엔드 |
| DailyReceipt-Django | (archived) v0 Django 백엔드 |
