leafmap 문서 및 자료 공개용 레포입니다.
원본 협업 레포는 이전 키 노출 이슈와 스토어 배포 준비 중으로 private하게 관리되고 있습니다.

# Leafmap
플레이스 기반 노트 아카이빙 서비스

### 개요
장소 공간에서의 경험들을 노트로 기록하며 공유하고, 스탬프를 통해 성취감을 높이는 안드로이드 어플리케이션

**개발 기간**
기획 2024.03 - 2024.08

개발 및 테스트 2024.09 - 

**담당 역할** 
프로젝트 기획, 일정 관리, 백엔드 API 설계 및 구현, CI/CD, 서버 환경 구축 및 모니터링, 테스트 피드백 

---
### 사용 기술
Spring boot, jpa, Spring security+JWT+OAuth, mariaDB, redis, Flutter, AWS(EC2, RDS, S3), Github Action, Docker, Google Place API, Git, Notion

### 주요 기여 내용
- 전반적인 프로젝트 기획 및 지속적인 수정 / ERD 설계
- API 엔드포인트 10개 이상 설계 및 개발 (Swagger기준 Note, Folder, Scrap, Notification)
- 인프라 구축 및 관리
- CI/CD
- 이슈 발생 시 로그 기반 원인 분석 및 공유
- FCM 푸시 알림 구현(백에서는 구현 완료했지만, 배포는 프론트 준비 상황에 따라 대기 중)
- 기존 구현된 인증 구조(Spring security+Jwt+OAuth2) 유지보수
- 예외처리 설계 및 개발
- Redis 캐싱 구현
- 팀 협업 및 일정 관리, 문서화

### 시스템 아키텍쳐
[시스템 아키텍쳐 이미지 삽입 예정

### ERD
[ERD 이미지 삽입 예정

### API 문서(Swagger)
[Swagger API 목록 이미지 삽입 예정
Swagger 링크

### CICD
**Github Actions를 통해 develop 브랜치 push 시 자동 docker 이미지 빌드**
**Docker compose로 Spring boot app + redis 컨테이너 구성**
AWS EC2 서버에 무중단 배포 적용
초기 Jenkins로 배포 시도 → 용량 이슈로 Github Actions로 전환

---
>블로그 링크: 
### Trouble Shooting
트러블 슈팅은 기술 블로그에 정리하고 있으며, 아래는 leafmap 프로젝트를 하며 진행한 트러블슈팅 목록입니다.

### 프로젝트 회고
이런 점을 배웠습니다.

더 자세한 회고는 블로그에 정리중입니다.

