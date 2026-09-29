### 김세현 — 백엔드 개발자

무엇을 신뢰할지 경계를 설계하고, 그 경계가 실제로 버티는지 검증합니다.

[![Gmail](https://img.shields.io/badge/Gmail-kimshh21%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kimshh21@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-byesummer-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/byesummer)

### 기술 스택

| Category | Stacks |
|---|---|
| Backend | ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Spring Cloud Gateway](https://img.shields.io/badge/Spring%20Cloud%20Gateway-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) |
| Data | ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Redisson](https://img.shields.io/badge/Redisson-C41E3A?style=flat-square) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| Infra & DevOps | ![Linux](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![GHCR](https://img.shields.io/badge/GHCR-181717?style=flat-square&logo=github&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) |

---

### 프로젝트

#### **Trillion** — MSA 온라인 서점 (8인) · `2025.11 ~ 2026.01`

8인 팀이 만든 MSA 온라인 서점. 개발 후 개선 사항을 찾아 수정

**담당**: JWT 기반 인증/인가(auth, 게이트웨이 인증·인가 필터), 회원 서비스

**핵심 구현**
- RTR·재사용 탐지, Redisson 분산 락
- 게이트웨이 직접 검증으로 인증 판단 약 4.3배 단축(2.3ms → 0.53ms)
- 소셜 로그인 교환 코드 패턴.

**Repository**: [auth](https://github.com/byesummer/trillion-books-auth) · [gateway](https://github.com/byesummer/trillion-books-gateway) · [member](https://github.com/byesummer/trillion-books-member)


#### **Workspace Booking** — 회의실 예약 (2인) · `2026.07 ~ ` **사내 실사용**

NHN Academy 교육 수행팀에서 근무하며 회의실 매번 사용 여부를 확인해야 했던 불편을 계기로 2인이 개발.

교육생 45명 · 관리자 3명이 약 2개월간 사용했고, 문의 → 당일 수정 → 익일 배포로 운영.

**담당**: 알림 파이프라인·인프라(배포·운영) 구현 (예약 정책 공동 설계)

**핵심 구현**
- 트랜잭션 경계 밖 LAZY 로딩 트러블슈팅
- Docker Compose → Kubernetes 이관(GitOps).

**Repository**: [backend](https://github.com/nhn-academy-workspace/workspace-backend) · [frontend](https://github.com/nhn-academy-workspace/workspace-frontend) · [manifests](https://github.com/nhn-academy-workspace/workspace-manifests)

---

### 학력 · 활동

- 명지대학교 정보통신공학과(인공지능·ICT 융합 전공) 졸업 `2025.08.`
- NHN Academy — Java 백엔드 개발자 과정 `2025.07. ~ 2026.01.`

### 경력
- NHN Academy 교육수행팀 `2026.01. ~ 2026.09.`

### 자격증

- 정보처리기사 `2024.09.10.`
- SQLD `2024.12.13.`
