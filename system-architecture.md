# 시스템 아키텍처

![image](https://github.com/user-attachments/assets/cfc17842-c7d7-4cda-81d7-ab186c87c56a)
### 흐름 세부 설명
- 사용자는 oauth2 로그인을 통해 인증/인가 과정(spring security+jwt+oauth2 기반)을 거쳐 서비스를 이용할 수 있음(refresh token은 redis에 저장)
- CI/CD는 Github Actions + Docker 를 활용하여 구성
<br> ➡️코드가 develop 브랜치에 push되면, 해당 브랜치 내용을 기반으로 build하고 docker로 이미지 배포 후 ec2에서 실행
- 서비스 중 실제 place 데이터 조회에 대하여 Google Place API(외부 API)사용
<br> ➡️client에서 플레이스 관련 api 호출 시 server가 관련 데이터를 로컬 DB에서 1차 탐색 후 없으면 외부 API 호출
- 인프라 구성
  - EC2에서 docker 통해 redis 컨테이너와 spring 컨테이너를 관리
  - RdS에서 mariaDB로 일반 데이터 관리, S3에서 이미지 데이터 관리, EC2에 EBS 추가(docker image 용량 확보 위해)
  - ELB로 https 설정
- notion으로 회의록 및 자료(API 명세, 일정, 협업문서 등) 관리, github로 소스코드 관리(Organization 내에서 레포 관리), swagger로 API 명세와 및 테스트
