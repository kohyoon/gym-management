# 🏋️ 헬스장 회원 및 운동 관리 시스템

> Java + Spring Boot + Oracle + MyBatis 기반의 백엔드 개인 프로젝트  
> 헬스장 회원의 등록, 운동 루틴 설정, 출석 관리 등을 효율적으로 처리할 수 있는 관리자용 시스템입니다.

---

## 📌 주요 기능

- 👤 회원 관리 (등록, 수정, 삭제, 조회)
- 🏋️ 운동 루틴 관리 (운동명, 부위, 세트 수 등록)
- 🔁 회원별 루틴 연결 (다대다 관계)
- 🗓️ 출석 체크 기능 (날짜 기반 기록)
- 🔒 (선택) 관리자 권한 및 인증 기능

---

## 🛠 사용 기술 스택

| 분류 | 기술 |
|------|------|
| Language | Java 17 |
| Framework | Spring Boot 3.x |
| DB | Oracle 11g/19c |
| ORM | MyBatis |
| Build Tool | Gradle |
| Others | Lombok, Validation, Git, GitHub |

---

## 🗂 프로젝트 구조 (예시)

```plaintext
src
├─ main
│  ├─ java
│  │  └─ com.example.gymsystem
│  │     ├─ controller
│  │     ├─ service
│  │     ├─ mapper
│  │     ├─ domain
│  │     └─ GymSystemApplication.java
│  └─ resources
│     ├─ application.yml (ignored)
│     ├─ application-sample.yml
│     └─ mapper
│        └─ MemberMapper.xml
