# SchoolHelper
제천고등학교 코딩연구소 동아리 프로젝트

교내 개인시간표 및 식단을 위한 백엔드 서버

## 시간표 
### 엔드포인트
`GET /timetable`

### 파라미터
- grade (필수): 학생의 학년
- class (필수): 학생의 반
- id (필수): 학생의 ID
- year (선택): 날짜의 연도. 기본값은 현재 연도입니다.
- month (선택): 날짜의 월. 기본값은 현재 월입니다.
- day (선택): 날짜의 일. 기본값은 현재 일입니다.

## 식단 컨트롤러
### 엔드포인트
`GET /meal`
### 파라미터
- year (선택): 날짜의 연도. 기본값은 현재 연도입니다.
- month (선택): 날짜의 월. 기본값은 현재 월입니다.
- day (선택): 날짜의 일. 기본값은 현재 일입니다.
