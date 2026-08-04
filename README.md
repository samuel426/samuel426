# 안녕하세요, 백엔드 개발자 우성현입니다.

Java와 Spring Boot를 중심으로 백엔드 개발 역량을 쌓고 있습니다.  
기능 구현에 그치지 않고, **데이터 정합성·예외 처리·로그와 이력·운영자 관점**까지 고려한 구조를 만드는 개발자를 지향합니다.

현재는 **삼성청년SW·AI아카데미(SSAFY**)에서 Java, 알고리즘, 웹 개발과 AI 기초를 학습하며 실무 역량을 확장하고 있습니다.

<p align="left">
  <a href="mailto:samuel.woo2014@gmail.com"><img src="https://img.shields.io/badge/Email-samuel.woo2014%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/samuel426"><img src="https://img.shields.io/badge/GitHub-samuel426-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <a href="https://www.instagram.com/khu.lighthouse"><img src="https://img.shields.io/badge/Volunteer-Lighthouse-E4405F?style=flat-square&logo=instagram&logoColor=white" /></a>
</p>

---

## Timeline

| 기간 | 활동 | 핵심 경험 |
|---|---|---|
| **2026.01 ~ 현재** | **삼성청년SW·AI아카데미(SSAFY)** | Java, 알고리즘, 웹 개발, AI 기초 학습 |
| **2025.12 ~ 2026.01** | **Dear.___** | 10명 팀 PO 및 백엔드 개발, 최우수상·인기상 |
| **2025.10** | **PortfolioIQ** | OpenAI 기반 GitHub 저장소 품질 평가 파이프라인 구현 |
| **2025.05** | **Khudadak** | 2일 해커톤 MVP 개발, 쿠톤 우수상 |
| **2025.07 ~ 2026.01** | **프로그래머스 백엔드 데브코스** | Java·Spring 기반 팀 프로젝트 수행 |
| **2024.01 ~ 2025.02** | **봉사동아리 등대 회장** | 연간 운영 로드맵 수립, 활동 기획·운영, 외부기관 협업 |
| **2024.03 ~ 2024.06** | **SQL Injection 캡스톤** | 취약 환경 구성, 공격 자동화, 탐색 알고리즘 개선, 대응 방안 분석 |

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

<details open>
<summary><b>Dear.___ | 디지털 타임캡슐 플랫폼</b></summary>

<br />

