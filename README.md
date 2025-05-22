# 익명 투표 앱 프로젝트


## 프로젝트 아키텍처

![msa-kafka](https://github.com/user-attachments/assets/a9a94a3c-b21c-47a0-bdec-846392b09ac2)


#### 기술 스택 : SpringBoot, Spring Security, Docker, JPA, Redis, Spring Cloud Gateway, Kafka


- MSA 아키텍처 기반 프로젝트 구현
- Spring Cloud Gateway를 사용하여 인증과 라우팅 중앙화
- Kafka를 도입하여 서비스간 비동기 이벤트 처리 구현
- 서비스별 db를 분리하여 데이터 정합성 및 성능 향상
