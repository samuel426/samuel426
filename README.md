# 안녕하세요, 백엔드 개발자 우성현입니다.

Spring Boot와 Java를 중심으로 백엔드 개발을 공부하고 있으며,  
서비스가 안정적으로 운영되기 위해 필요한 API 설계, 데이터 처리, 인증/인가, 관리자 기능, 모니터링 구조에 관심이 많습니다.

단순히 기능을 구현하는 것보다  
사용자와 운영자가 실제로 문제없이 사용할 수 있는 구조를 고민하는 개발자를 지향합니다.

---

## Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java-17%2F21-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)

### Database & Infra
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS%20EC2%20%7C%20S3-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### Collaboration
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)

---

## Projects

### Dear.___  
디지털 타임캡슐 플랫폼  
2025.12.03 ~ 2026.01.07, 5주  
역할: PO, Backend Developer  
수상: 최우수상, 인기상

특정 날짜 또는 장소 조건을 만족해야 열람할 수 있는 디지털 타임캡슐 서비스입니다.  
10명 규모 팀에서 PO 역할과 백엔드 개발을 함께 수행하며, 관리자 시스템과 서비스 운영 안정성을 위한 기능을 담당했습니다.

주요 담당 기능

- 관리자 대시보드 API 개발
- 회원, 캡슐, 신고, 제재, AI 검증 로그 관리 기능 구현
- OpenAI Moderation API 연동을 통한 유해 콘텐츠 검증
- 캡슐 연관 데이터 하드 딜리트 로직 구현
- JPA Fetch Join 및 쿼리 구조 개선을 통한 조회 성능 개선

기술 스택

`Java 21` `Spring Boot 3.5` `Spring Security` `JPA` `MySQL` `Redis` `AWS EC2` `S3` `Docker` `GitHub Actions`

---

### PortfolioIQ Evaluation  
GitHub 저장소 품질 분석 서비스  
2025.10.10 ~ 2025.10.27, 3주  
역할: Backend Developer

GitHub 저장소 데이터를 기반으로 README, TEST, COMMIT, CI/CD 항목을 평가하고,  
OpenAI API를 활용해 정량 점수와 정성 피드백을 생성하는 Evaluation 도메인을 구현했습니다.

주요 담당 기능

- OpenAI 기반 저장소 평가 파이프라인 구현
- 평가 결과 JSON 스키마 설계 및 파싱
- AI 응답의 코드블록 및 불필요 텍스트 정제 로직 구현
- AnalysisResult, Score 엔티티 저장 구조 설계
- AiGateway 인터페이스 기반 OpenAI/Noop 구현 분리
- API 키 유무에 따른 조건부 Bean 구조 적용
- 예외 처리 구조를 통해 비정상 AI 응답에 대한 장애 전파 통제

기술 스택

`Java` `Spring Boot` `JPA` `MySQL` `OpenAI API` `JSON Parsing`

---

### Khudadak  
윤작·다모작 추천 시뮬레이터  
2025.05.10  
수상: 쿠톤 우수상

사용자의 재배 조건을 입력받아 윤작과 다모작에 적합한 작물 TOP3를 추천하는 웹 서비스입니다.  
지역, 토양 pH, 질소 상태, 이전 작물, 병해충 이력 등을 기반으로 점수를 계산하고 추천 근거를 함께 제공합니다.

주요 담당 기능

- 작물 추천 API 구현
- 7가지 조건 기반 점수 계산 로직 설계
- 추천 결과 정렬 및 TOP3 반환
- Spring Boot 백엔드와 React 프론트엔드 연동
- CORS 설정 및 AWS 배포 환경 구성

기술 스택

`Java 17` `Spring Boot` `JPA` `MySQL` `React` `AWS EC2`

---

### SQL Injection 웹 보안 취약점 분석 및 대응  
캡스톤 디자인 프로젝트  
2024년 1학기

APM 환경에서 SQL Injection 취약 웹 페이지를 직접 구성하고,  
Boolean-based Blind SQL Injection 공격 시나리오를 구현한 뒤 대응 방안을 분석한 프로젝트입니다.

주요 내용

- Apache, PHP, MySQL 기반 취약 웹 환경 구성
- Boolean-based Blind SQL Injection 공격 자동화
- DB, Table, Column, User Data 추출 과정 구현
- Linear Search 방식의 비효율 분석
- Binary Search 방식으로 탐색 알고리즘 개선
- 매개변수화 쿼리, 입력값 검증, 에러 메시지 차단 등 대응 방안 정리

기술 스택

`Ubuntu` `Apache` `PHP` `MySQL` `Python` `Pandas`

---

## What I Care About

- 안정적으로 운영 가능한 백엔드 구조
- 데이터 무결성과 트랜잭션 처리
- 인증, 인가, 제재, 신고 등 운영 도메인
- 장애 상황을 고려한 예외 처리와 로그 설계
- 금융 서비스에 필요한 신뢰성과 보안성

---

## Experience Keywords

`Backend Development`  
`Spring Boot`  
`JPA`  
`MySQL`  
`Redis`  
`REST API`  
`Admin System`  
`Rate Limiting`  
`OpenAI API Integration`  
`Security`  
`AWS Deployment`

---

## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_ID&show_icons=true&theme=default)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_ID&layout=compact)

---

## Contact

- Email: samuel.woo2014@gmail.com
- Portfolio: 준비 중
- Blog: 준비 중
