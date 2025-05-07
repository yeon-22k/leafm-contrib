# leafm-contrib

✔️**개인 포트폴리오용으로 정리된 레포지토리입니다.**

프로젝트 **Leafmap**의 핵심 아이디어 및 설계 내용과 직접 구현하고 기여한 내용을 정리한 개인 아카이브입니다.  
스토어 배포 준비 중으로 원본 코드는 포함되어 있지 않으며 요청 시 일부 제공 가능합니다.

---

### 🌿Leafmap
플레이스 기반 노트 아카이빙 서비스 <br>
장소 공간에서의 경험들을 노트로 기록하며 공유하고, 스탬프를 통해 성취감을 높이는 안드로이드 어플리케이션

**담당 역할** :
프로젝트 기획, 일정 관리, 백엔드 API 설계 및 구현, CI/CD, 서버 환경 구축 및 모니터링, 테스트 피드백 

**사용 기술** : <br>
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-007396?style=flat&logo=hibernate&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat&logo=spring-security&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-3C5A99?style=flat&logo=oauth&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat&logo=amazon-ec2&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat&logo=amazon-rds&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat&logo=amazon-s3&logoColor=white)
<br>
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Google Place API](https://img.shields.io/badge/Google%20Place%20API-4285F4?style=flat&logo=google&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=black)

**기타문서** : <br>
- [ERD](https://github.com/yeon-22k/leafm-contrib/blob/브랜치명/경로/파일명)
- [시스템 아키텍처](https://github.com/yeon-22k/leafm-contrib/blob/브랜치명/경로/파일명)
- [Swagger API 목록](https://github.com/yeon-22k/leafm-contrib/blob/브랜치명/경로/파일명)

---

### 🛠️주요 기여 내용
- 전반적인 프로젝트 기획 및 지속적인 수정 / ERD 설계
- API 엔드포인트 10개 이상 설계 및 개발 (Swagger기준 Note, Folder, Scrap, Notification)
- 서버 인프라 구축 및 관리
- CI/CD 파이프라인 구현
- 이슈 발생 시 로그 기반 원인 분석 및 공유
- FCM 푸시 알림 구현(백에서는 구현 완료했지만, 배포는 프론트 준비 상황에 따라 대기 중)
- 기존 구현된 인증 구조(Spring security+Jwt+OAuth2) 유지보수
- 반복되는 체크로직 공통 클래스 설계 및 개발
- 보안 이슈 대응
- 팀 협업 및 일정 관리, 문서화

>📚관련 회고 및 트러블슈팅은 [기술 블로그](https://velog.io/@yeon22)에서 확인하실 수 있습니다.
