# 🦄 Shall We Pets! 🐠

## 💻 `프로젝트 소개`
‘위치기반 반려동물 동반 장소 추천 서비스’
<br/>
후보 프로젝트들의 과거(변경점), 현재(규모), 미래(성장 가능성)을 모두 고려했을 때 반려동물 사업이 타 프로젝트에 비해 가장 투자 가치가 높다고 판단하여 선정하였습니다.

<br/>

##  ⌨️ `개발 기간`
9.26 ~ 10.11

<br/>

## 🧑‍🤝‍🧑 `멤버구성`
 - 팀장 : 배하은
 - 형상관리자1 : 홍주연
 - 형상관리자2 : 이득규
 - 서기 : 이규섭
 - 리뷰어 : 이의정

<br/>

## ⚙️ `개발 환경`
![skills](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![skills](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)
![skills](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![skills](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![skills](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![skills](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![skills](https://img.shields.io/badge/axios-671ddf?&style=for-the-badge&logo=axios&logoColor=white)
![skills](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)

![skills](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![skills](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![skills](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![skills](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=Spring-Security&logoColor=white)
![skills](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)
![skills](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![skills](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![skills](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white)

![skills](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![skills](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![skills](https://img.shields.io/badge/Sourcetree-0052CC?style=for-the-badge&logo=Sourcetree&logoColor=white)
![skills](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)
![skills](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![skills](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![skills](https://img.shields.io/badge/Canva-%2300C4CC.svg?&style=for-the-badge&logo=Canva&logoColor=white)
![skills](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)


<br/><h2>📂 패키지구조</h2>

<details>
  <summary><b>프론트엔드 패키지 구조</b></summary>
  <div markdown="1">

```
C:.
|   App.css
|   App.js
|   index.js
|   Store.js
|
+---apis
|       API.js
|       BookmarkAPICalls.js
|       BusinessAPI.js
|       ImagesAPICalls.js
|       MemberAPICalls.js
|       MyInfoAPICalls.js
|       PointAPI.js
|       PostAPICalls.js
|       PostRegisterAPICalls.js
|       ReviewAPICalls.js
|       VerificationAPI.js
|
+---build
|       favicon.ico
|       logo192.png
|       logo512.png
|       manifest.json
|       robots.txt
|
+---components
|   +---commons
|   |       Footer.css
|   |       Footer.js
|   |       Footer_bg.css
|   |       Footer_bg.js
|   |       Header.css
|   |       Header.js
|   |       Navbar_Mypage.css
|   |       Navbar_MyPage.js
|   |
|   +---form
|   |       ChangePwdNotLoggedInForm.js
|   |       FindIdForm.js
|   |       FindPwdForm.js
|   |       LoginForm.js
|   |       PostListForm.js
|   |       SignUpForm.js
|   |       TestImages.js
|   |
|   +---items
|   |       BusinessDetail.js
|   |
|   \---lists
|           BusinessList.js
|
+---images
|       123.PNG
|       187803-200.png
|       2 2.png
|       7.png
|       ApplyDetailDefault.png
|       Arrow 2.png
|       Arrow.png
|       arrow_back.png
|       backicon.png
|       business_def_img.jpg
|       cancel_icon.png
|       charactor.avatar.png
|       Clock.png
|       cloud1.png
|       cloud2.png
|       cloud3.png
|       default_pfp.png
|       directions_car.png
|       down.png
|       eowjs.png
|       Globe.png
|       Heart.png
|       Icon.png
|       location_on.png
|       Main-boy&dog.png
|       Main-circle-1.png
|       Main-circle-2.png
|       Main-flower-left.png
|       Main-flower-right.png
|       Main-girl&dog.png
|       marking.png
|       pension.png
|       Phone.png
|       photo_icon.png
|       plus.png
|       post_def_pic.png
|       post_detail_def_pic.png
|       puppy1.jpg
|       puppy2.jpg
|       reviewpic.jpg
|       reviewpic2.jpg
|       reviewpic3.jpg
|       reviewpic4.jpg
|       reviewpic5.jpg
|       reviewpic6.jpg
|       reviwImage1.png
|       SC-cafe.png
|       SC-circle.png
|       SC-cultrue.png
|       SC-hospital.png
|       SC-service.png
|       SC-trip.png
|       Search.png
|       securityad1.png
|       securityad2.png
|       seoul (2).png
|       seoul.png
|       shallwepets_business_pic.png
|       shallwepets_business_pic1.png
|       shallwepets_logo.png
|       share.png
|       sharing.png
|       Star.png
|       star_filled.png
|       up.png
|       강원.png
|       광주.png
|       부산.png
|       인천.png
|       잔디밭.png
|       제주.png
|
+---layouts
|       Layout.css
|       Layout.js
|       Layout_bg.js
|       Layout_Mypage.css
|       Layout_MyPage.js
|
+---modules
|       index.js
|       MemberModule.js
|
\---pages
    +---admin
    |   |   AdminMenu.css
    |   |   AdminMenu.js
    |   |
    |   +---business
    |   |       AppliedList.js
    |   |       ApplyDetail.css
    |   |       ApplyDetail.js
    |   |       BusinessList.js
    |   |       BusinessMenu.js
    |   |
    |   \---member
    |           MemberDetail.css
    |           MemberDetail.js
    |           MemberList.js
    |           MemberMenu.js
    |           NavBar.css
    |           NavBar.js
    |           PointDetail.css
    |           PointDetail.js
    |           PointList.js
    |           ReviewList.css
    |           ReviewList.js
    |
    +---chat
    |       ChatApp.css
    |       ChatApp.js
    |       ChatHeader.js
    |       ChatInput.js
    |       ChatRoom.js
    |       ChatRoomList.js
    |       MessageList.js
    |       TokenUtils.js
    |
    +---global
    |       PrivacyPolicy.css
    |       PrivacyPolicy.js
    |       TermsOfUse.css
    |       TermsOfUse.js
    |
    +---location
    |       Directions.css
    |       Directions.js
    |       Map.js
    |       SelectLocation.css
    |       SelectLocation.js
    |
    +---main
    |       Main.css
    |       Main.js
    |       SelectCategory.css
    |       SelectCategory.js
    |       SelectCity.css
    |       SelectCity.js
    |
    +---member
    |       ChangePwdNotLoggedIn.css
    |       ChangePwdNotLoggedIn.js
    |       FindId.css
    |       FindId.js
    |       FindPwd.css
    |       FindPwd.js
    |       Login.css
    |       Login.js
    |       SignUp.css
    |       SignUp.js
    |
    +---mypage
    |       Bookmark.css
    |       Bookmark.js
    |       BusinessRegister.css
    |       BusinessRegister.js
    |       ChangePassword.css
    |       ChangePassword.js
    |       ChatHistory.js
    |       DeleteAccount.css
    |       DeleteAccount.js
    |       MyBusinessDetail.css
    |       MyBusinessDetail.js
    |       MyBusinessList.css
    |       MyBusinessList.js
    |       MyInfo.css
    |       MyInfo.js
    |       MyReviewList.css
    |       MyReviewList.js
    |       PointHistory.css
    |       PointHistory.js
    |
    \---post
            PostDetail.css
            PostDetail.js
            PostList.css
            PostList.js
```
    
  </div>
</details>


<details>
  <summary><b>백엔드 패키지 구조</b></summary>
  <div markdown="1">

```
C:.
+---main
|   +---java
|   |   \---com
|   |       \---ohdaesan
|   |           \---shallwepets
|   |               |   ShallWePetsBackApplication.java
|   |               |
|   |               +---auth
|   |               |   +---common
|   |               |   |       AuthConstants.java
|   |               |   |
|   |               |   +---config
|   |               |   |       BeanConfiguration.java
|   |               |   |       S3Config.java
|   |               |   |       SwaggerConfig.java
|   |               |   |       WebConfig.java
|   |               |   |       WebSecurityConfig.java
|   |               |   |
|   |               |   +---filter
|   |               |   |       CustomAuthenticationFilter.java
|   |               |   |       HeaderFilter.java
|   |               |   |       JwtAuthorizationFilter.java
|   |               |   |
|   |               |   +---handler
|   |               |   |       CustomAuthenticationProvider.java
|   |               |   |       CustomAuthFailUserHandler.java
|   |               |   |       CustomAuthSuccessHandler.java
|   |               |   |
|   |               |   +---service
|   |               |   |       CustomUserDetails.java
|   |               |   |       CustomUserDetailService.java
|   |               |   |
|   |               |   \---util
|   |               |           ConvertUtil.java
|   |               |           TokenUtils.java
|   |               |
|   |               +---bookmark
|   |               |   +---controller
|   |               |   |       BookmarkController.java
|   |               |   |
|   |               |   +---domain
|   |               |   |   +---dto
|   |               |   |   |       BookmarkDTO.java
|   |               |   |   |
|   |               |   |   \---entity
|   |               |   |           Bookmark.java
|   |               |   |
|   |               |   +---repository
|   |               |   |       BookmarkRepository.java
|   |               |   |
|   |               |   \---service
|   |               |           BookmarkService.java
|   |               |
|   |               +---chattingRoom
|   |               |   +---config
|   |               |   |       CorsConfig.java
|   |               |   |       WebSocketConfig.java
|   |               |   |
|   |               |   +---controller
|   |               |   |       ChattingRoomController.java
|   |               |   |
|   |               |   +---domain
|   |               |   |   +---dto
|   |               |   |   |       ChattingRoomDTO.java
|   |               |   |   |
|   |               |   |   \---entity
|   |               |   |           ChattingRoomEntity.java
|   |               |   |
|   |               |   +---handler
|   |               |   |       ChatWebSocketHandler.java
|   |               |   |
|   |               |   +---repository
|   |               |   |       ChattingRoomRepository.java
|   |               |   |
|   |               |   \---service
|   |               |           ChattingRoomService.java
|   |               |
|   |               +---csvR
|   |               |   \---controller
|   |               |           CsvToDbController.java
|   |               |
|   |               +---global
|   |               |       ErrorController.java
|   |               |       ErrorResponse.java
|   |               |       PostNotFoundException.java
|   |               |       ResponseDTO.java
|   |               |       UserStatusException.java
|   |               |
|   |               +---images
|   |               |   +---controller
|   |               |   |       ImagesController.java
|   |               |   |
|   |               |   +---domain
|   |               |   |   +---dto
|   |               |   |   |       ImagesDTO.java
|   |               |   |   |
|   |               |   |   \---entity
|   |               |   |           Images.java
|   |               |   |
|   |               |   +---repository
|   |               |   |       ImagesRepository.java
|   |               |   |
|   |               |   \---service
|   |               |           ImagesService.java
|   |               |           S3Service.java
|   |               |
|   |               +---member
|   |               |   +---controller
|   |               |   |       MemberController.java
|   |               |   |       MyPageController.java
|   |               |   |
|   |               |   +---domain
|   |               |   |   +---dto
|   |               |   |   |       ChangePasswordDTO.java
|   |               |   |   |       MemberDTO.java
|   |               |   |   |
|   |               |   |   \---entity
|   |               |   |           Grade.java
|   |               |   |           Member.java
|   |               |   |           RoleType.java
|   |               |   |           Status.java
|   |               |   |
|   |               |   +---repository
|   |               |   |       MemberRepository.java
|   |               |   |
|   |               |   \---service
|   |               |           MemberService.java
|   |               |           MyPageService.java
|   |               |
|   |               +---message
|   |               |   +---controller
|   |               |   |       MessageController.java
|   |               |   |
|   |               |   +---domain
|   |               |   |   +---dto
|   |               |   |   |       MessageDTO.java
|   |               |   |   |
|   |               |   |   \---entity
|   |               |   |           MessageEntity.java
|   |               |   |
|   |               |   +---repository
|   |               |   |       MessageRepository.java
|   |               |   |
|   |               |   \---service
|   |               |           MessageService.java
|   |               |
|   |               +---point
|   |               |   +---controller
|   |               |   |       PointController.java
|   |               |   |
|   |               |   +---domain
|   |               |   |   +---dto
|   |               |   |   |       PointDTO.java
|   |               |   |   |
|   |               |   |   \---entity
|   |               |   |           Point.java
|   |               |   |
|   |               |   +---repository
|   |               |   |       PointRepository.java
|   |               |   |
|   |               |   \---service
|   |               |           PointService.java
|   |               |
|   |               +---post
|   |               |   +---controller
|   |               |   |       BusinessController.java
|   |               |   |       PostController.java
|   |               |   |
|   |               |   +---domain
|   |               |   |   +---dto
|   |               |   |   |       BusinessDTO.java
|   |               |   |   |       PostDTO.java
|   |               |   |   |       PostImagesDTO.java
|   |               |   |   |       PostSummaryDTO.java
|   |               |   |   |
|   |               |   |   \---entity
|   |               |   |           Post.java
|   |               |   |           PostImages.java
|   |               |   |           Status.java
|   |               |   |
|   |               |   +---repository
|   |               |   |       PostImagesRepository.java
|   |               |   |       PostRepository.java
|   |               |   |
|   |               |   \---service
|   |               |           BusinessService.java
|   |               |           PostService.java
|   |               |
|   |               +---review
|   |               |   +---controller
|   |               |   |       ReviewController.java
|   |               |   |
|   |               |   +---domain
|   |               |   |   +---dto
|   |               |   |   |       ExtendedReviewDTO.java
|   |               |   |   |       ReviewDTO.java
|   |               |   |   |       ReviewImagesDTO.java
|   |               |   |   |       ReviewUpdateRequestDTO.java
|   |               |   |   |
|   |               |   |   \---entity
|   |               |   |           Review.java
|   |               |   |           ReviewImages.java
|   |               |   |
|   |               |   +---repository
|   |               |   |       ReviewImagesRepository.java
|   |               |   |       ReviewRepository.java
|   |               |   |
|   |               |   \---service
|   |               |           ReviewService.java
|   |               |
|   |               \---verification
|   |                   |   MailManager.java
|   |                   |   SHA256Util.java
|   |                   |
|   |                   +---controller
|   |                   |       MailController.java
|   |                   |       SMSController.java
|   |                   |
|   |                   \---service
|   |                           SMSService.java
|   |
|   \---resources
|       |   application.yml
|       |
|       +---static
|       |   |   post.csv
|       |   |
|       |   \---images
|       |           1727858353518_bananacat.jpg
|       |           1728289445113_bananacat.jpg
|       |
|       \---templates
\---test
    \---java


        \---com
            \---ohdaesan
                \---shallwepets
                        ShallWePetsBackApplicationTests.java
```
    
  </div>
</details>


<br/><h2>📌 주요 기능</h2>

<h3>🐣 회원가입 🐥</h3>

- 아이디, 닉네임 중복 체크
- 이메일 인증
- 휴대폰 번호 인증
- 인증번호 확인되면 더 이상 이메일과 휴대폰 번호 변경 불가
- 우편번호 찾기
- 프로필 사진 추가 가능
- 프로필 사진 크롭 기능 (정방형으로 자동 세팅, 초기화 가능)
- 약관 보기 또는 footer의 약관 클릭 시 약관/개인정보처리방침 자세히 보기 가능
- 필수 입력란, 버튼 클릭, 약관 모두 동의해야만 가입하기 버튼 활성화
- 만약 같은 이메일이나 휴대폰으로 가입이 되어있으면 재가입 불가

<br/><h3>🐋 로그인 🦭</h3>

- 아이디 저장 누르고 로그인 시 로그아웃 후에도 아이디 계속 저장
- 존재하지 않는 정보로 로그인 시도 시 경고문구 띄우고 로그인 방지
- 탈퇴회원이나 정지회원이 로그인 시도 시 로그인 방지

<br/><h3>🐷 아이디 찾기 🐽</h3>

- 토글로 이메일 또는 휴대전화 번호로 아이디 찾기 가능
- 이메일 인증
- 휴대폰 번호 인증
- 인증 시 존재하지 않는 아이디면 정보 재검토 요청
- 존재하는 회원의 정보와 일치하면 팝업창으로 아이디를 띄워주고 확인 버튼을 누르면 로그인 페이지로 이동

<br/><h3>🐼 비밀번호 찾기(변경) 🐾</h3>

- 토글로 이메일 또는 휴대전화 번호로 비밀번호 찾기(변경) 가능
- 이메일 인증
- 휴대폰 번호 인증
- 존재하는 회원의 정보와 일치하는 정보 입력 시 다음 페이지에서 새로운 비밀번호로 변경 가능
- 기존 비밀번호와 일치하는 비밀번호 입력 시 또는 비밀번호 정규식과 다르면 경고 문구 띄우고 비밀번호 변경 방지
- 조건에 맞는 비밀번호를 다시 입력하고 저장 시 바뀐 비밀번호로 로그인 할 수 있도록 로그인 화면으로 이동

<br/><h3>🦢 장소 목록 페이지 🦢</h3>

- 사용자가 도시/카테고리를 고르지 않고 바로 장소 목록 링크로 접속 시 서비스 선택 페이지로 이동하여 사용자 실수 방지
- 도시와 카테고리 선택 시 해당하는 장소 목록이 보여짐
- 장소마다 업체가 등록한 사진이나 리뷰에 업로드한 사진이 있으면 최신순으로 최대 5개까지 보여주고 만약 없으면 디폴트 사진을 보여줌
- 불러올 장소 수가 많을 경우를 대비해서 목록을 한 번에 가져오지 않고 스크롤 내릴때마다 일정 양을 불러오게끔 페이징 처리
- 지역 필터링 - 해당 시군구에 있는 장소만 가져오기
- 검색어 필터링 - 유저가 입력한 검색어가 포함된 장소만 필터링해서 가져오기

<br/><h3>🐠 장소 상세 페이지 🐟</h3>

- 헤더에 장소에 업체가 등록한 사진이나 리뷰에 업로드한 사진이 있으면 최신순으로 최대 5개까지 보여주고 만약 없으면 디폴트 사진을 보여줌
- 장소 평균 별점과 해당 장소에 등록된 리뷰 수 조회
- useEffect를 이용한 탭(정보, 리뷰, 사진) 변경
- 북마크 생성, 북마크 삭제
- 공유하기 버튼으로 링크 복사
- 정보 더보기 토글을 이용하여 장소 정보를 추가 정보를 보거나 필수 정보만 보기 가능
- 리뷰 탭에서 최신순/오래된순으로 보거나 사진 리뷰만 필터링 가능
- 로그인 했을 경우에는 별점 리뷰/텍스트 리뷰/사진 리뷰 작성 가능
- 등록된 리뷰가 본인이 쓴 리뷰면 수정/삭제 바로 가능
- 사진 탭을 클릭하거나 장소에 등록되어있는 사진이 5장 이상일 경우에는 5번째 헤더 사진을 클릭하면 사진 탭으로 이동
- 한 번에 일정 수의 사진만 불러오게끔 페이징 처리
- 사진을 클릭하면 팝업창으로 실제 비율로 사진 보기 가능

<br/><h3>🙈 관리자 페이지 🙉</h3>

- 회원 전체 조회, 회원 상세 조회, 회원 삭제, 회원의 업체 조회
- 전체 리뷰 조회, 필터, 리뷰 관리
- 회원 업체 승인 및 반려, 회원 업체 삭제, 업체 승인 정보 조회
- 회원 포인트 조회, 포인트 관리(포인트 수 조정)

<br/>

## 🗣️ 후기

>- 배하은 🍀: 이번 프로젝트는 제가 이전에 학습했던 내용을 복습하고 최대로 활용할 수 있는 좋은 기회였습니다. 특히 PostDetail 페이지에서 많은 기능을 구현하기 위해 CSS와 리액트 폼을 효율적으로 구성한 부분이 개인적으로 매우 만족스럽다.
수업시간에 배웠던 내용을 실제로 구현 연습하면서 API 호출 및 데이터 처리의 기초부터 심화 과정까지 많은 것을 경험할 수 있었습니다. 그중에서도 가장 기억에 남는 부분은 CSV 파일을 데이터베이스에 넣는 작업이었습니다. 처음에는 파일의 32개 열을 맞춰 정렬하고 각 컬럼에 맞게 데이터를 배치하는 과정이 생각보다 복잡하고 어려웠습니다. 데이터 양이 워낙 방대했기 때문에 실수를 줄이기 위해 여러 번 시행착오를 거쳐야 했고, 그 과정에서 많은 시간을 할애했지만 결과적으로 데이터베이스의 구조를 이해하는 데 큰 도움이 되었습니다. 다만, 아쉬웠던 점은 프로젝트의 완성도였습니다. WBS에 따라 프로젝트를 착실히 진행했지만, 후반부에 예상치 못한 오류를 해결하는 데 시간이 오래 걸리면서 전체 일정이 다소 촉박하게 마무리되었습니다. 특히 일부 오류를 해결하는 과정에서 시간이 지체되었고, 이러한 부분이 프로젝트 완성도에 영향을 주어 아쉬웠습니다. 이번 프로젝트를 통해 배운 것들을 바탕으로 다음 프로젝트에서는 더 나은 결과물을 만들어낼 수 있을 것 같습니다. 특히, API와의 연결 작업에서 얻은 경험을 바탕으로 더 효율적으로 백엔드와 프론트엔드를 통합하고, 데이터를 주고받는 기능을 더욱 능숙하게 구현할 수 있을 것 같습니다. 


<br/>

>- 홍주연 🐬: 이전 팀 프로젝트 경험을 바탕으로 직전에 했던 프로젝트보다 다들 속도도 빨라지고 충돌도 더 잘 해결했다고 생각합니다. 기능도 훨씬 복잡해지고 서로 참조하는 테이블 수도 늘어나니 코드도 길어지고 파일 수도 많아졌는데도 다들 큰 문제 없이 계획했던 기능을 거의 마무리지은 것 같아 좋았습니다. 이번 프로젝트에서는 외부 api를 사용해서 기능의 범위도 확장되고 사용하는 데이터의 양도 훨씬 커져서 더욱 다양한 기능을 구현할 수 있어서 좋은 경험이 되었습니다. 특히 채팅이나 길찾기 등 처음 적용시켜보는 생소한 기능들도 완성도 높게 구현해주셔서 나중에 더 다양한 기능을 시도해볼 수 있겠다는 동기가 되었습니다! 다만 조금 아쉬웠던 점은 최종 머지를 좀 더 일찍 진행해서 오류 수정과 점검을 좀 더 여유롭게 했어야하는데 중간중간 각자 맡은 역할이나 기능이 조금씩 수정되다보니 최종 결과물을 확인할 시간을 충분히 두지 못했다는 점입니다. 다음 프로젝트에서는 계획수립 단계에서 일정을 좀 더 꼼꼼하게 세우고 우선순위를 두어 계획을 최대한 수정하는 일이 없도록 해야겠다고 생각했습니다. 또한 형상관리자로서 머지할 때 꼭 충돌이 나지 않더라도 다른 팀원과 공동으로 사용한 파일에 대해서는 다시 한번 더 재검토하게끔 유도하고 확인했어야하는데 그러지 못한 것 같습니다. 머지 전에는 작동하던 부분도 충돌이 나지 않아 확인과정을 거치지 않고 머지한 후 오류가 나는 부분이 나중에 발견되는 경우가 종종 있었습니다. 다음 프로젝트 때는 이런 실수가 반복되지 않도록 개선하려고 합니다!

<br/>

>-- 이규섭:

<br/>

>-- 이득규:

<br/>


<br/>

## 🦋 Shall We Pets 웹 스크린 구성 및 기능

| **메인페이지** |  **서비스 선택**  |  **도시 선택** |
| :---:|:---:|:---:|
| <img align="center" alt="메인페이지" src="./img/메인.PNG" width="240px" /> | <img align="center" alt="서비스 선택" src="./img/서비스선택.PNG" width="240px" /> | <img align="center" alt="도시 선택" src="./img/장소선택.PNG" width="240px" /> |

| **장소 리스트** |  **장소 상세 페이지**  |  **위치 보여주기** |  **길찾기 상세 페이지** |
| :---:|:---:|:---:|:---:|
| <img align="center" alt="장소 리스트" src="./img/장소리스트.jpg" width="240px" /> | <img align="center" alt="장소 상세 페이지" src="./img/장소상세페이지.jpg" width="240px" /> | <img align="center" alt="위치 보여주기" src="./img/길찾기.jpg" width="240px" /> | <img align="center" alt="길찾기 상세 페이지" src="./img/길찾기상세.jpg" width="240px" /> |

| **회원가입** |  **프로필 사진 편집**  |  **로그인** |
| :---:|:---:|:---:|
| <img align="center" alt="회원가입" src="./img/회원가입.jpg" width="240px" /> | <img align="center" alt="프로필 사진 편집" src="./img/이미지크롭.jpg" width="240px" /> | <img align="center" alt="로그인" src="./img/로그인.PNG" width="240px" /> |

| **아이디 찾기** |  **비밀번호 찾기**  |  **약관 페이지** |
| :---:|:---:|:---:|
| <img align="center" alt="아이디 찾기" src="./img/아이디찾기.jpg" width="240px" /> | <img align="center" alt="비밀번호 찾기" src="./img/비밀번호찾기.jpg" width="240px" /> |  <img align="center" alt="약관 페이지" src="./img/이용약관.jpg" width="240px" /> |

| **관리자 메뉴** |  **회원관리**  |  **업체관리** |
| :---:|:---:|:---:|
| <img align="center" alt="관리자 메뉴" src="./img/관리자 화면.PNG" width="240px" /> | <img align="center" alt="회원 관리" src="./img/관리자회원관리.PNG" width="240px" /> | <img align="center" alt="업체관리" src="./img/관리자업체관리페이지.PNG" width="240px" /> |

| **관리자-회원조회** |  **관리자-회원상세조회**  |  **관리자-리뷰조회** |
| :---:|:---:|:---:|
| <img align="center" alt="회원조회" src="./img/관리자회원조회.PNG" width="240px" /> | <img align="center" alt="회원상세조회" src="./img/관리자회원상세조회.PNG" width="240px" /> | <img align="center" alt="리뷰조회" src="./img/관리자리뷰조회.PNG" width="240px" /> |

| **관리자-포인트회원조회** |  **관리자-포인트상세회원조회**  |  **관리자-업체전체필터링조회** |
| :---:|:---:|:---:|
| <img align="center" alt="포인트회원조회" src="./img/관리자포인트회원 조회.PNG" width="240px" /> | <img align="center" alt="포인트상세회원조회" src="./img/관리자포인트상세조회.PNG" width="240px" /> | <img align="center" alt="업체전체필터링조회" src="./img/관리자업체전체필터링조회.PNG" width="240px" /> |

| **관리자-업체상세조회** |  **관리자-관리자반려**  |  **관리자-업체전체필터링조회** |
| :---:|:---:|:---:|
| <img align="center" alt="업체상세조회" src="./img/관리자업체상세조회.PNG" width="240px" /> | <img align="center" alt="관리자반려" src="./img/관리자반려.PNG" width="240px" /> | <img align="center" alt="업체전체필터링조회" src="./img/관리자업체전체필터링조회.PNG" width="240px" /> |

