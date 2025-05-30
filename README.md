
</div>

<br/>

<div align="center">

### 🌱 성장하는 개발자  
클린 코드와 테스트 코드 작성에 관심이 많은 백엔드 개발자입니다.

</div>

<br/>

---

## 🧑‍💻 About Me

- **관심 분야:** 클린 아키텍쳐, 성능 최적화
- **개발자로서의 목표:**  
  AI 시대에도 요구받는, 문제 해결과 아키텍처 설계에 강한 개발자  
- **성장 방식:**  
  단순 구현이 아닌, 동작 원리와 아키텍처적 고민을 바탕으로 효율적이고 유지보수 가능한 코드를 지향합니다.

---

## 🚀 Projects

### 📈 Stocks Are Everywhere, 온세상이 주식이야
- **모의투자 플랫폼**
- **개발 기간:** 2025.02.28 ~ 2025.04.03
- **사용 기술:** `React`, `TypeScript`, `Vite`, `Spring Boot`, `Java`, `MySQL`, `Redis`, `JPA`, `RabbitMQ`, `gRPC`, `Python`, `FastAPI`
- **주요 트러블슈팅:**
    - User-service: 다수 동시 트랜잭션으로 인한 계좌 데이터 부정합 및 커넥션 고갈 문제 → 비관적 락 적용 및 DB 커넥션 풀 최적화로 해결.
    - Order-service: 외부 서비스 통신 비효율 및 빈번한 DB 조회로 인한 성능 저하 → gRPC 도입 및 종가 데이터 인메모리 캐싱으로 개선.
    - Matching-service:
       - 체결 대기열의 동시성 문제로 인한 구조 붕괴 → 인메모리 자료구조 변경하여 안정적인 동시 주문 처리 구현
       - 종목별 세밀한 락 관리로 처리량 70% 향상 
- [프로젝트 상세 보기](https://github.com/platypus3036/onseju)


### 📚 Book_wave
- **중고책 거래 플랫폼**
- **개발 기간:** 2024.11.11 ~ 2024.12.12
- **사용 기술:** `Spring Boot`, `OAuth 2.0`, `WebSocket`, `RabbitMQ`, `React`
- **주요 트러블슈팅:**
    - 채팅 시 닉네임 조회를 위한 불필요한 DB 접근 발생 → Access Token Claim에 닉네임 추가하여 DB 조회 최소화.
    - 동시 접속자 증가 시 채팅 메시지 전송 지연 및 HTTP 504 오류 발생 → RabbitMQ 메시지 큐 도입하여 비동기 처리 및 부하 분산.
- [프로젝트 상세 보기](https://github.com/Book-Wave)


### 재정 개조단
- **금융 상품 추천 비교 서비스**
- **개발 기간:** 2024.09.05 ~ 2024.10.15
- **사용 기술:** `Spring`, `React`, `AWS`
- **주요 트러블슈팅:**  
  - LLM 모델 사용시 파이썬 서버 - Spring 서버 동시 가동 불가 -> DL4J를 통한 JAVA로 LLM 구현 
- [프로젝트 상세 보기](https://github.com/P5-2)

<!-- 추가 프로젝트가 있다면 아래와 같이 계속 추가 -->
<!--
### 프로젝트명
- 한 줄 설명
- 개발 기간: YYYY.MM.DD ~ YYYY.MM.DD
- 사용 기술: `기술1`, `기술2`
- 주요 트러블슈팅: 간단히 요약
- [프로젝트 상세 보기](프로젝트_링크)
-->

---

## 💻 Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![SpringBoot](https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)

### Frontend
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

### Infrastructure
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

## 📊 Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=platypus3036&show_icons=true&theme=dark&bg_color=282829&text_color=00ff00&title_color=00ff00&icon_color=00ff00&border_color=00ff00" width="49%" />
  <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=akakehcn" width="40%" align="top" />
</div>

---

## 📫 Contact

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akakehcn@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/platypus3036)
[![Velog](https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=velog&logoColor=white)](https://velog.io/platypus3036)

</div>

