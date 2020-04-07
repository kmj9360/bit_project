## 팀 프로젝트 - GOODLUXE

* 제 목 : 중고명품 경매 및 거래 사이트 <br/>
* 기 간 : 2개월 (2019/12/23 ~ 2020/2/27) <br/>
* 참여인원 : 5명<br/><br/>


## 제작기간 

* 1주차 ~ 2주차 : 주제선정 및 기능 정리 <br/>
* 3주차 ~ 4주차 : UI 디자인 및 DB 설계 <br/>
* 5주차 ~ 6주차 : UI 구현 <br/>
* 6주차 ~ 9주차 : 기능 구현 및 통합 테스트 <br/>
* 9주차 ~ 10주차 : 오류 테스트 및 마무리 작업 <br/><br/>


## 사용기술

* Front-End : Javascript, HTML5, CSS3, JQuery, Ajax, JSP <br/>
* Back-End : Java, MyBatis, Oracle 11g, Spring Tool Suite 3 <br/>
* Open API : Chart.js, Kakao Developers, NAVER Developers, import, JavaMail <br/>
* Tool : Apache Tomcat 8.5, Apache Commons, Visual Studio Code, eXERD, Axure, Git, Github, SourceTree, Notion <br/><br/>


## 화면구조도

![화면구조도](https://user-images.githubusercontent.com/56961349/78255217-facfef80-7531-11ea-8342-176bff1d62ac.jpg) <br/><br/>


## 내용
* 회원가입 시 구글 SMTP를 이용한 인증, 도로명주소 API 연결 <br/>
* 카카오/네이버 API를 이용한 간편 로그인 <br/>
* 카카오맵 API를 이용한 위치소개 <br/>
* Import를 이용한 카카오페이 결제 <br/>
* 상품 리스트 필터를 이용한 여러가지 조건 적용 <br/>
* 상품 위시리스트/예약/알람 <br/>
* 상품 상세페이지 문의 및 리뷰 <br/>
* 관리자와의 1:1 채팅 <br/>
* 마이페이지 구독정보, 포인트, 활동내역, 회원정보 수정 <br/>
* 관리자 페이지 차트, 회원관리, 결제관리, 개인쉐어상품 수락/거절, 상품 반납처리 <br/><br/>

## 역할 및 페이지 구성 <br/>
#### 위치 : [bit_project/GOODLUXE/src/main/webapp/WEB-INF/views/](https://github.com/kmj9360/bit_project/tree/master/Goodluxe/src/main/webapp/WEB-INF/views)

* 일반 회원가입 _ [joinForm.jsp](https://github.com/kmj9360/bit_project/blob/master/Goodluxe/src/main/webapp/WEB-INF/views/__joinForm.jsp) <br/>
![회원가입페이지](https://user-images.githubusercontent.com/56961349/78282754-c2430c80-7557-11ea-8de8-f7bdb993cb06.jpg) <br/>

  * 유효성검사 및 중복검사 <br/>
  > js를 이용한 유효성검사<br/>
  > ajax를 이용한 실시간중복검사<br/><br/>
![유효성검사](https://user-images.githubusercontent.com/56961349/78292293-c6742780-7561-11ea-89ad-76128079e4d9.gif) <br/>

  * 이메일 인증 <br/>
  > 미인증시 _ [join_email_not_confirmed.jsp](https://github.com/kmj9360/bit_project/blob/master/Goodluxe/src/main/webapp/WEB-INF/views/join_email_not_confirmed.jsp) <br/>
![이메일미인증](https://user-images.githubusercontent.com/56961349/78307381-b3248480-7580-11ea-962e-6c51c25fe346.gif) <br/>
  > 인증 시 _ [join_email_confirmed.jsp](https://github.com/kmj9360/bit_project/blob/master/Goodluxe/src/main/webapp/WEB-INF/views/join_email_confirmed.jsp) <br/>
![이메일인증_인증시](https://user-images.githubusercontent.com/56961349/78633519-cd41c800-78dc-11ea-97cb-14a4e7c73a2f.gif)<br/>

* 간편 회원가입<br/>
  * 카카오<br/>
![카카오간편로그인](https://user-images.githubusercontent.com/56961349/78633404-8227b500-78dc-11ea-9217-f9e9d9731ddf.gif) <br/>

  * 네이버<br/>
![네이버간편로그인](https://user-images.githubusercontent.com/56961349/78633426-979cdf00-78dc-11ea-8a29-752d1e433d3a.gif) <br/>
