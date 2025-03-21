# Fastcampus Queue System 실습

이 프로젝트는 Fastcampus [대용량 트래픽 백엔드 실습 강의](https://github.com/morenice/fastcampus-2023-backend-advacned)를 기반으로 한 대기열 시스템 실습입니다.  
강의 내용을 그대로 구현하였으며, 사용자 요청을 시뮬레이션하는 웹 사이트(`website`)와 대기열 처리 로직이 포함된 서버(`flow`)로 구성되어 있습니다.

---

## 🧩 요구 사항

- Java 17+
- Redis (6.2 사용, 로컬 Docker로 실행 가능)

```bash
docker run -d -p 6379:6379 redis:6.2
```
---

## 🚀 실행 방법

# flow (대기열 시스템)
```bash
cd flow
./gradlew bootRun
```

# website (요청 시뮬레이터)
```bash
cd website
./gradlew bootRun
```
