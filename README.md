# API 명세서
| 기능 | Method | URL | request | response | 상태코드 |
| --- | --- | --- | --- | --- | --- |
| 일정 생성 | `POST` | /api/schedules | 요청 body | 등록 정보 | 200: 정상 등록 |
| 일정 조회 | `GET` | /api/schedules/{scheduleid} | 요청 param | 다건 응답 정보 | 200: 정상 조회 | 
| 일정 목록 조회 | `GET` | /api/schedules | 요청 param | 단건 응답 정보 | 200: 정상 조회 |
| 일정 수정 | `PUT` | /api/schedules/{scheduleid} | 요청 body | 수정 정보 | 200: 정상 수정 |
| 일정 삭제 | `DELETE` | /api/schedules/{scheduleid} | 요청 param | 삭제 정보 | 200: 정상 삭제 |
