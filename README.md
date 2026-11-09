### 내가 속한 동아리의 불편을 서비스로 만들고, 끝까지 운영하는 백엔드 개발자 남진(baggy)입니다

2023년 프론트엔드로 참여한 동아리방 예약 서비스 **DPlanner**를, 팀원들이 떠난 뒤 2026년 5월부터 서버까지 이어받아 혼자 운영하고 있습니다.

- 🛠 지금: DPlanner 서버 운영 · 대학 스트릿댄스 동아리 서비스 **SCENE** 기획(PO), 2027년 초 파일럿 준비
- 📝 기록: [baggytsk.github.io](https://baggytsk.github.io) - 공부한 것과 결정한 이유를 남깁니다
- 📫 jinoj0423@gmail.com

<br>

## Projects

| 프로젝트 | 한 줄 소개 | 내 역할 | 대표 경험 |
|---|---|---|---|
| **[MINE](https://github.com/100-hours-a-week/4-team-IMYME-be)** | CS 개념을 말로 설명하면 AI가 피드백하는 음성 학습 플랫폼 · 출시 첫 주 디스콰이엇 주간 1위 | 팀장 · Backend (6인 팀, BE 2명) | AI 결과 폴링을 SSE로 바꿔, 같은 k6 시나리오에서 `/attempts` 요청 TPS 14 → 1.2 req/s, p95 165 → 21.1ms |
| **[C.Groove](https://github.com/CGroove/CGroove-BE)** | 대학 댄스동아리 커뮤니티 · 행사 신청 플랫폼 | 개인 · Full-stack | 선착순 신청에 비관적 락 적용, 정원 10명에 50명 동시 신청 테스트(H2)로 초과 없음 확인 · 테스트 239개, 라인 커버리지 94.1% |
| **[DPlanner](https://github.com/dpplanner/api)** | 대학 동아리방·물품 예약 서비스 (iOS·Android·웹) · 가입자 305명 | 앱 FE ([app](https://github.com/dpplanner/app), 2023.12 – 2024.07) → 팀이 만든 서버를 인수해 단독 운영 (2026.05 – 현재) | 접근을 잃은 계정의 DB를 옮기다 복원 시험에서 게시글 누락을 발견해 Data Pump로 바꿔 30개 테이블 이전 |

<br>

## Tech Stack

| 프로젝트 | 직접 다룬 기술 |
|---|---|
| MINE | Java 21, Spring Boot, PostgreSQL(pgvector), Flyway, Redis, SSE, k6 |
| C.Groove | Java 21, Spring Boot, Spring Security, JPA · QueryDSL, MySQL, JUnit5 · Mockito, Oracle Cloud |
| DPlanner | Spring Boot 운영, Oracle DB, Docker, GitHub Actions · Flutter(앱) |

<br>

## Activity

- 카카오테크 부트캠프 3기 풀스택 (2025.09 – 2026.03) · AI 해커톤 최우수상 · 부하테스트 대회 8강
- 중앙대학교 소프트웨어학부 졸업 (2026.02)
- 매일 알고리즘 1문제 (Java) → [algorithm](https://github.com/baggytsk/algorithm)