**기간** 2025.12.03 ~ 2026.01.07  
**역할** PO, Backend Developer  
**성과** 최우수상, 인기상  
**Repository** [prgrms-web-devcourse-final-project/WEB7_9_FullChamZal_BE](https://github.com/prgrms-web-devcourse-final-project/WEB7_9_FullChamZal_BE)

특정 날짜 또는 장소 조건을 만족해야 열람할 수 있는 디지털 타임캡슐 서비스입니다.  
10명 규모 팀에서 PO와 백엔드 개발을 병행하며 관리자 시스템과 운영 안정성 기능을 담당했습니다.

**담당 내용**

- 회원, 캡슐, 신고, 제재, AI 검증 로그, 인증 로그를 관리하는 관리자 API 구현
- OpenAI Moderation API 연동 및 별도 트랜잭션을 통한 감사 로그 보존
- 외래키 의존 관계를 고려한 캡슐 연관 데이터 하드 딜리트 흐름 설계
- Fetch Join과 쿼리 구조 개선으로 관리자 조회의 N+1 문제 대응
- 프론트엔드와 API 명세, 일정, 역할 및 연동 기준 조율

**Tech**  
`Java 21` `Spring Boot 3.5` `Spring Security` `JPA` `MySQL` `Redis` `AWS EC2` `S3` `Docker` `GitHub Actions`

</details>

<details>
<summary><b>PortfolioIQ | GitHub 저장소 품질 분석 서비스</b></summary>

<br />

**기간** 2025.10.10 ~ 2025.10.27  
**역할** Evaluation Domain Backend Developer  
**Repository** [prgrms-be-devcourse/NBE7-9-2-Team08](https://github.com/prgrms-be-devcourse/NBE7-9-2-Team08)

GitHub 저장소의 README, TEST, COMMIT, CI/CD 항목을 분석하고 OpenAI API를 활용해 정량 점수와 정성 피드백을 생성하는 서비스입니다.

**담당 내용**

- OpenAI 기반 저장소 평가 파이프라인 구현
- 코드블록과 설명 문장을 제거한 뒤 표준 JSON으로 변환하는 응답 정제 로직 구현
- 비정상 응답과 JSON 파싱 실패를 도메인 예외로 처리
- `AiGateway` 인터페이스를 기준으로 OpenAI 구현체와 Noop 구현체 분리
- API 키가 없는 로컬·테스트 환경을 위한 조건부 Bean 구조 설계
- 분석 결과와 항목별 점수를 하나의 트랜잭션 안에서 저장

**Tech**  
`Java 21` `Spring Boot 3.5` `JPA` `MySQL` `OpenAI API` `JSON Parsing`

</details>

<details>
<summary><b>Khudadak | 윤작·다모작 추천 시뮬레이터</b></summary>

<br />

**기간** 2025.05.09 ~ 2025.05.10  
**역할** Backend Developer  
**성과** 쿠톤 우수상  
**Repository** [samuel426/khudadak](https://github.com/samuel426/khudadak)

지역, 토양 pH, 질소 상태, 이전 작물, 재배 시기, 병해충 이력 등을 입력받아 윤작과 다모작에 적합한 작물 TOP3와 추천 근거를 제공하는 서비스입니다.

**담당 내용**

- 7가지 조건 기반 작물 점수 계산 로직 설계
- 점수 내림차순 정렬과 TOP3 반환 API 구현
- 항목별 가점·감점 근거를 포함한 응답 구조 설계
- 핵심 추천 기능, 프론트엔드 연동, 배포 중심으로 MVP 범위 설정
- AWS EC2 배포 및 CORS 문제 해결

**Tech**  
`Java 17` `Spring Boot 3.4` `JPA` `MySQL` `React` `AWS EC2`

</details>

<details>
<summary><b>SQL Injection 웹 보안 취약점 분석 및 대응</b></summary>

<br />

**기간** 2024년 1학기  
**유형** 컴퓨터공학과 캡스톤 디자인

APM 환경에 취약 웹 페이지를 구성하고 Boolean-based Blind SQL Injection 공격을 자동화한 뒤 대응 방안을 분석했습니다.

**담당 내용**

- Apache, PHP, MySQL 기반 취약 웹 환경 구성
- DB, Table, Column, User Data 추출 과정 자동화
- Linear Search 방식의 비효율 분석
- Binary Search 방식으로 탐색 알고리즘 개선
- 매개변수화 쿼리, 입력값 검증, 에러 메시지 차단 등 대응 방안 정리

**Tech**  
`Ubuntu` `Apache` `PHP` `MySQL` `Python` `Pandas`

</details>

---

## Leadership & Community

<details>
<summary><b>봉사동아리 등대 | 회장</b></summary>

<br />

**활동 기간** 2024.01 ~ 2025.02  
**Activity Archive** [Instagram @khu.lighthouse](https://www.instagram.com/khu.lighthouse/)

- 1년 운영 로드맵 수립 및 월별 봉사 프로그램 기획
- 플로깅, 유기견 보호소, 무료급식소, 농촌봉사, 연탄·김장봉사 등 활동 운영
- 운영진 역할 분담, 참여 인원 관리, 외부기관 협업과 현장 조율
- 참여 목적과 가능한 시간이 다른 구성원이 선택할 수 있도록 활동 난이도와 성격을 구분

개발 프로젝트에서도 이 경험을 바탕으로 모호한 요구를 일정, 역할, API 명세와 완료 기준으로 구체화하려고 합니다.

</details>

---

## What I Care About

- 운영자가 문제를 확인하고 조치할 수 있는 백엔드 구조
- 데이터 무결성과 트랜잭션 경계
- 인증, 인가, 신고, 제재 등 운영 도메인
- 장애 상황을 고려한 예외 처리와 로그·이력 보존
- 금융 서비스에 필요한 데이터 정확성, 추적 가능성, 보안 의식

---

## Contact

- **Email** [samuel.woo2014@gmail.com](mailto:samuel.woo2014@gmail.com)
- **GitHub** [github.com/samuel426](https://github.com/samuel426)
- **Volunteer Activity** [instagram.com/lighthouse_official_](https://www.instagram.com/lighthouse_official_/)
