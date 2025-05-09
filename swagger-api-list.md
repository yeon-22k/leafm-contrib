# Swagger API 목록 및 관련 doc
![image](https://github.com/user-attachments/assets/c2d3fb46-013a-492d-b8fd-bb09c9b8e947)

### 📃API 목록

| 그룹 | 기능 | 메서드 | 경로 | 본인 작업 API |
|------|------|-----------|------|------|
| MyPage | 프로필 이미지 삭제 | ![DELETE](https://img.shields.io/badge/DELETE-F44336?style=flat) | /mypage/edit/image |  |
| MyPage | 마이페이지 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /mypage |
| MyPage | 구독한 사용자 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /mypage/subscriptions |
| MyPage | 스크랩 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /mypage/scraps |
| MyPage | 프로필 수정 | ![PATCH](https://img.shields.io/badge/PATCH-FFC107?style=flat) | /mypage/edit |
| QnA | 문의 삭제 | ![DELETE](https://img.shields.io/badge/DELETE-F44336?style=flat) | /inquiry/{inquiryId} |
| QnA | 문의 내역 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /inquiry |
| QnA | 문의 상세 조회 및 답변 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /inquiry/{inquiryId} |
| QnA | 문의 수정 | ![PATCH](https://img.shields.io/badge/PATCH-FFC107?style=flat) | /inquiry/{inquiryId} |
| QnA | 문의하기 | ![POST](https://img.shields.io/badge/POST-4CAF50?style=flat) | /inquiry |
| User | 사용자 구독 및 취소 | ![POST](https://img.shields.io/badge/POST-4CAF50?style=flat) | /subscriptions/{userId} |
| Scrap | 하트 삭제 및 스크랩 취소 | ![DELETE](https://img.shields.io/badge/DELETE-F44336?style=flat) | /note/{noteId} | ✔️ |
| Scrap | 하트 삭제 및 스크랩 취소 | ![DELETE](https://img.shields.io/badge/DELETE-F44336?style=flat) | /mypage/scraps/{noteId} | ✔️ |
| Scrap | 하트 추가 및 스크랩 | ![POST](https://img.shields.io/badge/POST-4CAF50?style=flat) | /note/{noteId} | ✔️ |
| OAuth2 | OAuth2 로그인 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /api/v1/auth/login/{provider} |
| OAuth2 | Access Token 재발급 | ![POST](https://img.shields.io/badge/POST-4CAF50?style=flat) | /api/v1/auth/reissue-token |
| Place | 플레이스 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /places |
| Place | 플레이스 상세 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /places/{placeId} |
| Challenge | 챌린지(스탬프) 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /challenge |
| Notification | 알림 목록 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /notification |✔️ |
| Notification | 알림 클릭 시 리디렉션 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /notification/redirection |✔️ |
| Notification | Fcm 토큰 받기 | ![POST](https://img.shields.io/badge/POST-4CAF50?style=flat) | /fcm |✔️ |
| Folder | 폴더 삭제 | ![DELETE](https://img.shields.io/badge/DELETE-F44336?style=flat) | /folder |✔️ |
| Folder | 폴더 해금(=챌린지 T/F)가능 여부 체크 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /folder |✔️ |
| Folder | 본인 폴더 목록 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /folders |✔️ |
| Folder | 타 사용자 폴더 목록 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /folder/{userId} |✔️ |
| Folder | 폴더 수정 | ![PATCH](https://img.shields.io/badge/PATCH-FFC107?style=flat) | /folder/{folderId} |✔️ |
| Folder | 폴더 생성 | ![POST](https://img.shields.io/badge/POST-4CAF50?style=flat) | /folder |✔️ |
| Note | 하트 삭제 및 스크랩 취소 | ![DELETE](https://img.shields.io/badge/DELETE-F44336?style=flat) | /note/{noteId} | ✔️ |
| Note | 타 사용자 노트 상세 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /note/{noteId} | ✔️ |
| Note | 지역 필터링 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /notes/{folderName}/{regionName} | ✔️ |
| Note | 타 사용자 폴더 내 노트 목록 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /notes/{folderId} | ✔️ |
| Note | 본인 폴더 내 노트 목록 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /notes/my/{folderId} | ✔️ |
| Note | 본인 노트 상세 조회 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /note/my/{noteId} | ✔️ |
| Note | 노트 생성 | ![POST](https://img.shields.io/badge/POST-4CAF50?style=flat) | /note | ✔️ |
| Note | 노트 수정 | PUT | /note/{noteId} | ✔️ |
| Health | 헬스 체크 | ![GET](https://img.shields.io/badge/GET-2196F3?style=flat) | /healthz-check | ✔️ |

### ✏️Swagger API 설계 일부
GET > POST > PATCH > DELETE 순입니다.
<table>
<tr>
  <td valign="top"><img src="https://github.com/user-attachments/assets/1fe33ca0-fb10-46c5-be08-329d7219df40" width="100%"></td>
  <td valign="top"><img src="https://github.com/user-attachments/assets/76469d42-8898-4787-a6f2-d02c3bcd7e10" width="100%"></td>
  <td valign="top"><img src="https://github.com/user-attachments/assets/512e40de-050e-4a1d-81e0-90bb16e85544" width="100%"></td>
  <td valign="top"><img src="https://github.com/user-attachments/assets/9871e882-e236-4bbc-8c8b-912519c78f41" width="100%"></td>
</tr>
</table>

<br>
