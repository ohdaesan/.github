💻 프로젝트 소개
힘든 삶 속에서 대학생으로 회귀한다면?.. 청춘 남녀들의 잊지 못할 대학생 체험기 가상 대학생활을 몸소 체험하며 두근두근함을 느끼는 우리는 청춘대🎀 두근두근 청춘❤

청춘 남녀들의 잊지 못할 대학생 체험기 가상 대학생활을 몸소 체험하며 두근두근함을 느끼는 우리는 청춘대🎀 두근두근 청춘❤

⌨️ 개발 기간
7월 10일 ~ 8월 14일
🧑‍🤝‍🧑 멤버구성
팀원1 : 지동현
팀원2 : 박성은
팀원3 : 배하은
팀원4 : 이의정
⚙️ 개발 환경
Html Css JavaScript Java Spring
SpringBoot SpringSecurity MySQL Timeleaf

💻 ...
GitHub

프론트 패키지 구조
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

백엔드 패키지 구조
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
