<div align="center">

# Hi, I'm SJM 👋

**Backend · Domain Design · Data Consistency**

Java와 Spring으로 서비스를 만들고,<br>
도메인 경계와 데이터 정합성을 고민합니다.

[GitHub](https://github.com/SJM-coding) · [Tech Blog](https://velog.io/@dobbyisfreee/posts)

</div>

---

### About

- 풋살 대회 플랫폼의 참가·대진·결제 흐름을 도메인으로 설계하고 있습니다.
- 도메인 이벤트와 포트로 경계 간 의존성을 줄이는 구조를 다룹니다.
- Outbox, 재시도, 멱등성을 적용하며 메시지 처리와 데이터 정합성을 공부합니다.

### Tech

![Java](https://img.shields.io/badge/Java-17-3730A3?style=flat-square)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA_%2F_Hibernate-59666C?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

### Selected Projects

#### [Futsal Hub — 백엔드 도메인 설계](https://github.com/SJM-coding/futsal-hub-architecture)

풋살 대회 개설부터 모집·대진·정산까지 다루는 서비스의 설계 문서입니다.

- 모듈러 모놀리스에서 도메인 이벤트와 포트로 컨텍스트 연결
- 참가 신청·청구·결제를 상태 전이와 이벤트로 연결
- 설계 문서 사이의 관계와 불변식을 스크립트로 검증

`Java` `Spring Boot` `JPA` `MySQL` `Redis` `DDD`

#### [Meaire — Outbox와 메시지 재처리](https://github.com/SJM-coding/Backend)

데이터 정합성을 공부하며 Outbox 패턴과 Kafka 재처리 흐름을 적용한 프로젝트입니다.

- Outbox 이벤트 적재와 폴링 기반 처리
- 재시도·백오프 및 멱등 키를 고려한 메시지 처리
- Retryable Topics와 DLT 메시지 저장

`Outbox Pattern` `Kafka` `Retry` `Idempotency`

### Writing

개발하면서 고민한 내용은 [기술 블로그](https://velog.io/@dobbyisfreee/posts)에 정리합니다.
