
![header](https://capsule-render.vercel.app/api?type=cylinder&color=4cd137&height300&section=header&text=창환's%20GIT&fontSize=60)


🐷profile
-
1996.01.13

가톨릭대학교 환경공학과 졸업

Android Developer

hobby : wrestling, ju-jitsu

✍️TechStack
-
 📌used as the main
   
<img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=Android&logoColor=white"> <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white"> <img src="https://img.shields.io/badge/Java-40739e?style=for-the-badge&logo=&logoColor=white">

❗️used at least once

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"> <img src="https://img.shields.io/badge/Html-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"> <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"> <img src="https://img.shields.io/badge/Vue-FC08D?style=for-the-badge&logo=Vue.js&logoColor=white">



🐗 ABOUT ME 🐗
-
<a href="https://mccoy-devloper.tistory.com/" target="_blank"><img src="https://img.shields.io/badge/Tistory Blog-000000?style=flat-square&logo=Tistory&logoColor=white"/></a> [멧돼지의 개발블로그](https://mccoy-devloper.tistory.com/)

<a href="https://caf-android.tistory.com/" target="_blank"><img src="https://img.shields.io/badge/Tistory Blog-7f8fa6?style=flat-square&logo=Tistory&logoColor=white"/></a> [앙큼이 여우 스터디 팀블로그](https://caf-android.tistory.com/)

📎Project,Activity🖇
-
-   2019
    -   7월~8월 :  [2019 와디즈 크라우드펀딩 아이디어 공모전](https://www.venturesquare.net/789592)
-   2021
    -   1월~2월 :  [말랑(커플다이어리)](https://github.com/tnvnfdla1214/Malang)
    -   7월~12월 : SOPT 29기 Android 파트 활동 [29기 과제](https://github.com/29th-WE-SOPT-Android-Part/Android-Changhwan)
    -   12월 ~1월 : [Spark](https://github.com/TeamSparker) Android 개발 리드로 참여 (2022.09.21 현재 업데이트중)
-   2022
    -   3월~8월 :  SOPT 30기 Android 파트 활동 [30기 과제](https://github.com/macbook-plz-30th-THE-SOPT-android-team4/30th-ChangHwan)
    -   4월~9월 :  [READ-ME](https://github.com/TEAM-README) Android 개발로 참여 (2022.10월 중 출시예정)
    -   7월~ :  [Photo-Surfer](https://github.com/TeamPhotoSurfer) Android 리드로 참여 (현재 개발중)
 
### -프로젝트별 기술 및 담당 개발사항 정리
<details>
<summary>Spark</summary>
<div markdown="1">

프로젝트 1줄 설명 : 친구와 함께하는 66일간의 습관 형성 서비스!

### 👉 **프로젝트 스펙 명시**

> 아키텍쳐 패턴 : MVVM
> 
> 디자인 패턴 : Repository Pattern(통신 시), Observer Pattern(Livedata), Delegation Pattern 
> 
> AAC : Databinding, Livedata, ViewModel, ViewPager2
> 
> 통신 : OkHttp3, Retrofit2
> 
> Async Task : Coroutine
> 
> Third Party Library : Glide
> 
> 협업 : Git flow
> 
> DI : Hilt

### 담당 개발 사항
>-아래 작성한 flow들을 개발하였고 그 중 특징적인 것들을 정리해 보았습니다.

> 2-1홈화면
> 
> -홈화면 습관방 별 상태값에 따른 뷰 분기처리 
> 
> -홈 각 토스트,버튼 애니메이션처리
> 
> -상태값에 따라 다이얼로그를 통한 정보전달
> 
> -무한스크롤 구현으로 부드러운 사용성 제공

> 2-2습관방 생성
> 
> -습관방을 종류별로 생성할수있도록 분기처리
> 
> -사용자와 상호작용하도록 중간페이지 구성
> 
> -요소별 애니메이션 적용으로 부드러운 사용성 제공

> 2-3코드로 참여
> 
> -다이얼로그를 통한 코드입력처리
> 
> -서버의 에러메시지를 받아서 화면에 띄워주는 네트워크 통신처리(네트워크 상황(오류)별 분기처리)

> 2-4대기방
> 
> -glide를 통한 이미지처리 
> 
> -사용자와 상호작용할수있는 info 버튼 구현

> 2-5목표작성
> 
> -object animator 를 통한 edittext 포커스시 화면전환 구현


</div>
</details>

<details>
<summary>READ-ME</summary>
<div markdown="1">

프로젝트 1줄 설명 : 사람들과 공유하는 독서록 서비스

### 👉 **프로젝트 스펙 명시**
> 아키텍쳐 패턴 : MVVM
> 
> 디자인 패턴 :  Repository Pattern, Observer Pattern(Livedata), Delegation Pattern, Multi Module
> 
> AAC : Databinding, Livedata, ViewModel, Navigation
> 
> 통신 : OkHttp3, Retrofit2
> 
> Async Task : Coroutine(Flow)
> 
> Third Party Library : coil, Timber
> 
> 협업 : Git flow
> 
> DI : Hilt

### 담당 개발 사항
>  아래 작성한 flow들을 개발하였고 그중 특징적인 것들을 정리해보았습니다.

> 각종 기초세팅 -> style guide,패키징,text style 등등 

> DI 기초 세팅 모듈 관련 세팅

> 오류처리를 자세하게 작성하기위해 retrofit 의 callAdapter를 커스텀 오류처리의 다양화,오류처리 관련 코드의 가독성을 좋게 만듬
>
> [사용기술을 정리한 글](https://mccoy-devloper.tistory.com/58?category=494185).

> 소셜 로그인 네이버 카카오 및 로그인 관련 전반적인 토큰관리 코드 작성 401관련 에러 coroutine exception handler 를 통한 처리
> 
> [코드를 정리한 글](https://mccoy-devloper.tistory.com/59?category=494185)

> 네이버 책검색 api 연동 

> 닉네임 설정뷰
> 
>네임 설정뷰 작업 정규표현식을 통한 규칙부여

> 책검색 뷰
> 
>네이버 책검색 api 연동시 다양하게 들어오는 null 값 처리 및 오류사항 대응 

> 글쓰기 뷰
>  
>여러 화면을 거쳐서 통신을 한번에 해야하므로 ActivityViewModel 을 사용 처리

</div>
</details>


<details>
<summary>Photo-Surfer</summary>
<div markdown="1">

프로젝트 1줄 설명 : 사진에 태그를 달아서 관리해보자!!

### 아직 기초적인 개발만 시작한 프로젝트

### 👉 **프로젝트 스펙 명시**
> 아키텍쳐 패턴 : MVVM
> 
> 디자인 패턴 :  Repository Pattern, Observer Pattern(Livedata), Delegation Pattern, Multi Module
> 
> AAC : Databinding, Livedata, ViewModel, Navigation
> 
> 통신 : OkHttp3, Retrofit2
> 
> Async Task : Coroutine
> 
> Third Party Library : Glide, Timber
> 
> 협업 : Git flow
> 
> DI : Hilt

### 담당 개발 사항
>  아래 작성한 flow들을 개발하였고 그중 특징적인 것들을 정리해보았습니다.

> 멀티모듈 기초세팅

> 기타 유틸 세팅,timber,hilt등 기초세팅

> 푸시 알림 기능 구현

> 소셜로그인 및 로그인 관련 토근 작업 기초세팅

> 화면 전환용 navigator 로직 세팅

> [포토서퍼 모듈 의존성 관계도](https://www.notion.so/go-photosurfer/eab5d5b6eb244cad8999b013dc1db180).


</div>
</details>
