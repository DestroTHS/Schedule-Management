Chapter3-일정관리 앱
<br>   

##  API 명세
### 일정 API
 기능           | Method | URL                     | Request  | Response | 상태코드      
|--------------|--------|-------------------------|----------|----------|-----------|
| 일정 생성        | POST   | /schedules              | 요청 body  | 등록 정보    | 201: 정상등록 |
| 전체 일정 조회     | GET    | /schedules              | 요청 param | 다건 응답 정보 | 200: 정상조회 |
| 전체 일정 조회 페이징 | GET    | /schedules/paging       | 요청 param | 다건 응답 정보 | 200: 정상조회 |
| 선택 일정 조회     | GET    | /schedules/{scheduleId} | -        | 단건 응답 정보 | 200: 정상조회 |
| 선택 일정 수정     | PATCH  | /schedules/{scheduleId} | 요청 body  | 수정 정보    | 200: 정상수정 |
| 선택 일정 삭제     | DELETE | /schedules/{scheduleId} | 요청 body  | -        | 200: 정상삭제 |


### 작성자 API
 기능        | Method | URL               | Request  | Response | 상태코드      
|-----------|--------|-------------------|----------|----------|-----------|
| 사용자 생성    | POST   | /users            | 요청 body  | 등록 정보    | 201: 정상등록 |
| 전체 사용자 조회 | GET    | /users            | 요청 param | 다건 응답 정보 | 200: 정상조회 |
| 선택 사용자 조회 | GET    | /users/{userId}   | -        | 단건 응답 정보 | 200: 정상조회 |
| 선택 사용자 수정 | PATCH    | /users/{userId} | 요청 body  | 수정 정보    | 200: 정상수정 |
| 선택 사용자 삭제   | DELETE    | /users/{userId} | -        | -        | 200: 정상삭제 |

## ERD
![image](https://github.com/user-attachments/assets/69462af3-a3be-4498-a5fd-0593cbd439c6)# Schedule-Management

