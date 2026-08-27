# 고정수 | Backend Developer

안녕하세요. Java와 Spring Boot를 사용해 백엔드 프로젝트를 만들고 있습니다.  
팀 프로젝트에서는 ERD와 API 명세를 작성하고, 인증·외부 API 연동·AWS 배포를 맡았습니다.  
최근에는 PyTorch로 CNN과 Attention 구조를 구현하며 공부하고 있습니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=notion&logoColor=white)](https://sudden-neptune-99c.notion.site/38fac364b188807e8149e3e7cea5121e)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kojungsu1105@gmail.com)

---

## Skills

**Backend**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**Database**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Infra & Tools**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Studying**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

---

## Projects

| Project | Role | Description |
|---|---|---|
| [**TODAIT**](https://github.com/UMC-TODAIT/TODAIT_BE) | Backend / Infra | 취향과 지역을 바탕으로 데이트·나들이 코스를 만드는 서비스 |
| [**냉방전쟁**](https://github.com/10th-UMC-Hackathon-A/Backend) | Backend / Infra | 냉방 온도를 익명 투표로 조율하는 서비스 · **UMC 교내 해커톤 우승** |
| [**Private Blockchain Network**](https://github.com/gocleanwater/SNS_LAB_Blockchain_2025.12-2025.03) | Development / Experiment | Raspberry Pi 3대로 구성한 비공개 블록체인 네트워크 |
| [**AI Study**](https://github.com/gocleanwater/AI-Study) | Personal Study | PyTorch로 CNN과 Attention 모듈 구현 |

<br />

<details>
<summary><strong>💖 TODAIT</strong></summary>

<br />

취향과 지역을 바탕으로 장소를 찾고, 원하는 순서로 데이트·나들이 코스를 구성하는 Android 서비스입니다.

`Java 17` `Spring Boot` `JPA` `MySQL` `Redis` `Spring Security` `JWT` `AWS`

- 회원·장소·분류·코스·추천 도메인의 전체 ERD 작성
- 요청·응답 형식, 인증 조건, 오류 코드를 포함한 API 명세 작성
- JWT 인증 필터와 인증 사용자 Principal 구조 개선
- 이메일 인증과 비밀번호 재설정 기능 구현
- 임시 코스의 생성·수정·복원·저장 과정 구현
- Kakao 장소 검색, OAuth, SMTP, Redis 연동
- AWS EC2·RDS·Nginx 환경과 GitHub Actions 배포 파이프라인 구성
- **50 Merged PRs · 211 Non-merge Commits**

[Repository](https://github.com/UMC-TODAIT/TODAIT_BE) · [포트폴리오에서 자세히 보기](https://sudden-neptune-99c.notion.site/38fac364b188807e8149e3e7cea5121e)

</details>

<details>
<summary><strong>🧊 냉방전쟁</strong></summary>

<br />

같은 공간에 있는 사람들이 원하는 냉방 온도를 익명 투표로 정하는 웹 서비스입니다.

`Java 21` `Spring Boot` `JPA` `MySQL` `Spring Security` `Swagger` `AWS` `Nginx`

- **UMC 10기 교내 장기 해커톤 우승**
- 투표 방 생성·조회·수정·삭제 API 구현
- Swagger API 문서 인터페이스 분리
- AWS VPC·보안 그룹·EC2·RDS 구성
- GitHub Actions 자동 배포와 Nginx HTTPS 환경 구성
- Spring Security, CORS, 프론트엔드 연동 문제 해결

[Repository](https://github.com/10th-UMC-Hackathon-A/Backend) · [포트폴리오에서 자세히 보기](https://sudden-neptune-99c.notion.site/38fac364b188807e8149e3e7cea5121e)

</details>

<details>
<summary><strong>💠 Private Blockchain Network</strong></summary>

<br />

Raspberry Pi 3대로 센서 데이터를 기록하는 비공개 블록체인 네트워크를 만들고 PoW와 PoA의 성능을 비교했습니다.

`Node.js` `JavaScript` `Raspberry Pi` `SHA-256` `P2P Network`

- 블록·트랜잭션·Genesis Block·Block Header 구현
- SHA-256 기반 블록 해시와 Merkle Root 계산
- 노드 등록, P2P 브로드캐스트, 체인 유효성 검사와 자동 동기화 구현
- PoW와 Authority Node 기반 PoA 구현
- 온·습도 센서 데이터 기록
- 변조된 트랜잭션이 합의를 통해 복구되는 과정 확인

[Repository](https://github.com/gocleanwater/SNS_LAB_Blockchain_2025.12-2025.03) · [포트폴리오에서 자세히 보기](https://sudden-neptune-99c.notion.site/38fac364b188807e8149e3e7cea5121e)

</details>

---

## Education & Activities

- **가천대학교 컴퓨터공학과**  
  Cumulative GPA `4.36 / 4.5` · Major GPA `4.4 / 4.5`
- **SNS Lab 학부연구생 경험**  
  비공개 블록체인과 합의 알고리즘 연구 및 구현
- **UMC 10기 Spring Boot Part Challenger**  
  베스트 워크북 5회 · 교내 장기 해커톤 우승
