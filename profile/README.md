<img width="256" height="256" alt="insidemovie" src="https://github.com/user-attachments/assets/be84822a-158a-40d1-a0f3-f1b5b0d20adf" />

<br/>
<br/>

# 1. Project Overview (프로젝트 개요)
- 프로젝트 이름: 인사이드 무비 (Inside Movie)
- 프로젝트 설명: 사용자 감정 기반의 맟춤 영화 서비스

<br/>
<br/>

# 2. Team Members (팀원 및 팀 소개)
| **송창용** | 채상윤 | 김대환 | 양지선 | 김소희 | 이종진 |
|:------:|:------:|:------:|:------:|:------:|:------:|
| <img src="https://avatars.githubusercontent.com/u/84127378?v=4" alt="송창용" width="150"> | <img src="https://avatars.githubusercontent.com/u/28301831?v=4" alt="채상윤" width="150"> | <img src="https://avatars.githubusercontent.com/u/154658933?v=4" alt="김대환" width="150"> | <img src="https://avatars.githubusercontent.com/u/112966788?v=4" alt="양지선" width="150"> | <img src="https://avatars.githubusercontent.com/u/83942772?v=4" alt="김소희" width="150"> | <img src="https://avatars.githubusercontent.com/u/34650789?v=4" alt="이종진" width="150"> |
| BackEnd<br/>AI<br/>CI/CD | FrontEnd<br/>BackEnd | BackEnd<br/>AI | BackEnd | BackEnd | FrontEnd |
| [GitHub](https://github.com/et007693) | [GitHub](https://github.com/Sangyoon98) | [GitHub](https://github.com/Gumraze-git) | [GitHub](https://github.com/yangjiseonn) | [GitHub](https://github.com/ksoheee) | [GitHub](https://github.com/Lee-Jong-Jin) |

<br/>
<br/>

# 3. Key Features (주요 기능)
- **인공지능 기반의 복합 감정 리뷰 분석**:
  - KoBERT 모델을 이용하여 리뷰의 복합 감정 상태 분석
  - 사용자 리뷰 집계를 통하여 영화의 대표 감정 프로필 생성

- **사용자 감정 매핑 및 맞춤 추천**:
  - 좋아요 한 영화를 기반으로 복합 감정 프로필 생성
  - 사용자 감정 벡터와 영화 감정 벡터의 코사인 유사도 연산으로 관련도가 높은 영화 추천

- **주간 영화 대결 & 투표**:
  - 스케쥴러를 활용하여 일주일마다 자동으로 대결 생성
  - 감정 상태별 대표 영화 세 가지 선정
  - 역대 대결 내역 우승 영화 확인

<br/>
<br/>

# 4. Tasks & Responsibilities (작업 및 역할 분담)
|  |  |  |
|-----------------|-----------------|-----------------|
| 송창용    |  <img src="https://avatars.githubusercontent.com/u/84127378?v=4" alt="송창용" width="100"> | <ul><li>팀 리딩 및 커뮤니케이션</li><li>CI / CD</li><li>백엔드 개발</li><li>AI 개발</li></ul>     |
| 채상윤   |  <img src="https://avatars.githubusercontent.com/u/28301831?v=4" alt="채상윤" width="100">| <ul><li>사용자 페이지 프론트엔드 개발</li><li>백엔드 개발</li></ul> |
| 김대환   |  <img src="https://avatars.githubusercontent.com/u/154658933?v=4" alt="김대환" width="100">    |<ul><li>백엔드 개발</li><li>AI 개발</li></ul>  |
| 양지선    |  <img src="https://avatars.githubusercontent.com/u/112966788?v=4" alt="양지선" width="100">    | <ul><li>백엔드 개발</li></ul>    |
| 김소희    |  <img src="https://avatars.githubusercontent.com/u/83942772?v=4" alt="김소희" width="100">    | <ul><li>백엔드 개발</li></ul>    |
| 이종진    |  <img src="https://avatars.githubusercontent.com/u/34650789?v=4" alt="이종진" width="100">    | <ul><li>관리자 페이지 프론트엔드 개발</li></ul>    |

<br/>
<br/>

# 5. Technology Stack (기술 스택)
|  |  |
|-----------------|-----------------|
| FrontEnd   |<img src="https://skills.syvixor.com/api/icons?i=typescript,react,tailwindcss,mui"/>| 
| BackEnd    |<img src="https://skills.syvixor.com/api/icons?i=java,springboot,jwt,mysql"/>|
| AI   |<img src="https://skills.syvixor.com/api/icons?i=python,fastapi"/>|
| Infra      |<img src="https://skills.syvixor.com/api/icons?i=jenkins,docker,nginx,aws"/>|
| Cooperation     |<img src="https://skills.syvixor.com/api/icons?i=notion,figma,github"/>|

<br/>
<br/>

# 6. Project Structure (프로젝트 구조)

## 6-1. FrontEnd
```plaintext
src
├── api
│   ├── axiosInstance.ts
│   ├── boxofficeApi.ts
│   ├── matchApi.ts
│   ├── memberApi.ts
│   ├── movieApi.ts
│   ├── recommendApi.ts
│   └── reviewApi.ts
├── App.css
├── App.tsx
├── assets
│   ├── appleTV+.png
│   ├── arrow_down.svg
│   ├── arrow_left.svg
│   ├── arrow_right.svg
│   ├── arrow_up.svg
│   ├── background_bubble.svg
│   ├── boxoffice_icon.svg
│   ├── calendar.svg
│   ├── character
│   ├── check.svg
│   ├── close.svg
│   ├── delete.svg
│   ├── disneyPlus.png
│   ├── down.svg
│   ├── edit.svg
│   ├── home_icon.svg
│   ├── insidemovie_blue_land.svg
│   ├── insidemovie_dark_long.svg
│   ├── insidemovie_white_long.svg
│   ├── insidemovie_white.png
│   ├── kakao.png
│   ├── like.svg
│   ├── logout.svg
│   ├── mail.svg
│   ├── match_icon.svg
│   ├── movie_background.png
│   ├── movie_icon.svg
│   ├── my_page.svg
│   ├── netflix.png
│   ├── nickname.svg
│   ├── password.svg
│   ├── profile
│   ├── report.svg
│   ├── sample_poster.png
│   ├── search.svg
│   ├── star_empty.svg
│   ├── star_full.svg
│   ├── star_half.svg
│   ├── styles
│   ├── TMDB.svg
│   ├── unlike.svg
│   ├── up.svg
│   ├── visibility_off.svg
│   ├── visibility_on.svg
│   ├── watcha.png
│   └── wavve.png
├── components
│   ├── BoxOfficeItem.tsx
│   ├── Button.tsx
│   ├── ConfirmDialog.tsx
│   ├── EmotionSlider.tsx
│   ├── Header.tsx
│   ├── home
│   ├── InputField.tsx
│   ├── MovieItem.tsx
│   ├── mypage
│   ├── MyReviewItem.tsx
│   ├── ReviewItem.tsx
│   ├── StarRating.tsx
│   ├── Tag.tsx
│   ├── TransparentBox.tsx
│   └── WinnerItem.tsx
├── fonts
│   ├── Paperlogy-1Thin.ttf
│   ├── Paperlogy-2ExtraLight.ttf
│   ├── Paperlogy-3Light.ttf
│   ├── Paperlogy-4Regular.ttf
│   ├── Paperlogy-5Medium.ttf
│   ├── Paperlogy-6SemiBold.ttf
│   ├── Paperlogy-7Bold.ttf
│   ├── Paperlogy-8ExtraBold.ttf
│   └── Paperlogy-9Black.ttf
├── index.css
├── interfaces
│   ├── boxOffice.ts
│   ├── movieOne.ts
│   └── review.ts
├── main.tsx
├── pages
│   ├── admin
│   └── user
├── services
│   ├── authorityFormating.ts
│   ├── calcPercentChange.ts
│   ├── dateFormating.ts
│   ├── mapMembersToRows.ts
│   ├── mapReportsToRows.ts
│   └── timeForToday.ts
├── types
│   ├── dashboardData.ts
│   ├── member.ts
│   ├── report.ts
│   ├── reportStatus.ts
│   └── svg.d.ts
└── vite-env.d.ts
```

## 6-2. BackEnd
```
src/main
├── java
│   └── com
│       └── insidemovie
│           └── backend
│               ├── api
│               │   ├── admin
│               │   │   ├── controller
│               │   │   │   └── AdminController.java
│               │   │   ├── dto
│               │   │   │   ├── AdminDashboardDTO.java
│               │   │   │   ├── AdminMemberDTO.java
│               │   │   │   ├── AdminReportDTO.java
│               │   │   │   └── TimeCountDTO.java
│               │   │   └── service
│               │   │       └── AdminService.java
│               │   ├── constant
│               │   │   ├── Authority.java
│               │   │   ├── EmotionType.java
│               │   │   ├── GenreType.java
│               │   │   ├── MovieLanguage.java
│               │   │   ├── ReportReason.java
│               │   │   ├── ReportStatus.java
│               │   │   └── ReviewSort.java
│               │   ├── Email
│               │   │   ├── controller
│               │   │   │   └── EmailController.java
│               │   │   └── Service
│               │   │       └── EmailService.java
│               │   ├── friend
│               │   │   └── entity
│               │   │       └── Friend.java
│               │   ├── jwt
│               │   │   ├── JwtFilter.java
│               │   │   └── JwtProvider.java
│               │   ├── match
│               │   │   ├── controller
│               │   │   │   └── MatchController.java
│               │   │   ├── dto
│               │   │   │   └── WinnerHistoryDto.java
│               │   │   ├── entity
│               │   │   │   ├── Match.java
│               │   │   │   ├── MovieMatch.java
│               │   │   │   └── Vote.java
│               │   │   ├── repository
│               │   │   │   ├── MatchRepository.java
│               │   │   │   ├── MovieMatchRepository.java
│               │   │   │   └── VoteRepository.java
│               │   │   ├── scheduler
│               │   │   │   └── MatchScheduler.java
│               │   │   └── service
│               │   │       └── MatchService.java
│               │   ├── member
│               │   │   ├── controller
│               │   │   │   └── MemberController.java
│               │   │   ├── dto
│               │   │   │   ├── emotion
│               │   │   │   │   ├── EmotionAvgDTO.java
│               │   │   │   │   ├── MemberEmotionSummaryRequestDTO.java
│               │   │   │   │   └── MemberEmotionSummaryResponseDTO.java
│               │   │   │   ├── KakaoUserInfoDto.java
│               │   │   │   ├── MemberInfoDto.java
│               │   │   │   ├── MemberLoginRequestDto.java
│               │   │   │   ├── MemberLoginResponseDto.java
│               │   │   │   ├── MemberSignupRequestDto.java
│               │   │   │   ├── NicknameCheckResponseDTO.java
│               │   │   │   ├── NicknameUpdateRequestDTO.java
│               │   │   │   ├── PasswordUpdateRequestDTO.java
│               │   │   │   ├── ProfileEmotionUpdateRequestDto.java
│               │   │   │   ├── TokenRequestDto.java
│               │   │   │   └── TokenResponseDto.java
│               │   │   ├── entity
│               │   │   │   ├── Member.java
│               │   │   │   └── MemberEmotionSummary.java
│               │   │   ├── repository
│               │   │   │   ├── MemberEmotionSummaryRepository.java
│               │   │   │   ├── MemberLikeRepository.java
│               │   │   │   └── MemberRepository.java
│               │   │   └── service
│               │   │       ├── MemberEmotionSummaryService.java
│               │   │       ├── MemberService.java
│               │   │       └── OAuthService.java
│               │   ├── movie
│               │   │   ├── config
│               │   │   │   ├── RedisConfig.java
│               │   │   │   └── RestTemplateConfig.java
│               │   │   ├── controller
│               │   │   │   ├── BoxOfficeController.java
│               │   │   │   └── MovieController.java
│               │   │   ├── dto
│               │   │   │   ├── boxoffice
│               │   │   │   │   ├── BaseBoxOfficeItemDTO.java
│               │   │   │   │   ├── BoxOfficeListDTO.java
│               │   │   │   │   ├── BoxOfficeRequestDTO.java
│               │   │   │   │   ├── DailyBoxOfficeResponseDTO.java
│               │   │   │   │   └── WeeklyBoxOfficeResponseDTO.java
│               │   │   │   ├── emotion
│               │   │   │   │   ├── MovieEmotionResDTO.java
│               │   │   │   │   └── MovieEmotionSummaryResponseDTO.java
│               │   │   │   ├── MovieDetailResDto.java
│               │   │   │   ├── MovieDetailSimpleResDto.java
│               │   │   │   ├── MovieSearchReqDto.java
│               │   │   │   ├── MovieSearchResDto.java
│               │   │   │   ├── MyMovieResponseDTO.java
│               │   │   │   ├── PageResDto.java
│               │   │   │   ├── PaginatedResponse.java
│               │   │   │   ├── RecommendedMovieReqDto.java
│               │   │   │   ├── RecommendedMovieResDto.java
│               │   │   │   ├── tmdb
│               │   │   │   │   ├── CastDTO.java
│               │   │   │   │   ├── CountryProvidersDTO.java
│               │   │   │   │   ├── CreditsDTO.java
│               │   │   │   │   ├── CrewDTO.java
│               │   │   │   │   ├── MovieDetailDTO.java
│               │   │   │   │   ├── ProviderDTO.java
│               │   │   │   │   ├── ReleaseDateDTO.java
│               │   │   │   │   ├── ReleaseDateResultDTO.java
│               │   │   │   │   ├── ReleaseDatesDTO.java
│               │   │   │   │   ├── SearchMovieResponseDTO.java
│               │   │   │   │   ├── SearchMovieWrapperDTO.java
│               │   │   │   │   └── WatchProviderDTO.java
│               │   │   │   └── TmdbGenreResponseDto.java
│               │   │   ├── entity
│               │   │   │   ├── boxoffice
│               │   │   │   │   ├── DailyBoxOfficeEntity.java
│               │   │   │   │   └── WeeklyBoxOfficeEntity.java
│               │   │   │   ├── Movie.java
│               │   │   │   ├── MovieEmotionSummary.java
│               │   │   │   ├── MovieGenre.java
│               │   │   │   ├── MovieHistory.java
│               │   │   │   └── MovieLike.java
│               │   │   ├── repository
│               │   │   │   ├── DailyBoxOfficeRepository.java
│               │   │   │   ├── MovieEmotionSummaryRepository.java
│               │   │   │   ├── MovieGenreRepository.java
│               │   │   │   ├── MovieLikeRepository.java
│               │   │   │   ├── MovieRepository.java
│               │   │   │   └── WeeklyBoxOfficeRepository.java
│               │   │   ├── scheduler
│               │   │   │   ├── DailyBoxOfficeScheduler.java
│               │   │   │   ├── MovieSeedScheduler.java
│               │   │   │   ├── MovieUpdateScheduler.java
│               │   │   │   └── WeeklyBoxOfficeScheduler.java
│               │   │   └── service
│               │   │       ├── BoxOfficeService.java
│               │   │       ├── MovieDetailService.java
│               │   │       ├── MovieEmotionSummaryService.java
│               │   │       ├── MovieLikeService.java
│               │   │       └── MovieService.java
│               │   ├── recommend
│               │   │   ├── controller
│               │   │   │   └── EmotionRecommendationController.java
│               │   │   ├── dto
│               │   │   │   ├── EmotionRequestDTO.java
│               │   │   │   ├── MovieRecommendationDTO.java
│               │   │   │   └── MovieSimilarityResDto.java
│               │   │   └── service
│               │   │       └── EmotionRecommendationService.java
│               │   ├── report
│               │   │   ├── controller
│               │   │   │   └── ReportController.java
│               │   │   ├── dto
│               │   │   │   └── ReportResponseDTO.java
│               │   │   ├── entity
│               │   │   │   └── Report.java
│               │   │   ├── repository
│               │   │   │   └── ReportRepository.java
│               │   │   └── service
│               │   │       └── ReportService.java
│               │   └── review
│               │       ├── controller
│               │       │   └── ReviewController.java
│               │       ├── dto
│               │       │   ├── EmotionDTO.java
│               │       │   ├── MyReviewResponseDTO.java
│               │       │   ├── PredictRequestDTO.java
│               │       │   ├── PredictResponseDTO.java
│               │       │   ├── ReviewCreatedResponseDTO.java
│               │       │   ├── ReviewCreateDTO.java
│               │       │   ├── ReviewResponseDTO.java
│               │       │   └── ReviewUpdateDTO.java
│               │       ├── entity
│               │       │   ├── Emotion.java
│               │       │   ├── Review.java
│               │       │   └── ReviewLike.java
│               │       ├── repository
│               │       │   ├── EmotionRepository.java
│               │       │   ├── ReviewLikeRepository.java
│               │       │   └── ReviewRepository.java
│               │       └── service
│               │           └── ReviewService.java
│               ├── BackendApplication.java
│               └── common
│                   ├── advice
│                   │   └── ControllerExceptionAdvice.java
│                   ├── config
│                   │   ├── db
│                   │   │   └── DatabaseInitializer.java
│                   │   ├── security
│                   │   │   └── SecurityConfig.java
│                   │   ├── swagger
│                   │   │   └── SwaggerConfig.java
│                   │   └── WebClientConfig.java
│                   ├── entity
│                   │   └── BaseTimeEntity.java
│                   ├── exception
│                   │   ├── BadRequestException.java
│                   │   ├── BaseException.java
│                   │   ├── ExternalServiceException.java
│                   │   ├── ForbiddenException.java
│                   │   ├── IllegalStateException.java
│                   │   ├── InternalServerException.java
│                   │   ├── NotFoundException.java
│                   │   └── UnAuthorizedException.java
│                   └── response
│                       ├── ApiResponse.java
│                       ├── ErrorStatus.java
│                       ├── PageResult.java
│                       └── SuccessStatus.java
└── resources
    ├── application-key.yml
    ├── application-local.yml
    ├── application-prod.yml
    └── application.yml

```

## 6-3. AI
```
├── __pycache__
│   ├── config.cpython-312.pyc
│   ├── const.cpython-312.pyc
│   ├── database.cpython-312.pyc
│   ├── main.cpython-312.pyc
│   ├── models.cpython-312.pyc
│   └── schemas.cpython-312.pyc
├── config.py
├── const.py
├── database.py
├── Dockerfile
├── environment.yml
├── main.py
├── models
│   └── 0717_kobert_5_emotion_model
│       ├── config.json
│       ├── model.safetensors
│       ├── special_tokens_map.json
│       ├── spiece.model
│       └── tokenizer_config.json
├── models.py
├── README.md
├── requirements.txt
├── routers
│   ├── __init__.py
│   ├── __pycache__
│   │   ├── __init__.cpython-312.pyc
│   │   ├── home.cpython-312.pyc
│   │   ├── predict.cpython-312.pyc
│   │   └── recommend.cpython-312.pyc
│   ├── home.py
│   ├── predict.py
│   ├── recommend.py
│   └── review.py
├── schemas.py
└── services
    ├── __pycache__
    │   └── prediction.cpython-312.pyc
    └── prediction.py
```

# 7. ScreenShots (캡쳐화면)
## 7.1 로그인 & 회원가입
![1](https://github.com/user-attachments/assets/8d73e847-39da-43e8-bf52-9102e6c048dc)
![2](https://github.com/user-attachments/assets/1f702fa2-c285-40e9-a81d-c5b466c101e5)
![3](https://github.com/user-attachments/assets/a12ae237-b06d-42b4-a0b3-86ae4d540823)
![4](https://github.com/user-attachments/assets/c98dea8e-6a60-4487-81d2-83ba4839e268)
![5](https://github.com/user-attachments/assets/12c274e5-11e0-48e7-8e38-3a245aa1ebc0)
![6](https://github.com/user-attachments/assets/81f263a1-3d6e-4295-acca-d2e7ef3617a8)
![7](https://github.com/user-attachments/assets/476ff8ca-d248-49cf-a245-96d62e526494)
![8](https://github.com/user-attachments/assets/93e34c4a-0ab3-4041-9cfc-083af3947585)

## 7.2 홈 화면
![9](https://github.com/user-attachments/assets/c9b92a36-8ef3-426b-ac36-569958014164)
![10](https://github.com/user-attachments/assets/1b2fceec-2aa5-4800-9c8a-efcdd9600a0b)

## 7.3 추천 영화
![11](https://github.com/user-attachments/assets/151633e1-f4d6-4dd9-bbe5-c98b124ea392)

## 7.4 박스오피스 순위
![12](https://github.com/user-attachments/assets/68f4d52c-3a20-4e3f-859e-63a413187f4a)

## 7.5 금주의 영화 대결
![13](https://github.com/user-attachments/assets/8707c81d-c946-44dc-8b71-34f6b698fca3)

## 7.6 영화 상세
![14](https://github.com/user-attachments/assets/606e252d-822d-475e-9318-73d36372d51c)

## 7.7 리뷰 작성 및 수정
![15](https://github.com/user-attachments/assets/40dbfe64-a217-47b8-b9a7-836986694e76)

## 7.8 마이페이지
![16](https://github.com/user-attachments/assets/20a0caea-6159-4094-8c56-a35f031b98b7)

## 7.9 관리자 페이지
![17](https://github.com/user-attachments/assets/589046e8-6073-41cb-be49-00aa8cd1acf8)
![18](https://github.com/user-attachments/assets/18953101-3f1e-420b-aae7-f298c4a09b34)
![19](https://github.com/user-attachments/assets/b7fcb194-d621-4e49-9b30-8d4fec66739b)
![20](https://github.com/user-attachments/assets/b1217ced-6524-409d-b516-91042445ac57)
![21](https://github.com/user-attachments/assets/806ec1ef-6414-4281-b6fb-c9a5b7323b2d)
