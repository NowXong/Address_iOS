# Address

#### Address book application project using Xcode

#### 제작자 : 송예진


---


### DB(MYSQL) 연결

MySQL Connector Download Link: [MySQL Connector][Connector]

[Connector]: https://dev.mysql.com/downloads/connector/j/8.0.html




### JSP 폴더 내 자료

JSP 폴더 내의 자료는 톰켓 서버 경로(/webapps/ROOT/INMAC/jsp) 안에 'jsp파일'들을 넣어준다.




### JSP와 DB를 연결하기 위한 JSP내 사용자 환경에 맞는 소스 변경 요소들

String url_mysql = "jdbc:mysql://localhost/___데이터베이스 스키마 이름___?serverTimezone=Asia/Seoul&characterEncoding=utf8&useSSL=false";

String id_mysql = "**아이디**";

String pw_mysql = "**암호**";



### CRUD
|Create|Read|Update|Delete|
|------|------|------|------|
|회원가입|로그인|연락처 수정|연락처 삭제|
|연락처 등록|ID/PW 찾기|본인정보 수정|즐겨찾기 해제|
|즐겨찾기 등록|연락처 목록||회원 탈퇴|
||즐겨찾기 목록|||



### 구현 기능들
* 로그인 정보 저장 기능
* 원하는 그룹별 묶어 관리
* 핸드폰 내의 사진을 핸드폰 내에 임시파일로 저장하고 tomcat 서버에 올림
* 즐겨찾는 연락처 사용 가능
