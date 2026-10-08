<div align="center">

# Hi, I'm SJM 👋

**Backend · Web · iOS**

[GitHub](https://github.com/SJM-coding) · [Tech Blog](https://velog.io/@dobbyisfreee/posts)

</div>

---

### About

백엔드, 웹, iOS를 개발해 왔습니다.

현재는 **풋살허브를 개발하고 운영하며**, 코드를 만드는 일을 넘어 서비스의 목표를 이루는 데 집중하고 있습니다. 개발은 그 목표를 실현하는 수단이라고 생각합니다.

**“AI 시대에는 인간이 가장 큰 병목이다”**라는 관점에 공감합니다. 사람이 매번 개입해야 하는 과정을 줄이고, 반복되는 작업을 AI가 수행할 수 있도록 업무 흐름과 시스템을 설계하고 있습니다.

### Tech

![Java](https://img.shields.io/badge/Java-17-3730A3?style=flat-square)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA_%2F_Hibernate-59666C?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

### Selected Projects

#### FUTSALHUB — 풋살 대회 플랫폼

풋살 대회 개설부터 모집·대진·정산까지 다루는 서비스입니다.

> 현재 운영 중인 서비스로, 소스 코드는 비공개입니다. 백엔드 구조와 주요 설계 결정은 공개 설계 문서에서 확인할 수 있습니다.

[설계 문서 보기](https://github.com/SJM-coding/futsal-hub-architecture)

- 모듈러 모놀리스에서 도메인 이벤트와 포트로 컨텍스트 연결
- 참가 신청·청구·결제를 상태 전이와 이벤트로 연결
- 설계 문서 사이의 관계와 불변식을 스크립트로 검증

`Java` `Spring Boot` `JPA` `MySQL` `Redis` `DDD`

#### Meaire — Outbox와 메시지 재처리

데이터 정합성을 공부하며 Outbox 패턴과 Kafka 재처리 흐름을 적용한 프로젝트입니다.

[코드 보기 · Fork](https://github.com/SJM-coding/Backend)

- Outbox 이벤트 적재와 폴링 기반 처리
- 재시도·백오프 및 멱등 키를 고려한 메시지 처리
- Retryable Topics와 DLT 메시지 저장

`Outbox Pattern` `Kafka` `Retry` `Idempotency`

### Writing

개발하면서 고민한 내용은 [기술 블로그](https://velog.io/@dobbyisfreee/posts)에 정리합니다.
