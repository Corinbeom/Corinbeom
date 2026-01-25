
## About
문제를 먼저 정의하고, 필요한 기술을 빠르게 붙여 끝까지 완성하는 개발자입니다.  
기능들을 한 시스템으로 묶어 사용자 여정을 만들고, 성능과 운영 복잡도를 함께 줄이는 설계를 선호합니다.

## Tech
### Backend
![Java](https://img.shields.io/badge/Java-000000?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-000000?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-000000?style=for-the-badge&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-000000?style=for-the-badge&logo=hibernate&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### AI / Worker
![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-000000?style=for-the-badge&logo=fastapi&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-000000?style=for-the-badge&logo=postgresql&logoColor=white)

### Frontend
![TypeScript](https://img.shields.io/badge/TypeScript-000000?style=for-the-badge&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-000000?style=for-the-badge&logo=react&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000000?style=for-the-badge&logo=expo&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)

### Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000000?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-000000?style=for-the-badge&logo=mysql&logoColor=white)

### Infra
![Redis](https://img.shields.io/badge/Redis-000000?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-000000?style=for-the-badge&logo=docker&logoColor=white)


## Featured Projects

### READ-ON-ME
- AI 기반 도서 추천 중심의 멀티 서비스 독서 플랫폼
- Expo 앱 / Spring Boot API / FastAPI AI 워커를 역할 기준으로 분리해 결합도 최소화
- Redis 캐시 TTL, 벡터 검색 파이프라인, SSE 알림으로 사용자 플로우를 끊기지 않게 설계
- Repo: [Read On Me](https://github.com/Corinbeom/READ-ON-ME "Read On Me로 이동합니다")

### SingSongGame
- 실시간 멀티플레이 음악/퀴즈 게임
- STOMP 기반 WebSocket + Redis Pub/Sub로 이벤트 흐름을 분리해 상태 동기화 정합성 확보
- 룸 단위 진행 흐름이 꼬이지 않게 이벤트 순서와 상태 업데이트 경계를 설계
- Repo: [SingSongGame](https://github.com/orgs/DRS-SingSongGame/repositories "SingSongGame으로 이동합니다")

### KorPlace
- 서울시/경기도/관광공사 등 공공데이터 문화행사·관광 정보를 한곳에서 조회하는 통합 서비스
- 기관별 응답 구조 차이를 표준화해 프론트 예외 처리를 줄이고 검색 조건을 단일화
- 동적 조건 조회와 호출 최적화로 평균 응답 속도 개선 경험
- Repo: [KorPlace](https://github.com/orgs/MatsuriSeoul/repositories "KorPlace로 이동합니다")

## Highlights
- E2E 재현 가능한 로컬 개발 환경 구성: docker-compose 기반으로 앱–서버–워커 연동 검증
- 캐시/검색/실시간 알림 등 사용자 경험에 직접 영향을 주는 구간을 우선순위로 최적화
- 기능 추가보다 경계 설계와 예외 케이스 정리가 전체 품질을 결정한다고 믿습니다


## Links
Blog: [Velog](https://velog.io/@corinbeom/posts "Velog로 이동합니다")

## Contact
✉️ Email : eun4005@gmail.com
