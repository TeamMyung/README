# 스파르타 물류 🚚

## 서비스 소개
기업 고객의 주문 정보를 효율적으로 관리하고 신속한 배송을 지원하는 **B2B 물류 관리 및 배송 시스템**입니다.  
주문 처리, 배송 관리, 허브 경로 계산, 알림 전송 등의 기능을 제공합니다.

---

## 팀원 및 역할

| 이름 | 역할 | 담당 | GitHub |
| --- | --- | --- | --- |
| 김이안 | 팀장 | 인증/인가, 회원, 배송, 배송 담당자 | [링크](https://github.com/YB-Taekwon) |
| 한성연 | 팀원 | 슬랙 메시지, 허브 경로 | [링크](https://github.com/cicle00) |
| 조현서 | 팀원 | API Gateway, Eureka Server, 배송 경로 | [링크](http://github.com/jo-hseo) |
| 신나리 | 팀원 | 허브, 업체 | [링크](https://github.com/fleurnari) |
| 이수민 | 팀원 | 상품, 주문 | [링크](http://github.com/leesumin7766) |

---

## 시스템 구성

- **API Gateway**: 인증/인가 중앙 관리, 서비스 간 JWT 전달  
- **Microservices**: 주문, 상품, 허브, 업체, 배송 등 독립 서비스  
- **Kafka**: 서비스 간 이벤트 기반 비동기 통신  
- **Redis**: 허브 정보 캐싱  
- **외부 API 연동**: Slack, Kakao Map, Gemini  

---

## 주요 기능

- **JWT 기반 인증/인가**  
- **CRUD 및 검색/페이징 기능**  
- **감사 로그 & Soft Delete**  
- **AI 예측 + Slack 알림**  
- **허브 경로 계산 및 최적 배송 경로 제공**

---

## 기술 스택

- **백엔드**: Java 17, Spring Boot 3.5.7, Spring Security, QueryDSL, Spring Cloud  
- **데이터베이스**: PostgreSQL, Redis  
- **DevOps**: Docker, Docker Compose  
- **메시징/모니터링**: Kafka, Zipkin  
- **API 문서화**: Swagger  
- **외부 API**: Slack, Kakao Map, Gemini  

---

## 시스템 아키텍처

<img width="896" height="644" alt="Image" src="https://github.com/user-attachments/assets/bb380474-e695-475b-b639-c676db35092c" />

---
## ERD

<img width="959" height="612" alt="Image" src="https://github.com/user-attachments/assets/df10870c-3dd8-478d-a485-4244cd41aba9" />




