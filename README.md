
![cruise](https://github.com/dolphin157/projectCruise/assets/102042928/ea7f0410-4ec9-489b-b534-c85c848ce1a1)


<br><br>

<br><br>


# ✨개발동기
![1_개발동기 (1)](https://github.com/eunzzzzz1/projectCruise/assets/139827141/856d3d1e-7da9-4684-871e-b5de46053f61)
![1_개발동기 (2)](https://github.com/eunzzzzz1/projectCruise/assets/139827141/8a1c1ae2-f0b0-4b88-8c84-3776c828546c)
![1_개발동기 (4)](https://github.com/eunzzzzz1/projectCruise/assets/139827141/767b162b-14fe-45d3-a428-7ed91b9c4fb6)



<br><br>

<br><br>

# 📅프로젝트 기간
![2_일정](https://github.com/eunzzzzz1/projectCruise/assets/139827141/a7bf19a0-3f65-4c1b-8d0b-a0fefaba4073)

<br><br>

<br><br>



# 🔧개발환경

- OS : Windows11, Mac
- Frontend : Html5, Css3, Javascript, Jquery, Ajax
- Backend : Java(jdk-11), SpringBoot 2.7.15
- DB : Oracle-xe-11g, MyBatis
- Tools : IntelliJ, Git, Docker
  




<br><br>

<br><br>


# 📊DB 설계
![4_DB설계](https://github.com/eunzzzzz1/projectCruise/assets/139827141/fde770a9-aeb7-4d60-a997-052845d1b199)
<br><br>

<br><br>


# 🧑‍💻구현 기능

### 회원가입, 로그인
<img width="608" alt="스크린샷 2023-10-31 오전 11 39 03" src="https://github.com/dolphin157/projectCruise/assets/102042928/0e704c58-7cd0-4a9b-a73e-5475aef67f77">
<img width="608" src="https://github.com/dolphin157/projectCruise/assets/102042928/099a6e03-1e08-49d5-ad27-dc12089fa208">


- 일반 로그인/회원가입
- 소셜 로그인/회원가입
- 최근 로그인 표기
- Spring Security


### 크루 초대하기
<img width="608" src="https://github.com/dolphin157/projectCruise/assets/102042928/e5193785-53de-4729-93b4-193e90f76698">
<img width="608" src="https://github.com/dolphin157/projectCruise/assets/102042928/3c9b343c-13e1-42e8-8bbd-43a84e95f53d">

- 카카오톡 보내기 API

### 메인 페이지

<img width="608" src="https://github.com/dolphin157/projectCruise/assets/102042928/7966adc1-95fe-4e35-abb1-5e4b6f828285">

- fullpage 플러그인 활용

### 크루 게시판
<img width="608" src="https://github.com/dolphin157/projectCruise/assets/102042928/bafd2108-e2bc-4f00-a5c8-70aa8ea6c633">

- 게시글 목록 조회
- 게시물 등록, 수정, 삭제
- 공지 기능

### 크루 소통 게시판
- 댓글 등록, 수정, 삭제
- 대댓글 등록, 수정, 삭제

### 크루 별 상세페이지
- 크루 소식 조회
- 크루 일정 조회
- 크루 상세정보 조회
- 모임계좌 내역조회
- 멤버 별 회비내역 조회
- 회비 납입

### 크루 별 관리페이지
- 선원 별 회비 조회
- 회비 요청
- 크루 일정 관리
- 크루 정보 수정
- 회원 관리
- 항해 중단

### 마이페이지 메인
- 내 크루 모아보기
- 내 계좌 관리
- 내 일정 모아보기

### 마이페이지 상세
- 내 알림 조회, 삭제
- 내가 쓴 글/댓글 관리
- 회원정보 수정
- 비밀번호 변경

### 실시간 알림
- WebSocket을 이용해 실시간으로 알림 전송


### 크루 만들기

<br><br>

# 🌟문제점
- 일반가입과 소셜가입한 회원간 회원정보의 불일치성
- 서버 재시작시에도 로그인이 유지되는 현상
<br><br>
# 🛠️해결
- 각 소셜 가입마다 가져올 수 있는 정보가 다르다 보니 회원마다 가지고 있는 정보의 불균형이 생겼는데 이를 해소하기 위해 소셜 가입에서는 기본적인 정보만 가져와서 가입을 시키고 추가 정보 입력을 하지 않으면 로그인이 불가능하게 만들어서 해결하였음.
- 서버를 재시작하면 당연히 로그인도 다시 해야 하는데 톰캣의 버전이 높아서 서버를 재시작하거나 심지어 컴퓨터를 껐다 켜도 기존의 세션이 백업이 되는 기능이 있다는 것을 알게 되었고 세션 영속성에 false 값을 줌으로써 해결하였음.



<br><br>

<br><br>


