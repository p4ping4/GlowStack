# GlowStack project
📍 GlowStack Development Roadmap

GlowStack은 8주 스프린트 기반으로 개발되는 Neon UI 기반 Portfolio SaaS입니다.
아래 로드맵은 전체 기능을 단계적으로 완성해 나가는 과정입니다.

🚀 Sprint 1 — Project Setup & Branding
Monorepo 구축 (frontend / backend / docs)
Workspace 패키지 설정
ESLint, Prettier, Commitlint 구성
GitHub Actions 기본 파이프라인 설정
Tailwind 네온 컬러 토큰 정의
GlowStack 로고 & 브랜딩 기초 확립
GlassCard / GlowButton 컴포넌트 디자인

⚙️ Sprint 2 — Frontend Foundation

Vite + Tailwind 환경 구성
Global 라우팅 구조(/login, /dashboard 등)
Glass Navigation Bar 구축
ThemeManager (Dark + Neon)
Axios + React Query 설정
NeonButton, GlassCard 기본 컴포넌트 구현

🔐 Sprint 3 — Backend Authentication
Express 초기 설정
MongoDB 연결 & User 모델 생성
/auth/sign_up 구현
/auth/login 구현
JWT 기반 인증 로직
Axios interceptor 및 Protected Route 적용

🧩 Sprint 4 — Profile & Skills Management
/user/me 조회 API
/user 업데이트 API
프로필 수정 UI
SkillChip 편집 인터페이스
변경 감지(“unsaved changes”) 기능
이미지 업로드 전략 설정

📝 Sprint 5 — Project CRUD & Dashboard
Project 모델 생성
/projects CRUD API 구현
프로젝트 카드 UI 구성
프로젝트 생성/수정 모달
링크/이미지 필드 지원
Dashboard 프로젝트 목록 UI

🎨 Sprint 6 — Public Portfolio Page
/u/:username 포트폴리오 페이지 완성
Hero Section (Neon Ring + Glow Profile)
Skills Section
ProjectGrid & Hover Glow
About Section + 타임라인 UI
SEO Meta Builder
User URL 라우팅 구조 완성

⚡ Sprint 7 — Motion, Particles & Theme Expansion

Framer Motion 전체 적용
Hero 파티클 배경
SkillChip pulse animation
ProjectCard stagger animation
3가지 네온 테마 프리셋 생성
전체 UI Polish 작업

☁️ Sprint 8 — Deployment, Docs & Release
Frontend Vercel 배포
Backend Railway/Render 배포
도메인 연결 (예: glowstack.dev)
.env.example 생성
README 정리 + Demo 이미지 추가
최종 QA & 버그 수정
GlowStack v1.0.0 릴리즈

🗺️ Long-Term Plans
커스텀 테마 에디터
템플릿 기반 포트폴리오 생성
프로젝트 통계/조회수
Drag & Drop 프로젝트 정렬
팀 포트폴리오(조직용) 모드
GlowStack Pro 플랜 기능 연구